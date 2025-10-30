# StayBooking

A full-stack booking platform built with **Spring Boot**, **React (Ant Design)**, and **PostgreSQL/PostGIS**.  
It enables users to upload, search, and book stays with location-based filtering, and provides hosts with listing management and reservation tracking.

---

## 🚀 Tech Stack

**Backend**  
- Java, Spring Boot, Spring Data JPA, JWT Authentication  
- PostgreSQL + PostGIS for geospatial search  
- Docker for containerized local development  

**Frontend**  
- React, Ant Design  
- RESTful API integration  
- Proxy configuration for local backend connection  

---

## 💡 Features

- **Stay Management** — Hosts can upload, update, or delete stays with images and descriptions.  
- **Reservation System** — Users can book and cancel stays, with automatic validation for availability.  
- **Geospatial Search** — PostGIS-based location query supporting search by distance and map coordinates.  
- **Authentication & Authorization** — Secure login and registration with JWT-based token system.  
- **Containerized Setup** — Easy deployment and testing using Docker Compose.  

---

## 🧱 Project Structure

```
StayBooking/
├── backend/          # Spring Boot backend (API, database, auth, PostGIS)
│   ├── src/main/java/com/staybooking/
│   └── src/main/resources/
├── frontend/         # React single-page application
│   ├── src/
│   ├── public/
│   └── package.json
└── docker-compose.yml   # PostGIS local database setup
```
## 🧑‍💻 Author

**Yuelu Zhang**  
Master’s Candidate in Information Systems, NEU
- GitHub: [YueluZhang](https://github.com/YueluZhang)

---

## 📜 License

This project is licensed under the [MIT License](./LICENSE).
