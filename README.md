<h1 align="center">Hi 👋, I'm Shubham Dhapse</h1>

<h3 align="center">
🚀 Senior Java Backend Engineer | Microservices | System Design | Fintech
</h3>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?lines=Backend+Engineer+with+5%2B+Years+Experience;Java+%7C+Spring+Boot+%7C+Microservices;System+Design+%7C+Distributed+Systems;Building+Scalable+Fintech+%26+Backend+Systems&center=true&width=700&height=45">
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=shubhamdhapse10-alt&label=Profile%20views&color=blue&style=flat" />
</p>

---

## 🧠 Engineering Mindset

* I design systems with **scalability, resilience, and maintainability** in mind
* Strong focus on **performance, concurrency, and low-latency APIs**
* Experienced in solving **real-world production issues**
* Follow **clean architecture, SOLID principles, and clean code**
* Interested in **distributed systems, system design, and event-driven architecture**
* Believe in building systems that are **reliable, observable, and production-ready**

---

## 👨‍💻 Professional Summary

* 💼 **5+ years** of Java Backend Development experience
* 🏦 Experience in **Banking & Fintech Systems**
* 🚀 **Senior Associate – Product Engineering**
* 🔥 Strong expertise in:

  * Java 17 / Java 21
  * Spring Boot & Spring MVC
  * Microservices
  * REST APIs
  * Spring Data JPA
  * PostgreSQL
  * MongoDB
  * Redis
  * Kafka
  * Multithreading & Concurrency
  * Docker
  * Git & Maven
* ⚡ Experience building **high-performance and transaction-intensive backend systems**
* 🔄 Experience with **API integrations, workflow orchestration, caching, and database optimization**

---

## ⚙️ System Design Expertise

* 🔹 Microservices Architecture
* 🔹 API Gateway & Service Discovery
* 🔹 RESTful API Design
* 🔹 Circuit Breaker & Fault Tolerance
* 🔹 Distributed Transactions
* 🔹 Saga Pattern
* 🔹 Event-Driven Architecture
* 🔹 Kafka-based Asynchronous Processing
* 🔹 Redis Caching
* 🔹 Database Indexing & Query Optimization
* 🔹 Horizontal Scalability
* 🔹 Concurrency & Multithreading
* 🔹 WebSocket-based Real-Time Communication
* 🔹 Polyglot Persistence
* 🔹 Optimistic Locking
* 🔹 Eventual Consistency

---

# 🛠️ Tech Stack

### 💻 Languages

