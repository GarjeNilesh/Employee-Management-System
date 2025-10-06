# Employee-Management-System

A full-stack Employee Management System built with:

🖥️ Frontend: React (Vite, React Router, Axios)

⚙️ Backend: Spring Boot (RESTful APIs, JPA, MySQL/PostgreSQL)

🗃️ Database: MySQL

🗂️ Project Structure employee-management-system/ ├── frontend/ # React App └── backend/ # Spring Boot App

🚀 Features

✅ View all employees

➕ Add new employees

📝 Update employee information

❌ Delete employees

📦 RESTful APIs with Spring Boot + JPA

🌐 Modern responsive UI using React

🛠️ Tech Stack Layer Technology Frontend React, Axios, Vite, React Router Backend Spring Boot, Spring Web, Spring Data JPA Database MySQL or PostgreSQL Build Tool (Backend) Maven or Gradle API Style REST 🧑‍💻 Getting Started ⚙️ Prerequisites

Node.js (v18+)

Java JDK (17 or 21 recommended)

Maven

MySQL / PostgreSQL

Git

📦 Backend Setup (Spring Boot)

Navigate to backend folder:

cd backend

Configure DB in application.properties or application.yml:

spring.datasource.url=jdbc:mysql://localhost:3306/employees_db spring.datasource.username=root spring.datasource.password=root

spring.jpa.hibernate.ddl-auto=update

Run the application:

./mvnw spring-boot:run

The backend will run on: http://localhost:8080

🌐 Frontend Setup (React)

Navigate to frontend folder:

cd frontend

Install dependencies:

npm install

Run the React app:

npm run dev

The frontend will run on: http://localhost:5173

📁 API Endpoints (Example) Method Endpoint Description GET /api/v1/employees Get all employees POST /api/v1/employees Add new employee PUT /api/v1/employees/{id} Update employee by ID DELETE /api/v1/employees/{id} Delete employee by ID 🧪 Testing

Backend: Use Postman to test API endpoints.

Frontend: Manual UI tests, optional integration/unit tests with Jest & React Testing Library.

📌 Future Improvements

Authentication & Authorization (Spring Security + JWT)

Search, Pagination, Sorting

Profile pictures (file upload)

🧑‍🏫 Author

Nilesh Garje garjenilesh5858@gmail.com
