# 📌 CRUD Operations using Spring Boot & REST APIs  

## 🔹 Overview  
This project demonstrates a **CRUD (Create, Read, Update, Delete) application** built with **Spring Boot**.  
It exposes RESTful APIs to manage **Product** details (`id`, `name`, `quantity`, `price`) and returns results in **JSON format**.  
APIs were tested and validated using **Postman** and **browser**.  

---

## 🔹 Features  
- ✅ Create a new product (**POST**)  
- ✅ Retrieve products (**GET**)  
- ✅ Update product details (**PUT**)  
- ✅ Delete a product (**DELETE**)  
- ✅ Verify responses in Postman and browser  

---

## 🔹 Tech Stack  
- **Language:** Java  
- **Framework:** Spring Boot  
- **Build Tool:** Maven  
- **API Format:** REST + JSON  
- **Testing Tool:** Postman  

---

## 🔹 API Endpoints  

| Method  | Endpoint             | Description              |
|---------|----------------------|--------------------------|
| POST    | `/addProduct`        | Add a new product        |
| GET     | `/products`          | Get all products         |
| GET     | `/products/{id}`     | Get product by ID        |
| PUT     | `/update/`           | Update product details   |
| DELETE  | `/delete/{id}`       | Delete product by ID     |

---

## 🔹 How to Run  

1. Clone this repository:  
   ```bash
   git clone https://github.com/PavanTsappati/Crud_Operations
