# 🏠 Staybooking

> A full-stack online stay rental platform with geospatial search, built with Spring Boot, React, and PostGIS.

![Java](https://img.shields.io/badge/Java-21-orange?logo=java)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.x-brightgreen?logo=springboot)
![React](https://img.shields.io/badge/React-18-blue?logo=react)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-PostGIS-336791?logo=postgresql)
![GCP](https://img.shields.io/badge/GCP-Cloud_Run-4285F4?logo=googlecloud)
![Docker](https://img.shields.io/badge/Docker-Containerized-2496ED?logo=docker)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## 📌 Overview

Staybooking enables hosts to list and manage properties, and guests to search and book stays with location-based filtering. The platform features a PostGIS-powered geospatial search engine, JWT authentication, and is deployed on Google Cloud Run.

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Backend | Java, Spring Boot, Spring Security, Spring Data JPA |
| Database | PostgreSQL + PostGIS (geospatial), Google Cloud Storage (media) |
| Frontend | React, Ant Design |
| Deployment | Docker, Google Cloud Run |

---

## ✨ Features

- 🏡 **Stay Management** — Hosts can upload, update, and delete listings with images
- 📅 **Reservation System** — Guests can book and cancel stays with availability validation
- 📍 **Geospatial Search** — PostGIS + GiST indexing for radius and proximity queries, reducing average query latency by ~40%
- 🔐 **Authentication** — Secure JWT token-based login and registration via Spring Security
- ☁️ **Cloud Storage** — Media files managed via Google Cloud Storage
- 🐳 **Containerized** — Docker Compose for easy local setup

---

## 📁 Project Structure

```
Staybooking/
├── Staybooking_Backend/   # Spring Boot backend
├── Staybooking_Frontend/  # React frontend
├── .gitignore
├── LICENSE
└── README.md

```
---

## 🚀 Getting Started

### Prerequisites
- Java 21+
- Node.js 18+
- Docker (for local PostgreSQL + PostGIS)
- Google Cloud credentials (for Cloud Storage)

### ▶️ Backend
```bash
cd Staybooking_Backend
# Configure application.properties with your DB and GCP credentials
docker-compose up -d   # Start PostgreSQL + PostGIS locally
./mvnw spring-boot:run
```

### ▶️ Frontend
```bash
cd Staybooking_Frontend
npm install
npm start
```

---

## 👩‍💻 Author

**Yuelu Zhang** — MS Information Systems, Northeastern University  
[![GitHub](https://img.shields.io/badge/GitHub-YueluZhang-181717?logo=github)](https://github.com/YueluZhang)

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).
