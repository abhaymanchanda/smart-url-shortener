# Smart URL Shortener

A full-stack URL shortener built with React and Spring Boot.

## 🚀 Features

- Create short URLs from long URLs
- User registration and login
- JWT-based authentication
- Manage shortened URLs
- Track URL click activity
- View URL analytics
- React-based frontend
- Spring Boot REST API backend
- Responsive web interface

## 🛠️ Tech Stack

### Frontend
- React
- Vite
- Tailwind CSS
- JavaScript

### Backend
- Java
- Spring Boot
- Spring Security
- Spring Data JPA
- JWT
- REST APIs

### Tools
- Git & GitHub
- Maven
- Docker

## 🏗️ Architecture

```text
┌─────────────────────┐
│    React Frontend   │
│                     │
│      Vite + React   │
└──────────┬──────────┘
           │
           │ REST API
           ▼
┌─────────────────────┐
│   Spring Boot API   │
│                     │
│  Authentication     │
│  URL Management     │
│  Analytics          │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│      Database       │
│                     │
│  Users              │
│  URL Mappings       │
│  Click Events       │
└─────────────────────┘