# CMU Law Project Management Petition System

A full-stack web application designed to manage petitions, user permissions, and project workflow for the CMU Law department.  
This system allows staff , track petition status, and manage approval workflows efficiently.

---

## 🚀 Overview

The system provides a centralized platform for petition submission, approval tracking, and project management.  
It includes user role management, secure data handling, and a structured backend–frontend connection.

This project was developed by a team, and my main responsibilities included backend development, database design, permission handling, and supporting frontend development by connecting React components with backend services.

---

## My Responsibilities (What I Built)

### Backend Development (Node.js + Express)
- Implemented RESTful APIs for petition operations, user management, and data retrieval.
- Handled input validation, error handling, and secure API design.
- Connected and synchronized backend logic with the frontend (React).

### Database Design (Prisma + SQL)
- Designed database schema for petitions, users, roles, and project workflow.
- Implemented CRUD operations through Prisma ORM.
- Ensured data consistency and relationships (one-to-many, many-to-many).

### Permission & Role Management
- Developed role-based access control (RBAC):
  - Admin  
  - Staff  
  - Student  
- Implemented permission checks at backend middleware level.

### Docker Setup
- Configured project to run with Docker for consistent development environments.
- Wrote and managed Dockerfile & Docker Compose.
- Helped teammates run the system smoothly using containerization.

### 🧩 Git & Collaboration
- Managed Git branches, merging, pull requests, and conflict resolution.
- Helped team maintain a clean Git workflow.
- Assisted teammates with repo connection & setup.

### 🎨 Frontend Support (React)
- Assisted with integrating frontend pages with backend APIs.
- Helped debug issues between UI and backend services.

---

## 🛠 Tech Stack

### **Frontend**
- React.js  
- HTML / Tailwind 
- JavaScript  

### **Backend**
- Node.js  
- Express.js  

### **Database**
- Prisma ORM  
- SQL  

### **Tools & Other**
- Docker  
- Git / GitHub  
- Postman  
- VS Code  

---

## Features

- Petition submission and tracking  
- User & role management  
- Approval workflow  
- Data storage with relational database  
- Secure backend API  
- Dockerized development environment  

---

## 📦 Installation

```sh
./build_docker.sh

//ดู database ข้อมูลด้านใน
docker exec -it cmu-law-project-management-petition-system-db-1 psql -U postgres -d petition_db