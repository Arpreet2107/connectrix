# 💬 Connectrix – Full Stack Real-Time Chat Application

Connectrix is a scalable real-time chat application inspired by WhatsApp, built with a robust tech stack including **Spring Boot 3**, **Angular 19**, and **PostgreSQL**. It supports secure messaging, file sharing, role-based authentication, and a responsive UI for seamless cross-device communication.

---

## 🚀 Features

- ✅ Real-time messaging using **WebSockets (STOMP + SockJS)**
- 🔐 Secure login with **OAuth2 Authentication (Keycloak)**
- 🗂 Role-based access control for **Admin**, **User**, etc.
- 📎 Share **images**, **videos**, and **documents**
- 🖥 Fully responsive UI using **Bootstrap**
- 🧱 Scalable **Hexagonal Architecture** (Ports and Adapters)
- 📦 RESTful API with clean modular design

---

## 🛠️ Tech Stack

| Category           | Technologies Used                                              |
|--------------------|----------------------------------------------------------------|
| **Frontend**       | Angular 19, TypeScript, Bootstrap 5                            |
| **Backend**        | Spring Boot 3, REST API, JPA, Hibernate                        |
| **Authentication** | Keycloak (OAuth2), Spring Security                            |
| **Database**       | PostgreSQL                                                    |
| **Real-Time**      | WebSocket, STOMP, SockJS                                      |
| **Architecture**   | Hexagonal Architecture (Clean Code)                           |
| **Dev Tools**      | Postman, IntelliJ, Git, GitHub                                |

---

---

## 📂 Project Structure

```connectrix/
│
├── connectrix-api/ # Spring Boot backend
│ ├── domain/ # Core business logic
│ ├── application/ # Service layer
│ ├── infrastructure/ # DB & messaging adapters
│ └── config/ # Keycloak, WebSocket, etc.
│
├── connectrix-ui/ # Angular frontend
│ ├── components/ # UI components
│ ├── services/ # API and WebSocket logic
│ └── environments/ # Dev/Prod environment configs
```
---

## 🧪 Running Locally

### Prerequisites
- Node.js (v18+)
- Angular CLI
- Java 17+
- PostgreSQL
- Keycloak (for OAuth2 setup)
---

### Backend

```bash
cd connectrix-api
./mvnw spring-boot:run
```
---

###Ensure PostgreSQL is running and credentials are set in application.properties.
---

###Frontend
```cd connectrix-ui
npm install
ng serve
```
---

App will be served at http://localhost:4200.
---


| Method | Endpoint                 | Description            |
| ------ | ------------------------ | ---------------------- |
| GET    | `/api/users`             | Get all users          |
| POST   | `/api/messages`          | Send a new message     |
| GET    | `/api/messages/{chatId}` | Fetch messages by chat |
---

👨‍💻 Author
Arpreet Mahala
📧 arpreet4114@gmail.com
---


🌟 Acknowledgements
Spring Boot Docs
---

Angular Docs
---

Keycloak Docs
---

Built with 💙 for developers who value structure, speed, and scalability.
