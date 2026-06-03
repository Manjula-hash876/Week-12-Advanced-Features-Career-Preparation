# Advanced Social Media Platform

## Project Overview

The **Advanced Social Media Platform** is a full-stack web application developed as a capstone project for Week 12: Advanced Features & Career Preparation. The application demonstrates real-world software engineering concepts including real-time communication, media uploads, authentication, testing, deployment automation, performance optimization, and DevOps practices.

The platform allows users to communicate in real time, upload media files, receive notifications, and interact securely using a scalable architecture.

---

# Features

## Core Features

* User Registration & Login
* JWT Authentication & Authorization
* Real-Time Chat with Socket.io
* Real-Time Notifications
* Image & Video Uploads
* Cloudinary Integration
* Responsive Frontend UI
* Protected Routes
* User Profile Management

---

# Advanced Features

* Typing Indicators
* Lazy Loading & Code Splitting
* API Rate Limiting
* Input Validation & Sanitization
* Helmet Security Headers
* Dockerized Deployment
* CI/CD Pipeline using GitHub Actions
* Frontend & Backend Testing
* SEO Optimization
* Nginx Reverse Proxy Support

---

# Technology Stack

## Frontend

* React.js
* React Router
* Axios
* Socket.io Client
* Tailwind CSS / CSS
* React Testing Library

## Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* Socket.io
* JWT Authentication
* Multer
* Cloudinary

## DevOps & Deployment

* Docker
* Docker Compose
* GitHub Actions
* Nginx
* Vercel / Render

---

# Project Structure

```bash
project-root/
│
├── frontend/
├── backend/
├── tests/
├── docker/
├── .github/workflows/
├── portfolio-website/
├── resume/
├── README.md
└── architecture-diagram.png
```

---

# Installation Guide

## Clone Repository

```bash
git clone https://github.com/your-username/advanced-socialmedia-platform.git
```

---

# Frontend Setup

```bash
cd frontend

npm install

npm run dev
```

Frontend runs on:

```bash
http://localhost:5173
```

---

# Backend Setup

```bash
cd backend

npm install

npm run start
```

Backend runs on:

```bash
http://localhost:5000
```

---

# Environment Variables

## Frontend `.env`

```env
VITE_API_URL=http://localhost:5000
```

---

## Backend `.env`

```env
PORT=5000

MONGO_DB_URL=mongodb://localhost:27017/socialmedia

JWT_SECRET_KEY=advancedSecretKey

CLIENT_URL=http://localhost:5173

CLOUDINARY_NAME=your_cloud_name

CLOUDINARY_API_KEY=your_cloudinary_api_key

CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

---

# Docker Setup

## Build Containers

```bash
docker-compose build
```

---

## Start Application

```bash
docker-compose up -d
```

---

## Stop Containers

```bash
docker-compose down
```

---

# Real-Time Features

The application uses Socket.io for:

* Real-time messaging
* Instant notifications
* Typing indicators
* User room management

---

# File Upload System

Media uploads are implemented using:

* Multer middleware
* Cloudinary cloud storage
* Image and video support
* File validation

---

# Security Features

* JWT Authentication
* Password Hashing using bcrypt
* Helmet Security Headers
* MongoDB Injection Protection
* Express Rate Limiting
* Input Sanitization

---

# Testing

## Frontend Testing

* Component Rendering
* User Interaction Testing
* API Mocking

## Backend Testing

* API Testing with Supertest
* Authentication Validation
* Socket.io Event Testing

---

# Run Tests

## Frontend

```bash
cd frontend

npm test
```

---

## Backend

```bash
cd backend

npm test
```

---

# CI/CD Pipeline

GitHub Actions workflows automate:

* Frontend Build
* Backend Build
* Automated Testing
* Docker Deployment
* Security Scanning
* Production Deployment

Workflow files are located in:

```bash
.github/workflows/
```

---

# Performance Optimization

* Lazy Loading
* Code Splitting
* Optimized API Calls
* Caching Strategies
* SEO Meta Tags
* Lighthouse Audits

---

# Portfolio Website

The repository also contains a professional portfolio website showcasing:

* Skills
* Projects
* Resume
* Experience
* Contact Information

Location:

```bash
portfolio-website/
```

---

# Deployment

## Frontend Deployment

* Vercel
* Netlify

## Backend Deployment

* Render
* Railway

## Docker Deployment

```bash
docker-compose up -d
```

---

# Screenshots

## Application Dashboard

(Add screenshot here)

---

## Real-Time Chat

(Add screenshot here)

---

## Media Upload

(Add screenshot here)

---

# Future Enhancements

* AI-powered recommendations
* Push Notifications
* Mobile Application
* Microservices Architecture
* Video Calling
* Analytics Dashboard

---

# Learning Outcomes

This project demonstrates:

* Full-stack development expertise
* Real-time application architecture
* DevOps & CI/CD implementation
* Testing strategies
* Cloud integrations
* Secure backend development
* Scalable application deployment

---

# Author

## Manjula Kalluri

* Full Stack Developer
* Backend Engineer
* DevOps Enthusiast

GitHub:

```bash
https://github.com/your-username
```

LinkedIn:

```bash
https://linkedin.com/in/your-profile
```

---

# License

This project is developed for educational and portfolio purposes.

MIT License.
