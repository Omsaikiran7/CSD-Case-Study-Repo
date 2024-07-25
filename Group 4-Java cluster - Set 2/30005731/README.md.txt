Car Service Appointment Scheduling System

This is a console-based application designed to manage car service appointments, customer information, and service details for an automobile service center. It is developed using Core Java and MySQL with JDBC for database interactions.

Features

- **Appointment Management**:
  - Schedule new service appointments
  - View appointment details
  - Update appointment information
  - Cancel appointments

- **Customer Management**:
  - Register new customers
  - View customer details
  - Update customer information
  - Delete customer accounts

- **Service Management**:
  - Add new services offered by the service center
  - View service details
  - Update service information
  - Delete services

Database Setup

1. Create a database named `carservicedb` in MySQL.
2. Create the necessary tables for customers, services, and appointments.

Project Setup

1. Clone the repository or download the project files.
2. Place the `mysql-connector-j-9.0.0.jar` file in the project directory.
3. Compile the Java files:

    javac -cp ".;mysql-connector-j-9.0.0.jar" *.java

4. Run the application:

    java -cp ".;mysql-connector-j-9.0.0.jar" Main