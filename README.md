#  Hi, I'm Md Shahjahan

### Java Backend Developer | Spring Boot | REST APIs | DSA

</div>

I'm an **Information Technology graduate** with a strong foundation in
**Java, Spring Boot, Data Structures & Algorithms, Object-Oriented Programming,
DBMS, and Operating Systems**.

I enjoy building secure, scalable backend applications, designing clean REST APIs,
and solving algorithmic problems while continuously improving my software
engineering skills.

- 🎓 B.Tech in Information Technology (2022 – 2026), Techno Main Salt Lake, Kolkata
- ☕ Focused on **Java Backend Development and Spring Boot**
- 🚀 Experience with **REST APIs, Spring Security, JWT, JPA/Hibernate, MySQL and PostgreSQL**
- 🔐 Built authentication flows with **JWT, refresh-token rotation, Keycloak and role-based access control**
- 🧱 Comfortable with **layered architecture (Controller → Service → Repository) and microservices**
- 🧩 Solved **400+ DSA problems** across LeetCode and GeeksforGeeks
- 🏆 Secured **961st rank among 20K+ participants** in a LeetCode Weekly Contest
- 🏅 Ranked among the **Top 5 students in college**
- 🌱 Currently improving **Spring Boot, Microservices, System Design and DSA**
- 📫 Reach me at **shahjahanknj@gmail.com**

---

# 🛠️ Technical Skills

## 💻 Programming Languages

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

- Java (primary)
- C++
- JavaScript

---

