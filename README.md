# 🎫 Mini Support Desk

A full-stack web application for internal support ticket management.

## ✨ Features

### 🔐 Authentication & Authorization
- User/Admin roles with JWT authentication
- Secure login and registration

### 🎫 Ticket Management
- Users can create, view, and update tickets
- Admins can manage all tickets
- Ticket lifecycle (OPEN, IN_PROGRESS, RESOLVED, CLOSED)

### 💬 Conversation
- Comment threads on tickets
- Real-time communication

## 🏗️ Tech Stack

### Backend
- Java 17 + Spring Boot
- Spring Security + JWT
- Spring Data JPA
- MySQL Database

### Frontend
- React 18
- React Router
- Axios for API calls
- CSS-in-JS for styling

## 🚀 Quick Start

### Prerequisites
- Java 17
- Node.js 16+
- MySQL 8+

### Backend Setup
```bash
cd backend

# Configure database in application.properties

# Build and run
mvn clean install
mvn spring-boot:run
