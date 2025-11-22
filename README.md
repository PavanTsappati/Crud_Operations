# CRUD Operations – Spring Boot + JSP Project

This project is a simple and clean **CRUD (Create, Read, Update, Delete)** web application built using **Spring Boot, JSP, Hibernate/JPA, and MySQL**.  
Users can add, update, view, and delete employee records through a user-friendly web interface.

---

## 📸 Application Screenshot

![CRUD Page](/mnt/data/Crud page.png)

*(GitHub lo image upload chesaka, ee path ni RAW URL tho replace cheyyandi.)*

---

## 🚀 Features

- Add new employee
- View employees list
- Update employee details
- Delete employee
- MySQL DB integration
- JSP UI pages
- Clean Maven project structure

---

## 🛠️ Tech Stack

| Layer | Technology |
|------|------------|
| Backend | Spring Boot |
| Frontend | JSP, HTML, CSS |
| Build Tool | Maven |
| ORM | Hibernate / JPA |
| Database | MySQL |
| Server | Embedded Tomcat |

---

## 📂 Project Structure


---

## ⚙️ Setup & Installation

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/yourusername/Crud_Operations-main.git
cd Crud_Operations-main
CREATE DATABASE crud_app;
spring.datasource.url=jdbc:mysql://localhost:3306/crud_app
spring.datasource.username=root
spring.datasource.password=yourpassword
spring.jpa.hibernate.ddl-auto=update
mvn spring-boot:run