## ⚙️ Backend Technologies

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring MVC](https://img.shields.io/badge/Spring%20MVC-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)

- Spring Boot
- Spring MVC
- Spring Security
- Spring Data JPA
- Spring AI & Google Gemini API
- REST API Design
- Microservices
- JPA / Hibernate
- JWT Authentication
- OAuth2 Resource Server
- Keycloak
- Role-Based Access Control
- Layered & MVC Architecture

---

## 🗄️ Databases

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

- MySQL
- PostgreSQL
- MongoDB
- SQL
- Database Design
- JPA/Hibernate

---

## 🎨 Frontend

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

- React
- JavaScript
- HTML5
- CSS3

---

## 🧰 Tools & Development Environment

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ%20IDEA-000000?style=for-the-badge&logo=intellijidea&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

- Git & GitHub
- Maven
- Postman
- IntelliJ IDEA
- VS Code
- Docker & Docker Compose
- Keycloak
- Linux (basic command line)

---

# 🚀 Java Projects

## 🎟️ Event Ticket Platform

A full-stack event ticket management application built with **Spring Boot, React, Vite, PostgreSQL and Keycloak**. Organizers create and manage events, attendees purchase tickets, and event staff scan ticket QR codes for entry. Authentication and authorization are handled by Keycloak.

**Tech:** `Java 21` `Spring Boot 3.4.4` `Spring Security` `Keycloak` `PostgreSQL` `Spring Data JPA` `React` `Vite` `Docker Compose` `Maven`

### ✨ Features

- **Event Management** — organizers can create and manage events.
- **Ticket Booking** — attendees can purchase tickets for available events.
- **QR Code Tickets** — tickets are verified by scanning QR codes, with manual validation as a fallback and checks to prevent duplicate ticket use.
- **Authentication & Authorization** — secure, role-based access using Keycloak with the Spring Security OAuth2 Resource Server (JWT validation).
- **REST API** — Spring Boot backend exposing event, ticket-type, purchase and validation endpoints.
- **Modern Frontend** — React app powered by Vite, proxying API requests to the backend.

### 🧱 Architecture & Tech Stack

| Component | Technology |
| --- | --- |
| Backend | Java 21, Spring Boot 3.4.4 |
| Frontend | React, Vite |
| Database | PostgreSQL (managed via Adminer) |
| Authentication | Keycloak (realm: `event-ticket-platform`) |
| Build Tool | Maven |
| Package Manager | npm |
| Local Infrastructure | Docker Compose (PostgreSQL, Adminer, Keycloak) |

```
event-ticket-platform/
├── docs/       # Project documentation
├── backend/    # Spring Boot backend
├── frontend/   # React frontend
└── README.md
```

### 🔑 Highlights

- Designed **REST API workflows** for event management, ticket types, purchases and ticket validation.
- Integrated **Keycloak with Spring Security OAuth2 Resource Server** for JWT validation and role-based access.
- Modelled event, user, ticket and ticket-type relationships using **Spring Data JPA and PostgreSQL**.
- Designed **QR-code and manual ticket validation** workflows.
- Containerized supporting services (PostgreSQL, Adminer, Keycloak) with **Docker Compose** for one-command local setup.

### ▶️ Run Locally

```bash
# 1. Start PostgreSQL, Adminer and Keycloak
cd backend && docker compose up -d

# 2. Run the Spring Boot backend (port 8080)
./mvnw spring-boot:run

# 3. Run the React frontend (port 5173)
cd ../frontend && npm install && npm run dev
```

Keycloak runs at `http://localhost:9090`, Adminer at `http://localhost:8888`. Prerequisites: JDK 21, Node.js 20+, Docker and Git.

🔗 [View Event Ticket Platform](https://github.com/mniMdShahjahan/event-ticket-app)

---

## 🤖 AI Email Assistant — Chrome Extension

An AI-powered Chrome extension that helps users write, improve and reply to emails directly while composing, built with a **Spring Boot backend, React frontend and Google Gemini**. Part of my **Spring AI Masters** repository.

**Tech:** `Java` `Spring Boot` `Spring AI` `Gemini API` `React` `JavaScript` `Chrome Extension APIs` `Web Speech API` `Maven`

### ✨ Features

- Writes and improves email content using AI.
- Grammar, spelling and punctuation correction.
- Multiple tones: **Formal, Professional, Casual, Friendly and Polite**.
- **Voice input** with the Web Speech API to generate and correct email content while composing.
- **Auto-generate and auto-reply** — AI-generated responses are inserted directly into emails.
- Chrome Extension integration for seamless AI-assisted composing and replying.

### 🔑 Highlights

- Built a Spring Boot REST backend that integrates with the **Google Gemini API**.
- Connected a React frontend and Chrome extension to the backend.
- Kept API keys out of source control using environment variables / local config.

🔗 [View AI Email Assistant](https://github.com/mniMdShahjahan/ai-email-assistant/tree/main/spring-ai-masters-main)

---

## 🎮 LevelUp Tasks — Gamified Productivity App

A full-stack productivity platform that combines task management with
gamification to encourage consistency.

**Tech:** `Java` `Spring Boot` `Spring Security` `JWT` `React` `JPA` `Hibernate` `MySQL`

### Highlights

- Built RESTful APIs using **Spring Boot and MVC architecture**.
- Implemented task management workflows, productivity analytics and **Pomodoro sessions**.
- Implemented secure authentication using **Spring Security and JWT** with **refresh-token rotation**.
- Implemented **role-based access control**.
- Designed a modular **gamification engine** with **XP and streak systems**.
- Designed database entities using **JPA/Hibernate** with MySQL for persistent storage.
- Maintained clean separation between business logic and the web layer, with components designed for isolated unit testing.

🔗 [View LevelUp Tasks](https://github.com/mniMdShahjahan/Task_Tracker_Full_Stack-main) · 🌐 [Live Demo](https://task-tracker-full-stack-main.vercel.app)

---

## 💰 Expense Service — Microservices

A backend microservice for managing user expenses as part of a
microservices-based Expense Tracker application.

**Tech:** `Java` `Spring Boot` `REST APIs` `Microservices`

### Highlights

- Developed REST APIs to **add, view, update and delete** user expenses.
- Implemented **Controller → Service → Repository** layered architecture.
- Designed the service as an independent microservice focused on maintainability and scalability.
- Tested REST APIs using **Postman**.

<!-- 🔗 [View on GitHub](https://github.com/mniMdShahjahan/Expense-Service) — replace Expense-Service with the repo name, then uncomment -->

---

## 🎫 Ticket Booking System

A console-based train ticket booking application built with **Core Java and OOP**.

**Tech:** `Java` `OOP` `JSON` `File Handling`

### Highlights

- Implemented user registration, train listing, ticket booking and seat availability management.
- Used JSON-based file storage for persistent data.
- Applied core **OOP principles** with modular Java classes.

<!-- 🔗 [View on GitHub](https://github.com/mniMdShahjahan/Ticket-Booking-System) — replace Ticket-Booking-System with the repo name, then uncomment -->

---

# 🧠 Other Projects

- **🧠 VectorX Engine** — C++ vector database with HNSW, KD-Tree and brute-force search, 768-dimensional Ollama embeddings and a RAG pipeline.
- **✈️ Airline Ticket Management System** — C++ console-based reservation system with STL, OOP and file persistence. [View Project](https://github.com/mniMdShahjahan/Flight-Reservation-Management-System)
- **🏠 House Price Prediction** — Python, Pandas, Scikit-learn regression models.
- **🌫️ AQI Prediction & Forecasting** — Python, XGBoost, SQL; evaluated with MAE, RMSE and R². [View Project](https://github.com/mniMdShahjahan/AirQualityIndex)

---

# 🧠 Core Computer Science

- **Data Structures & Algorithms**
- **Object-Oriented Programming**
- **Operating Systems**
- **Database Management Systems**
- **Cryptography**
- **Problem Solving**
- **REST API Design**
- **Layered & MVC Architecture**
- **Microservices Architecture**
- **Authentication & Authorization**

---

# 🧩 Data Structures & Algorithms

I actively practice DSA to strengthen my problem-solving and algorithmic thinking.

### Topics

`Arrays` · `Strings` · `Linked Lists` · `Stack` · `Queue` · `Hashing`

`Recursion` · `Backtracking` · `Binary Trees` · `BST` · `Graphs`

`Heap` · `Greedy` · `Dynamic Programming` · `Sliding Window`

`Two Pointers` · `Binary Search` · `Prefix Sum` · `Monotonic Stack`

### 🏆 Achievements

- Solved **400+ DSA problems** across LeetCode and GeeksforGeeks.
- Secured **961st rank among 20K+ participants** in a LeetCode Weekly Contest.
- Ranked among the **Top 5 students in college**.

---

# 📚 Relevant Coursework

- Data Structures & Algorithms
- Operating Systems
- Database Management Systems
- Object-Oriented Programming
- Cryptography

---

# 🌱 Currently Learning

- Advanced Spring Boot, Spring Security & Spring AI
- Microservices & System Design
- REST API Best Practices
- SQL & Database Optimization
- Dynamic Programming & Graph Algorithms

---

# 📜 Certifications

- **Spring Boot 3 & Spring AI**
- **Java Core & OOP**

---

# 🤝 Connect With Me

<p align="left">

<a href="https://www.linkedin.com/in/md-shahjahan-a1a0481b9/">
<img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="https://github.com/mniMdShahjahan">
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<a href="https://leetcode.com/u/shahJahanKng/">
<img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black"/>
</a>

<a href="mailto:shahjahanknj@gmail.com">
<img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

</p>

---

⭐ **Thanks for visiting my profile!**

💡 *Always learning. Always building. Always solving.*
