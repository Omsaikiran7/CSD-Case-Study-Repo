
# Case study-(75) 30005793

1.Install and set up Mysql workbench and Eclipse ide.

2.Install mySql connector jar file and initialize it with the ecclipse ide


install Mysql connector


```bash
wget https://dev.mysql.com/get/Downloads/Connector-J/mysql-connector-java-8.0.29.tar.gz
tar -xvf mysql-connector-java-8.0.29.tar.gz

```

 Move the JAR file to your project directory:
```bash
mkdir -p /path/to/your/project/lib
mv mysql-connector-java-8.0.29/mysql-connector-java-8.0.29.jar /path/to/your/project/lib/
```




## Tables 


The table member contains


| Name | Type     | 
| :-------- | :------- | 
| `member_id` | `primarykey` | 
| `name` | `varchar` | 
| `email` | `varchar` | 
| `phone_number` | `varchar` | 
| `membership_type` | `varchar` | 

The table trainer contains

| Name| Type     | 
| :-------- | :------- | 
| `trainer_id` | `primarykey` | 
| `name` | `varchar` | 
| `email` | `varchar` | 
| `phone_number` | `varchar` | 
| `specialization` | `varchar` | 

The table class contains

| Name| Type     | 
| :-------- | :------- | 
| `class_id` | `primarykey` | 
| `trainer_id` | `int` | 
| `class_name` | `varchar` | 
| `schedule` | `datetime` | 
| `capacity ` | `int` | 
| `status` | `enum` | 


## Appendix

Initialize the following fields with with your details




    static String  password =  "xxxx";
    static String dbms = "xxxx";
    static String serverName = "xxxx";
    static String portNumber = "xxxx";
    static String dbName = "members";
    static Connection connection = null;
