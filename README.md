# 🧾 Employee Management System

A full-stack web application to manage employee records with a seamless frontend-backend integration.

## 🚀 Tech Stack

- **Frontend**: React.js (with components like AddEmployee, ListEmployee, Header, Footer)
- **Backend**: Spring Boot (REST APIs for employee operations)
- **Database**: MySQL (JPA for ORM)
- **Build Tools**: Maven, npm

## 🗂️ Project Structure

```
employee-management-system/
├── employee-management-frontend/   # React.js frontend
│   └── src/component/              # React components
├── employee-managment-backend/     # Spring Boot backend
│   └── src/main/java/...           # Controllers, Models, Services
```

## 📦 Features

- Add, update, delete, and list employees
- RESTful API integration
- Clean separation of concerns (MVC architecture)
- Responsive UI using React

## 🛠️ Setup Instructions

### Backend

1. Navigate to backend:
   ```
   cd employee-managment-backend
   ```
2. Configure `application.properties` for MySQL.
3. Run the Spring Boot application:
   ```
   ./mvnw spring-boot:run
   ```

### Frontend

1. Navigate to frontend:
   ```
   cd employee-management-frontend
   ```
2. Install dependencies and start React app:
   ```
   npm install
   npm start
   ```
---

> 🙌 Built for educational purposes. Hope this helps others in understanding full-stack web application development!

