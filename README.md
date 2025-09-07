# 📊 StockManager

**StockManager** is a robust Java-based microservices application designed for efficient stock market management. It enables administrators to manage stock inventories and customer data, while allowing users to buy, sell, and track their portfolios in real time. The system is built with scalability and modularity in mind, using Spring Boot for RESTful APIs and Oracle Database for secure, persistent data storage.

---

## 🚀 Technologies Used

- **Java 8+**
- **Spring Boot** (Spring Starter Project)
- **JDBC**
- **REST APIs**
- **Oracle Database**
- **Oracle JET (OJet)** – Frontend framework

---

## 🧩 Microservices Architecture

| Microservice         | Description                                      |
|----------------------|--------------------------------------------------|
| `admin-service`      | Admin stock management and price changes         |
| `user-service`       | Buy/sell stocks and view user portfolio          |
| `stock-service`      | Stock registry and listing                       |
| `transaction-service`| Records of buy/sell actions                      |

Each service is independently deployable and communicates via REST APIs.

---

## 🛠️ Features

### 👨‍💼 Admin Features
- Add, remove, and modify stocks
- Change stock prices
- Delete customer accounts
- Secure admin-only endpoints

### 👤 User Features
- Login/Signup with role-based access
- Buy and sell stocks
- View personal portfolio
- Track transaction history
- Edit profile details

### 📈 Stock Features
- Real-time/randomized price fluctuations
- Centralized stock registry

---

## 🗃️ Data Model

- **Stocks**: Symbol, name, price, quantity
- **Customers**: ID, name, email, profile details
- **Transactions**: Buy/sell records with timestamps

---

## 🖥️ Frontend Overview

Built using **Oracle JET (OJet)**:
- Homepage with login/signup options
- Role-based access: Admin vs Customer
- Intuitive dashboards for portfolio and stock management

---

## 📂 Getting Started

1. Clone the repository
2. Set up Oracle Database and configure JDBC connection
3. Build and run each microservice using Spring Boot
4. Launch the OJet frontend and access via browser

---

## 📌 Future Enhancements

- Add authentication via OAuth2
- Integrate real-time stock APIs
- Implement notification system for price alerts

---

## 📬 Contact

For questions or contributions, feel free to reach out or open an issue.

---