![Java](https://img.shields.io/badge/Java-orange?style=for-the-badge\&logo=openjdk)
![SQL](https://img.shields.io/badge/SQL-blue?style=for-the-badge)
![JavaScript](https://img.shields.io/badge/JavaScript-yellow?style=for-the-badge\&logo=javascript)

### 🚀 Backend

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-green?style=for-the-badge\&logo=springboot)
![Spring MVC](https://img.shields.io/badge/Spring%20MVC-green?style=for-the-badge\&logo=spring)
![Spring Data JPA](https://img.shields.io/badge/Spring%20Data%20JPA-green?style=for-the-badge\&logo=spring)
![Microservices](https://img.shields.io/badge/Microservices-blue?style=for-the-badge)
![REST API](https://img.shields.io/badge/REST%20APIs-orange?style=for-the-badge)

### 🗄️ Databases

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-blue?style=for-the-badge\&logo=postgresql)
![MongoDB](https://img.shields.io/badge/MongoDB-green?style=for-the-badge\&logo=mongodb)
![Redis](https://img.shields.io/badge/Redis-red?style=for-the-badge\&logo=redis)

### 📨 Messaging & Streaming

![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-black?style=for-the-badge\&logo=apachekafka)
![WebSocket](https://img.shields.io/badge/WebSocket-blue?style=for-the-badge)

### ☁️ DevOps & Tools

![Docker](https://img.shields.io/badge/Docker-blue?style=for-the-badge\&logo=docker)
![Jenkins](https://img.shields.io/badge/Jenkins-red?style=for-the-badge\&logo=jenkins)
![Git](https://img.shields.io/badge/Git-orange?style=for-the-badge\&logo=git)
![Maven](https://img.shields.io/badge/Maven-red?style=for-the-badge\&logo=apachemaven)
![AWS](https://img.shields.io/badge/AWS-orange?style=for-the-badge\&logo=amazonaws)

---

# 🔥 Featured Projects

## 📊 Market Data Service

> Real-time market data backend built using **Java 21, Spring Boot, REST APIs and WebSocket**.

### 🚀 Key Features

* 📈 Fetches **Top 20 Spot Trading Pairs by Volume**
* 🔌 Integrates with **OKX Public Market APIs**
* ⚡ Real-time order book updates using **WebSocket**
* 🧩 Backend acts as a **proxy layer**, so the UI does not directly communicate with OKX
* 🔄 Supports dynamic WebSocket subscriptions for instruments
* 📊 Maintains rolling market statistics
* 🧵 Handles concurrent real-time market data updates
* 🛡️ Separation of concerns with clean backend architecture
* 📡 Supports real-time order book streaming

### 🏗️ Architecture

```text
                    ┌──────────────────┐
                    │       UI         │
                    └────────┬─────────┘
                             │
                             ▼
                    ┌──────────────────┐
                    │  Spring Boot API │
                    └────────┬─────────┘
                             │
                ┌────────────┴────────────┐
                │                         │
                ▼                         ▼
       ┌────────────────┐       ┌─────────────────┐
       │  OKX REST API  │       │ OKX WebSocket   │
       │                │       │                 │
       │ Top 20 Markets │       │ Order Book      │
       └────────────────┘       └─────────────────┘
```

### 🛠️ Tech Stack

`Java 21` `Spring Boot 3.5.6` `REST API` `WebSocket` `Maven` `OKX API`

🔗 **Repository:**
https://github.com/shubhamdhapse10-alt/market-data-service

---

# 🛒 E-commerce Order Management — Polyglot Persistence

> Spring Boot backend demonstrating **Polyglot Persistence using PostgreSQL + MongoDB**, with transactional order processing and concurrency control.

🔗 **Repository:**
https://github.com/shubhamdhapse10-alt/Repository-name-ecommerce-poly-persistence

### 🎯 Architecture Decision

The application uses different databases based on the nature of the data.

| Domain          | Database   | Purpose                       |
| --------------- | ---------- | ----------------------------- |
| Users           | PostgreSQL | Relational consistency        |
| Orders          | PostgreSQL | ACID transactions             |
| Order Items     | PostgreSQL | Referential integrity         |
| Payments        | PostgreSQL | Transactional consistency     |
| Inventory       | PostgreSQL | Concurrent stock management   |
| Product Catalog | MongoDB    | Flexible document structure   |
| Reviews         | MongoDB    | Document-oriented data        |
| Replies         | MongoDB    | Nested documents              |
| Activity Logs   | MongoDB    | Append-oriented activity data |

### 🔥 Key Engineering Features

* 🗄️ **Polyglot Persistence** using PostgreSQL + MongoDB
* 🔐 **ACID transactions** for order processing
* 📦 Atomic flow for:

  * Inventory deduction
  * Order creation
  * Order items
  * Payment creation
* 🔄 **Optimistic locking using `@Version`**
* 🛡️ Prevents inventory overselling during concurrent orders
* ⚡ Asynchronous activity logging using `@Async`
* 🔀 Eventual consistency between PostgreSQL and MongoDB
* 🛠️ **Flyway** for database schema migrations
* 🧪 **Testcontainers** for integration testing
* 🐳 Docker Compose based infrastructure
* 📚 Swagger/OpenAPI documentation
* 🧱 Layered architecture
* 🔀 Separate JPA and MongoDB persistence layers

### 🏗️ Architecture

```text
                         ┌─────────────────────┐
                         │      REST APIs      │
                         │     Spring Boot     │
                         └──────────┬──────────┘
                                    │
                         ┌──────────▼──────────┐
                         │      Services       │
                         │                     │
                         │ Order Service       │
                         │ Product Service     │
                         │ Review Service      │
                         └──────────┬──────────┘
                                    │
                    ┌───────────────┴────────────────┐
                    │                                │
                    ▼                                ▼
           ┌─────────────────┐              ┌─────────────────┐
           │   PostgreSQL    │              │     MongoDB     │
           │                 │              │                 │
           │ Users           │              │ Products        │
           │ Orders          │              │ Reviews         │
           │ Order Items     │              │ Replies         │
           │ Payments        │              │ Activity Logs   │
           │ Inventory       │              │                 │
           └─────────────────┘              └─────────────────┘
```

### 🔒 Transaction & Concurrency Flow

```text
                     Place Order
                          │
                          ▼
                  Validate Inventory
                          │
                          ▼
                    Deduct Stock
                          │
                          ▼
                    Create Order
                          │
                          ▼
                  Create Order Items
                          │
                          ▼
                   Create Payment
                          │
                          ▼
                       COMMIT
```

If any transactional operation fails, the PostgreSQL transaction is rolled back.

Inventory uses **optimistic locking with `@Version`** to handle concurrent order requests.

### 🧪 Integration Testing

Uses **Testcontainers** to run integration tests against real PostgreSQL and MongoDB containers.

Testing covers:

* ✅ Successful order processing
* ✅ Inventory deduction
* ✅ Order and payment creation
* ✅ Transaction rollback
* ✅ Insufficient inventory scenarios
* ✅ Concurrent inventory updates

### 🛠️ Tech Stack

`Java 17` `Spring Boot 3.3` `Spring Data JPA` `PostgreSQL` `Spring Data MongoDB` `MongoDB` `Flyway` `Testcontainers` `Docker Compose` `Swagger/OpenAPI` `Maven`

---

# 🏦 Professional Projects

## HDFC — GoNoGo 8.0 Loan Platform

* Developed backend services using **Java & Spring Boot**
* Integrated **10+ REST APIs**
* Implemented **Redis caching** for frequently accessed data
* Optimized database queries to improve API performance
* Worked on systems supporting approximately **5K concurrent users**
* Worked on loan processing and application workflows
* Participated in code reviews and mentoring
* Worked with multiple internal and external service integrations

### Technologies

`Java` `Spring Boot` `Microservices` `REST APIs` `PostgreSQL` `Redis` `Docker`

---

## 🏦 Bandhan — Loan Onboarding Platform

* Developed Spring Boot microservices for loan onboarding
* Implemented REST-based service integrations
* Integrated **UIDAI Aadhaar/KYC services**
* Worked with **MuleSoft REST integrations**
* Implemented workflow-based loan processing
* Troubleshot production and integration issues

### Technologies

`Java` `Spring Boot` `Microservices` `REST APIs` `MuleSoft` `KYC` `PostgreSQL`

---

## 💳 OD Journey

* Developed backend services for the Overdraft journey
* Implemented JWT-based authentication
* Worked on service integrations and workflow processing
* Performed production issue analysis and RCA
* Contributed to reducing downtime through optimization and issue resolution

### Technologies

`Java` `Spring Boot` `JWT` `Microservices` `REST APIs`

---

# 📈 Impact & Achievements

* ✅ **5+ years** of Java Backend Engineering experience
* ✅ Banking & Fintech domain experience
* ✅ Integrated **10+ REST APIs**
* ✅ Experience with systems supporting **high-concurrency workloads**
* ✅ Improved API performance using **Redis caching and query optimization**
* ✅ Experience with **Kafka-based event-driven architecture**
* ✅ Experience building **real-time WebSocket applications**
* ✅ Hands-on experience with **PostgreSQL + MongoDB Polyglot Persistence**
* ✅ Implemented **optimistic locking and transaction management**
* ✅ Experience with **Testcontainers-based integration testing**
* ✅ Experience troubleshooting production issues and performing RCA
* ✅ Docker-based development and deployment experience

---

# 📊 GitHub Analytics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=shubhamdhapse10-alt&show_icons=true&theme=tokyonight" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=shubhamdhapse10-alt&theme=tokyonight" />
</p>

---

# 🎯 Currently Exploring

* 🏗️ Advanced System Design
* ⚡ High-throughput backend systems
* 🔄 Event-driven Microservices
* 📨 Apache Kafka
* 🧠 Distributed Systems
* 🚀 Java 21
* 🗄️ Polyglot Persistence
* 📡 Real-time WebSocket Systems
* ☁️ Cloud-native Applications
* 🔐 Scalable & Secure REST APIs
* 🚀 Performance Optimization

---

# 🌐 Connect With Me

<p align="left">

<a href="https://www.linkedin.com/in/shubham-dhapse">
<img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin">
</a>

<a href="mailto:shubhamdhapse10@gmail.com">
<img src="https://img.shields.io/badge/Email-red?style=for-the-badge&logo=gmail">
</a>

</p>

---

## 💡 Engineering Philosophy

<p align="center">
<b>"I build backend systems that are scalable, resilient, and designed to handle real-world production challenges."</b> 🚀
</p>
