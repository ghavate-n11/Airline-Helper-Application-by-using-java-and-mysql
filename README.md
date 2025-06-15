# Airline Helper Application

## Project Description
The **Airline Helper Application** is a Java-based desktop application designed to simplify airline booking, flight management, and passenger details. Built using **Java (Swing, JDBC)** and **MySQL**, this application provides an efficient and user-friendly interface for managing flight-related activities.

## Features
- **User Registration & Login**
- **Add Customer Details**
- **Book & Cancel Flights**
- **Search Flights**
- **Generate Boarding Pass**
- **View Flight Information**
- **Database Integration with MySQL**
- **Secure Authentication System**

##Technologies Used
- **Java** (Swing for GUI, JDBC for Database Connectivity)
- **MySQL** (Database for storing flight and user data)
- **NetBeans / Eclipse** (Recommended IDE)
- **XAMPP / MySQL Workbench** (For Database Management)

##Installation Guide
### Prerequisites
- Install **JDK 11+**
- Install **MySQL Server**
- Install **NetBeans / Eclipse** (or any preferred IDE)
- Install **XAMPP (Optional for MySQL Management)**

### Steps to Run the Project
1. **Clone the Repository**
   ```sh
   git clone https://github.com/ghavate-n11/Airline-Helper-Application.git
   cd Airline-Helper-Application
   ```
2. **Set Up MySQL Database**
   - Create a new database `airline_db`
   - Import the provided `airline_db.sql` file into MySQL
3. **Configure Database in Java**
   - Open `Conn.java`
   - Update the database URL, username, and password
   ```java
   Connection con = DriverManager.getConnection("jdbc:mysql://localhost:3306/airline_db", "root", "password");
   ```
4. **Run the Application**
   - Open the project in NetBeans/Eclipse
   - Run the `Home.java` file
   - Login using test credentials or create a new account


## Contributors
- **Nilesh Ghavate** [Java Developer]
- **Tejas Bachute** [Frontend Developer]
- **Yash Ahire** [Sql Developer & Project Management]
