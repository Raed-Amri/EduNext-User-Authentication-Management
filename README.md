# 🎓 EduNext – User Authentication & Management (Spring Boot Backend)

[![Java](https://img.shields.io/badge/Java-17+-orange?logo=java&logoColor=white)](https://www.java.com/)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.2-green?logo=spring&logoColor=white)](https://spring.io/projects/spring-boot)
[![Maven](https://img.shields.io/badge/Maven-3.9-blue?logo=apache-maven&logoColor=white)](https://maven.apache.org/)
[![MySQL](https://img.shields.io/badge/Database-MySQL-lightgrey?logo=mysql&logoColor=white)](https://www.mysql.com/)

---

## 📌 Overview
**EduNext Backend** is a **Spring Boot application** that handles **user authentication and management** for an intelligent study platform.  
It provides robust APIs for **registration, login, and role-based access control** for learners and teachers, integrating **Spring Security** for secure authentication.  

The backend is designed to serve as a foundation for the **EduNext frontend application**, with potential for expansion into a **full web or mobile platform**.

---

## 🎯 Project Goal
The main objectives of this project are to:  
- Implement **secure user authentication and authorization** with Spring Security.  
- Support **role-based access control** for learners and teachers.  
- Manage **user profiles, roles, and permissions** efficiently.  
- Provide a **robust backend API** for the EduNext platform.  
- Serve as a **foundation for integrating AI-assisted learning features** in the future.

---

## 🚀 Features
- **User Registration:** Collect user details including first name, last name, email, password, phone number, and profile picture.  
- **Login & Authentication:** Secure login using email and password.  
- **Role-Based Access Control:** Assign roles (`Teacher` or `Learner`) and restrict access accordingly.  
- **Profile Management:** Update user information and manage profile credentials.  
- **Pack & Subscription Management:** Control access to courses and exams based on purchased packs with expiration dates.  
- **AI Voice Authentication (Optional):** Integrate AI for voice-based login verification.  

---

## 🛠️ Tech Stack
- **Language:** Java 17+  
- **Framework:** Spring Boot (Security, Data JPA, Web)  
- **ORM:** Hibernate / Spring Data JPA  
- **Database:** MySQL / PostgreSQL (configurable)  
- **Dependencies:**  
  - Spring Security  
  - Spring Data JPA  
  - Lombok  
  - Maven  

---

## 📁 Project Structure
The backend is structured into the following packages:

| Package | Description |
|---------|-------------|
| `entity` | Contains **JPA entities** like User, Role, Pack, Subscription. |
| `repository` | Spring Data JPA repositories for database operations. |
| `service` | Business logic for user management, authentication, and subscriptions. |
| `controller` | REST controllers exposing API endpoints. |
| `security` | Configurations for **Spring Security**, JWT, and role-based access control. |
| `dto` | Data Transfer Objects for request and response payloads. |

---

## ⚙️ Getting Started

### Prerequisites
- **Java 17+ SDK**  
- **Maven** (for dependency management)  
- **IDE:** IntelliJ IDEA, Eclipse, or VS Code with Java support  
- **Database:** MySQL or PostgreSQL (configured as needed)
