# Code by PanhaPhin
# Full Stack Angular 17 + .NET 8 Library Management System
 Library Management System


 Steps:
1. Clone the Repository.
2. Create Database with any name eg. ABC
2. Open API solution in Visual Studio 2022
3. Go to appsettings.json and update the database string in "DB" section.
4. Also fill from email and email code. (optional)
5. Open Package manager console and run update-database command.
6. Now run API solution.
7. Go to UI folder and open in Visual Studio Code.
8. Run npm install, and then ng serve
9. Project will be running.




Open http://localhost:3000 in your browser to view the result.

You can start editing the page by modifying pages/index.js. The app auto-updates as you edit.

📡 API Routes
API routes live in the pages/api directory and are mapped to /api/*. For example:

http://localhost:3000/api/hello → pages/api/hello.js

Learn more about API routes here.




# 📚 Full Stack Library Management System

A robust, full-featured Library Management System built with **Angular 17** (Frontend) and **.NET 8 Web API** (Backend). This full-stack application is designed for scalability, performance, and maintainability using modern development best practices.

---

## 🚀 Tech Stack

### 🧭 Frontend

- Angular 17 (Standalone Components, Signals)
- Angular Router & Guards
- RxJS
- SCSS / Tailwind CSS
- JWT Authentication
- Angular Material / PrimeNG (UI)

### 🧰 Backend

- .NET 8 Web API
- Entity Framework Core 8
- SQL Server / SQLite
- Clean Architecture (API, Application, Domain, Infrastructure)
- JWT Auth & Role-Based Authorization
- FluentValidation
- Swagger for API Documentation

---

## 📁 Project Structure

### 🔹 Frontend (`/client`)



---

## 🧪 Features

- 📚 Book Management (CRUD)
- 👤 User & Role Management
- 🔐 Secure Authentication (JWT)
- 📖 Book Issue & Return
- 📅 Borrowing History & Logs
- 📊 Dashboard with Metrics
- 🔍 Search, Filter & Pagination
- 📄 API Documentation via Swagger
- 🌐 Responsive & Modern UI

---

## ⚙️ Getting Started

### Prerequisites

- Node.js (v18+)
- Angular CLI
- .NET 8 SDK
- SQL Server / SQLite

---

## 🔧 Backend Setup
```bash

cd server/LibraryManagement.API

# Apply EF Core migrations
dotnet ef database update

# Run the API
dotnet run

---

## 🧪 Testing
## Frontend

```bash
ng test

# Backend
```bash
dotnet test

---
## 🔧 Backend Setup
```bash

cd server/LibraryManagement.API

# Apply EF Core migrations
dotnet ef database update

# Run the API
dotnet run

---

## 🌐 Frontend Setup

### Prerequisites
```bash
cd client
npm install
ng serve

---




### 📥 Clone the Repository

```bash
git clone https://github.com/PanhaPhin/Library-Management-System.git
cd library-management-system



---

Let me know if you want to:
- Add badges (e.g., build passing, license)
- Include screenshots or diagrams
- Generate Swagger or Postman collections
- Write Docker support or GitHub Actions

Just say the word and I’ll hook you up like a pro 👨‍💻✨
