# Employee Management System – ASP.NET Core Web API (Backend)

This repository contains the **backend API** for the **Employee Management System**.
It is built using **ASP.NET Core Web API** and provides RESTful endpoints consumed by the Angular frontend.

---

## 🚀 Tech Stack

- ASP.NET Core Web API (.NET 9)
- Entity Framework Core
- SQL Server
- RESTful APIs
- Swagger (OpenAPI)

---

## ✨ Features

- Create employee
- Get all employees
- Get employee by ID
- Update employee details
- Delete employee
- Auto-incremented employee ID
- Swagger UI for API testing
- CORS enabled for Angular frontend

---

## 🔗 Frontend Integration

This backend is consumed by an Angular frontend application.

🔗 **Frontend Repository:**  
👉 https://github.com/Abhishekpatidar0/employee-management-frontend

---

## 📌 API Endpoints

| Method | Endpoint                  | Description              |
|------|---------------------------|--------------------------|
| GET  | `/api/employees`          | Get all employees        |
| GET  | `/api/employees/{id}`     | Get employee by ID       |
| POST | `/api/employees`          | Add new employee         |
| PUT  | `/api/employees/{id}`     | Update employee          |
| DELETE | `/api/employees/{id}`   | Delete employee          |

---

## 📦 Project Setup

### 1️⃣ Prerequisites

- .NET SDK **9.0+**
- SQL Server (LocalDB / Express / Full)
- Visual Studio or VS Code

---

### 2️⃣ Configure Database

Update the connection string in `appsettings.json`:

```json
"ConnectionStrings": {
  "DefaultConnection": "Server=YOUR_SERVER;Database=EmployeeDb;Trusted_Connection=True;"
}
