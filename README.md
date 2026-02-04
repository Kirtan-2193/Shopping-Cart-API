# 🛍️ Shopping Cart API

A **RESTful Shopping Cart API** built using **Java Spring Boot** — designed to handle core cart operations such as adding items, updating quantities, removing items, and viewing cart contents. This API can be used as the backend for e-commerce applications or learning Spring Boot REST development.

---

## 🚀 Features

- 📦 Add products to a cart
- 🔄 Update cart item quantities
- ❌ Remove items from the cart
- 🧾 View cart contents
- 🚀 Built using Spring Boot with RESTful architecture

This project follows standard REST principles and is easily extensible for features such as authentication, product catalog services, order placement, etc.

---

## 🛠️ Tech Stack

| Technology       | Purpose |
|------------------|---------|
| **Java**         | Core language |
| **Spring Boot**  | REST API framework |
| **Spring Web**   | HTTP & REST controllers |
| **Spring Data JPA** *(optional)* | ORM for database interaction |
| **Maven**        | Build & dependency management |

---

## 📁 Project Structure

├── src/
│ ├── main/java/com/yourorg/cartapi
│ │ ├── controller/ # REST endpoints
│ │ ├── service/ # Business logic
│ │ ├── model/ # Entities / DTOs
│ │ ├── repository/ # Database interaction
│ │ └── ShoppingCartApiApplication.java
├── .gitignore
├── pom.xml
└── README.md
