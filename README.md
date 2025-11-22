# CRUD Operations – Java + JDBC + MySQL Project

A simple and beginner-friendly **CRUD (Create, Read, Update, Delete)** console application developed using **Java, JDBC, and MySQL**.  
This project helps users manage employee records through a command-line interface.

---

## 📸 Project Preview

<p align="center">
  <img src="Crud Page.png" width="550">
</p>

> 🔧 After uploading the image to GitHub, click the image → copy **RAW link** → replace the image URL above.

---

## 🔥 Features

✔ Add new employee  
✔ View employee list  
✔ Update employee details  
✔ Delete employee record  
✔ Prevents duplicate entry based on ID  
✔ Console-based user interface  

---

## 🛠️ Technologies Used

| Technology | Purpose |
|-----------|---------|
| Java | Core logic |
| JDBC | Database connectivity |
| MySQL | Persistent data storage |
| Eclipse | Development environment |

---

## 📌 How the System Works

1️⃣ User launches the program  
2️⃣ Console displays menu with options:
- Add Employee  
- View Employees  
- Update Employee  
- Delete Employee  
- Exit  

3️⃣ Based on user input, database operations execute using JDBC  
4️⃣ Data is stored and updated securely in MySQL  

---

## 📂 Project Structure

```
Crud_Operations-main
├── src
│   ├── Main.java
│   ├── Employee.java
│   ├── DBConnection.java
│   └── EmployeeService.java
├── crud.sql
└── README.md
```

---

## ⚙️ Setup & Installation

### 1️⃣ Clone the Repository

```sh
git clone https://github.com/yourusername/Crud_Operations-main.git
cd Crud_Operations-main
```

### 2️⃣ Create MySQL Database

```sql
CREATE DATABASE crud_app;
```

### 3️⃣ Update Database Credentials in Code

```java
String url = "jdbc:mysql://localhost:3306/crud_app";
String username = "root";
String password = "YOUR_PASSWORD";
```

### 4️⃣ Run the Application

Execute `Main.java` from your IDE (Eclipse/IntelliJ/VS Code).

---

## 🚀 Future Enhancements

🔹 File-based logging  
🔹 GUI (Swing or JavaFX)  
🔹 Authentication system  
🔹 Deploy as REST API with Spring Boot  

---

### ⭐ Support

If you found this project useful, consider ⭐ starring the repository!

