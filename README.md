# 🎓 Student Management System

A Student Management System backend built with **NestJS**, **PostgreSQL**, **TypeORM**, and **JWT Authentication**. The project provides secure REST APIs for managing students, users, courses, and departments with role-based access control.

---

## 🚀 Features

- JWT Authentication
- Role-Based Access Control (RBAC)
- Student Management (CRUD)
- User Management (CRUD)
- Course Management (CRUD)
- Department Management (CRUD)
- Input Validation
- PostgreSQL Database
- TypeORM ORM
- RESTful API
- Modular Architecture
- Swagger API Documentation

---

## 🛠️ Tech Stack

- NestJS
- TypeScript
- PostgreSQL
- TypeORM
- JWT Authentication
- Passport.js
- Class Validator
- Swagger
- Node.js

---

## 📂 Project Structure

```text
src/
│
├── auth/
│   ├── dto/
│   ├── guards/
│   ├── strategies/
│   ├── auth.controller.ts
│   ├── auth.service.ts
│   └── auth.module.ts
│
├── users/
│   ├── dto/
│   ├── entities/
│   ├── users.controller.ts
│   ├── users.service.ts
│   └── users.module.ts
│
├── students/
│   ├── dto/
│   ├── entities/
│   ├── students.controller.ts
│   ├── students.service.ts
│   └── students.module.ts
│
├── courses/
│
├── departments/
│
├── common/
│
├── app.module.ts
└── main.ts
```

---

## 📌 CRUD Operations

### Authentication

- Register User
- Login User
- JWT Authentication
- Role Authorization

### Students

- Create Student
- Get All Students
- Get Student by ID
- Update Student
- Delete Student

### Courses

- Create Course
- Read Courses
- Update Course
- Delete Course

### Departments

- Create Department
- Read Departments
- Update Department
- Delete Department

---

## 📡 API Endpoints

| Method | Endpoint | Description |
|---------|----------|-------------|
| POST | `/auth/register` | Register User |
| POST | `/auth/login` | Login |
| GET | `/students` | Get All Students |
| GET | `/students/:id` | Get Student |
| POST | `/students` | Create Student |
| PATCH | `/students/:id` | Update Student |
| DELETE | `/students/:id` | Delete Student |

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/USERNAME/Dashboard.git
```

Move into the project

```bash
cd Dashboard
```

Install dependencies

```bash
npm install
```

Configure environment variables

```env
DATABASE_HOST=localhost
DATABASE_PORT=5432
DATABASE_USER=postgres
DATABASE_PASSWORD=password
DATABASE_NAME=student_management

JWT_SECRET=your_secret_key
```

Run the project

```bash
npm run start:dev
```

---

## 📚 Available Scripts

```bash
npm run start
npm run start:dev
npm run build
npm run test
npm run lint
```

---

## 👥 Team Collaboration

| Branch | Responsibility |
|---------|----------------|
| `main` | Production-ready code |
| `develop` | Integration branch |
| `feature/auth` | Authentication & Authorization |
| `feature/student-crud` | Student Management |
| `feature/course-department` | Course & Department Management |
| `feature/dashboard` | Dashboard, Testing & Documentation |

---

## 🔄 Git Workflow

1. Create a feature branch from `develop`.
2. Implement the assigned feature.
3. Commit your changes with meaningful commit messages.
4. Push the branch to GitHub.
5. Open a Pull Request to `develop`.
6. After review, merge into `develop`.
7. Merge `develop` into `main` for releases.

---

## 📖 API Documentation

Swagger documentation will be available at:

```
http://localhost:3000/api
```

---

## 📄 License

This project is licensed under the Apache-2.0 License.

---

## 👨‍💻 Contributors

- S. M. A. Rob
- 

---

⭐ If you found this project useful, consider giving it a star on GitHub.
