# 🎬 CineVerse - Movie Recommendation Platform

CineVerse is a full-stack movie recommendation platform built using **Java Spring Boot** and **MongoDB**.  
The platform allows users to explore movies, get personalized recommendations, manage watchlists, and interact with a secure authentication system.

## 🚀 Features

### 🔐 User Authentication
- User registration and login system
- Secure authentication using Spring Security
- User profile management

### 🎥 Movie Management
- Browse available movies
- View movie details
- Search and explore movies

### ⭐ Recommendation System
- Personalized movie recommendations
- Recommendation based on user preferences and ratings

### 📌 Watchlist
- Add movies to watchlist
- Remove movies from watchlist
- Manage saved movies

### 👤 User Profile
- View and update profile information
- Track user activity

---

## 🛠️ Tech Stack

### Backend
- Java
- Spring Boot 3
- Spring MVC
- Spring Security
- Maven

### Database
- MongoDB

### Frontend
- HTML
- CSS
- JavaScript
- Thymeleaf

### Tools
- IntelliJ IDEA / VS Code
- MongoDB Atlas / Local MongoDB
- Git & GitHub

---

## 📂 Project Structure

```
movie-platform
│
├── src/main/java/com/movieplatform
│   │
│   ├── config          # Security and application configuration
│   ├── controller      # Web controllers
│   ├── model           # Database models
│   ├── repository      # MongoDB repositories
│   ├── service         # Business logic
│
├── src/main/resources
│   ├── templates       # HTML pages
│   ├── static          # CSS, JS files
│   └── application.properties
│
└── pom.xml
```

---

## ⚙️ Installation & Setup

### 1. Clone Repository

```bash
git clone https://github.com/your-username/cineverse.git
```

### 2. Open Project

Open the project in:

- IntelliJ IDEA  
or
- VS Code

---

### 3. Configure MongoDB

Update your `application.properties` file:

```properties
spring.data.mongodb.uri=YOUR_MONGODB_CONNECTION_STRING
spring.data.mongodb.database=movieplatform
```

Replace the connection string with your MongoDB URL.

---

### 4. Run Application

Using Maven:

```bash
mvn spring-boot:run
```

Or run the main Spring Boot application class.

---

## 🌐 Application URL

After starting the application:

```
http://localhost:8080
```

---

## 📸 Screenshots

(Add your project screenshots here)

---

## 🔮 Future Improvements

- AI-based recommendation engine
- Movie rating and review system
- Integration with movie APIs
- Mobile application version
- Advanced search filters

---

## 👨‍💻 Developer

**Suryansh Sharma**

B.Tech Computer Science Engineering  
Lamrin Tech Skills University

---

## 📄 License

This project is created for educational and learning purposes.
