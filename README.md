# 💼 Job Portal App

<p align="center">
  <img src="https://img.shields.io/badge/Frontend-React-blue?style=for-the-badge&logo=react" />
  <img src="https://img.shields.io/badge/Backend-SpringBoot-brightgreen?style=for-the-badge&logo=springboot" />
  <img src="https://img.shields.io/badge/Database-MongoDB-green?style=for-the-badge&logo=mongodb" />
  <img src="https://img.shields.io/badge/Status-%20Developed-orange?style=for-the-badge&logo=progress" />
</p>

> A full-stack Job Portal web application to browse, search, and post job listings with modern features like pagination and keyword filtering.

---

## 🚀 Overview

**Job Portal App** helps connect employers with job seekers through an intuitive platform. It demonstrates a real-world implementation of a CRUD-based full-stack app with a clean, scalable architecture.

### 🧩 Core Features

- 🔍 **Search Jobs** by keyword (e.g., Java, Python)
- 📄 **Paginated Job Feed** (6 jobs per page)
- 📝 **Post a New Job** via a form
- 🌐 **RESTful API** with Swagger Documentation
- ⚙️ **MongoDB Integration** for data storage
- ❌ **404 Page** for invalid URLs

---

## 🛠️ Tech Stack

| Layer         | Technologies Used                        |
|---------------|-------------------------------------------|
| 🖼 Frontend    | React.js, React Router, Axios, Tailwind CSS |
| ⚙ Backend     | Java 17, Spring Boot, Spring Web, Swagger |
| 🛢 Database    | MongoDB (local or Atlas)                 |
| 🧪 Tools       | Postman, Git, IntelliJ, VSCode, Maven    |

---

## 📸 Screenshots

| Page | Preview |
|------|---------|
| 🏠 Home Page | ![Home](https://github.com/Mahmud-Alam/spring-boot-job-portal-app/blob/main/screenshots/01.png) |
| 📝 Job Form | ![Create](https://github.com/Mahmud-Alam/spring-boot-job-portal-app/blob/main/screenshots/02.png) |
| 💼 Job Listings | ![List](https://github.com/Mahmud-Alam/spring-boot-job-portal-app/blob/main/screenshots/03.png) |
| 🔍 Search | ![Search](https://github.com/Mahmud-Alam/spring-boot-job-portal-app/blob/main/screenshots/04.png) |
| 🧪 Swagger UI | ![Swagger](https://github.com/Mahmud-Alam/spring-boot-job-portal-app/blob/main/screenshots/05.png) |
| ❌ 404 Page | ![404](https://github.com/Mahmud-Alam/spring-boot-job-portal-app/blob/main/screenshots/06.png) |

---

<details>
<summary><strong>📥 Installation Guide</strong> (click to expand)</summary>

### 🔧 Prerequisites

- Java 17+
- Node.js & npm
- MongoDB (local or Atlas)

---

### 🔙 Backend Setup

```bash
# Clone the repo
git clone https://github.com/Krushil45/job-portal-app.git
cd job-portal-app/backend

---

### ✏️ Edit your MongoDB config inside application.properties:

<properties>
spring.application.name=job-portal
spring.data.mongodb.uri=mongodb://localhost:27017/job_portal_db
spring.data.mongodb.database=job_portal_db

# Run the backend
./mvnw spring-boot:run

### 📍 Backend runs on: http://localhost:8080

```
🌐 Frontend Setup

```bash
cd ../frontend
npm install
npm run dev

### 📍 Frontend runs on: http://localhost:5173
```
</details>

# 💼 Job Portal API – Powered by Spring Boot

## 📘 API Endpoints

| Method | Endpoint              | Description                    |
|--------|------------------------|--------------------------------|
| GET    | `/job-posts`          | Fetch all job posts            |
| GET    | `/job-posts/{text}`   | Search jobs by keyword         |
| POST   | `/create-job-post`    | Create a new job post          |

---

## 🔧 Sample Payload

```json
{
  "profile": "Java Spring Boot Developer",
  "desc": "We are hiring Java Spring Boot developers!",
  "exp": 2,
  "techs": ["Java", "Spring Boot"]
}
```

---

### 🧪 Swagger Documentation
You can access a full API interface via Swagger UI:

http://localhost:8080/swagger-ui.html
Includes:

📄 Request/Response Schemas

🧪 API Testing Interface

✅ Model Validations

---

### 🔮 Future Improvements
🔐 JWT-based Authentication

👥 Role-based Access (Employer / Seeker)

🧾 Job Detail Page with Apply Feature

✅ Enhanced Validation & Error Messages

☁️ Deployment on Render / Railway / Vercel

---

### 🤝 Contributing
We welcome contributions of all kinds!
How to contribute:
  Fork the repository

Create a feature branch
  git checkout -b feature/NewFeature

Commit your changes
  git commit -m 'Add New Feature'

Push to GitHub
  git push origin feature/NewFeature

Open a Pull Request


---

### 👨‍💻 Author
#Kapupara Krushil

📧 Email: krusilkapupara456@gmail.com

🔗 GitHub: @Krushil45

🔗 LinkedIn: krushil-kapupara


---

### 🙌 Acknowledgments
Inspired by real-world job platforms

Thanks to the open-source Spring Boot & React communities for their incredible tools and documentation

“Connecting Minds, Building Futures.”
