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


3️⃣ Apply Migrations (If Required)
dotnet ef database update

4️⃣ Run the API
dotnet run
The API will start at:  http://localhost:5211

5️⃣ Swagger UI
Open Swagger to test APIs:
http://localhost:5211/swagger

🧠 Architecture Notes
Follows RESTful API principles
Uses Entity Framework Core for data access
Clean separation of concerns (Controllers, Models, DbContext)
Designed to be production-ready and interview-safe

🧪 Testing
Manual testing via Swagger UI.
Automated tests are not configured yet.

👤 Author
Abhishek Patidar
Angular & .NET Full-Stack Developer

https://github.com/Abhishekpatidar0/employee-management-frontend 




