# Apache-MySQL-Conn-Test-using-Java

This project demonstrates a simple Java application that connects to a MySQL database using JDBC.

## Requirements

- Java Development Kit (JDK)
- XAMPP (or any MySQL server)
- MySQL Connector/J (JAR file)

## Setup

1. **Start MySQL Server:**
   - Launch XAMPP and start the MySQL service.

2. **Database Configuration:**
   - Create a database named `user_db`.
   - Create a table `registerinfo` with columns `username` (TEXT) and `password` (VARCHAR(255)).

3. **Java Setup:**
   - Ensure you have the MySQL Connector/J JAR file in your project directory.

4. **Compile and Run:**

   ```bash
   javac -cp ".;path\to\mysql-connector-j-9.0.0.jar" SimpleUserSystem.java
   java -cp ".;path\to\mysql-connector-j-9.0.0.jar" SimpleUserSystem
