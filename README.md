# FirstApiSpring – Product REST API

## 📌 Project Description

**FirstApiSpring** is a simple REST API application built with **Spring Boot**.
It provides basic **CRUD operations** (Create, Read, Update, Delete) for managing products.

The application uses an **in-memory H2 database** and includes **Swagger UI** for automatic API documentation and testing.

---

## 🛠️ Technologies Used

* **Java**
* **Spring Boot**
* **Spring Web**
* **Spring Dependency Injection**
* **In-memory database (Map-based repository)**
* **H2 Database**
* **Springdoc OpenAPI (Swagger UI)**

---

## ▶️ How to Run the Application

1. Clone this repository to your local machine.
2. Open the project folder in **IntelliJ IDEA**.
3. Run the file:

   ```
   FirstRestApiSpringApplication.java
   ```
4. The server will start at:

   ```
   http://localhost:8080
   ```

---

## 📖 API Documentation (Swagger UI)

Swagger UI is automatically generated and provides a complete overview of all available endpoints.

Access it here:

```
http://localhost:8080/swagger-ui/index.html
```

### Swagger Overview

![Swagger Overview](img.png)

---

## 🔗 Available Endpoints

### 1️⃣ Create Product (POST)

Creates a new product in the database.

![Create Product](img_1.png)
![Create Product Result](img_2.png)

---

### 2️⃣ Get All Products (GET)

Returns a list of all products.

![Get All Products](img_4.png)
![Get All Products Result](img_5.png)

---

### 3️⃣ Get Product by ID (GET)

Returns a single product based on its ID.

![Get Product by ID](img_6.png)

---

### 4️⃣ Update Product (PUT)

Updates an existing product.

![Update Product](img_7.png)
![Update Product Result](img_8.png)

---

### 5️⃣ Delete Product (DELETE)

Deletes a product by its ID.

![Delete Product](img_10.png)
![Delete Product Result](img_11.png)

---

## 🗄️ H2 Database Console

You can view and manage the H2 in-memory database directly from your browser.

### Access Details

* **URL:** [http://localhost:8080/console](http://localhost:8080/console)
* **JDBC URL:** `jdbc:h2:mem:testdb`
* **User:** `sa`
* **Password:** *(leave blank)*

### Example SQL Query

```sql
SELECT * FROM PRODUCTS;
```

![H2 Database View](img_12.png)

---



