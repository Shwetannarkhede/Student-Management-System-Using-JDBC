# **📚 Student Management System (Console + JDBC)**
A simple Java-based console application that performs **CRUD operations on student records** using **JDBC**, designed with a clean modular architecture involving Controller, Service, and DAO layers.

## **✅ Features**
* ➕ Add a new student
* 📄 View all students
* 🔍 Search student by **ID**, **Name**, or **Course**
* 📝 Update student details
* ❌ Delete student
* 💡 Uses **MySQL database** with JDBC
* 🧱 Modular design (Controller, Service, DAO)

## **📁 Project Structure**

```
Student-Management-System-using-JDBC/
│
├── src/
│   ├── MainApp.java
│   │
│   ├── db/
│   │   └── DBConnection.java
│   │
│   └── service/
│       └── StudentService.java
│
├── lib/
└── README.md
```

## **🛠 Technologies Used**
* 💻 Java (JDK 8+)
* 🗃 MySQL
* 🔌 JDBC API
* 📦 Eclipse IDE (can also be run via IntelliJ or CLI)

## **🗄 Database Configuration**
Create a MySQL database:

```
CREATE DATABASE Management;
USE Management;

CREATE TABLE  Student (
id INT PRIMARY KEY,
 name VARCHAR(100) NOT NULL,
 course VARCHAR(100) NOT NULL);
```

Update DB credentials inside `DBConnection.java`:

```
String url = "jdbc:mysql://localhost:3306/studentdb";
String username = "root";
String password = "your_mysql_password";
```

## **🚀 How to Run**
1. Clone the repo:

```
git clone https://github.com/Shwetannarkhede/Student-Management-System-Using-JDBC.git
```

2. Open in Eclipse or any Java IDE
3. Run `MainApp.java`

## **📋 Prerequisites**
* Java Development Kit (JDK 8 or higher)
* MySQL Server
* JDBC Driver for MySQL
* IDE (Eclipse, IntelliJ IDEA, or VS Code)

## **🧑‍💻 Author**
**Shweta Nilkanth Narkhede**  🔗 [GitHub Profile](https://github.com/Shwetannarkhede)

## **📄 License**
This project is open-source and free to use under the MIT License.
