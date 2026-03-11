# Mobile Commerce Platform – Spring Boot + Ionic

Full-stack mobile commerce platform demonstrating how a mobile application interacts with a backend API to handle authentication, product browsing, cart management, and order processing.

The project simulates a real-world shopping application where users can browse products, manage their profile, and place orders through a mobile interface.

![Java](https://img.shields.io/badge/Backend-Java-blue)
![Spring Boot](https://img.shields.io/badge/Framework-SpringBoot-green)
![Ionic](https://img.shields.io/badge/Mobile-Ionic-blue)
![Angular](https://img.shields.io/badge/Frontend-Angular-red)
![MySQL](https://img.shields.io/badge/Database-MySQL-orange)
![Auth](https://img.shields.io/badge/Auth-JWT-purple)
![Storage](https://img.shields.io/badge/Storage-AWS%20S3-yellow)
![API](https://img.shields.io/badge/API-REST-green)
![Cloud](https://img.shields.io/badge/Cloud-AWS-orange)

---

<p align="center">
  <img src="https://raw.githubusercontent.com/Thiago771414/imagensProjetos/main/slices/mobile/diagramaIonic.png" width="900">
</p>

---

# Problem

Mobile commerce applications require reliable backend services capable of handling authentication, product catalogs, shopping carts, and order workflows.

Developers must integrate multiple technologies such as authentication systems, cloud storage, image upload, and database persistence while maintaining a secure API.

---

# Solution

This project demonstrates a full-stack architecture composed of:

Mobile application (Ionic + Angular)

Backend API (Java Spring Boot)

Cloud services for storage and communication

The platform implements a complete user journey:

• user registration and login  
• product browsing  
• shopping cart management  
• order confirmation workflow  
• user profile with photo upload  

---

# Architecture

Mobile App (Ionic / Angular)  
↓  
REST API (Spring Boot)  
↓  
MySQL Database  

External services:

• Amazon S3 for image storage  
• SMTP email notifications  
• JWT authentication  

---

# Screenshots

## Login Screen

<p align="center">
  <img src="https://raw.githubusercontent.com/Thiago771414/imagensProjetos/main/slices/mobile/loginIonic.png" width="90">
</p>

---

## Product Catalog

<p align="center">
  <img src="https://raw.githubusercontent.com/Thiago771414/imagensProjetos/main/slices/mobile/categoriasIonic.png" width="90">
</p>

---

## Menu

<p align="center">
  <img src="https://raw.githubusercontent.com/Thiago771414/imagensProjetos/main/slices/mobile/menuIonic.png" width="90">
</p>

---
## Profile
<p align="center">
  <img src="https://raw.githubusercontent.com/Thiago771414/imagensProjetos/main/slices/mobile/PerfilIonic.png" width="90">
</p>
---

# Key Features

• JWT authentication  
• user profile with image upload  
• Amazon S3 image storage  
• email notifications  
• shopping cart workflow  
• order processing API  

---

# Technology Stack

Backend

Java  
Spring Boot  
JPA / Hibernate  
MySQL  
JWT Authentication  

Frontend

Ionic 3  
Angular 5  

Cloud

Amazon S3  
SMTP Email Service  

---

# Note on Dependencies

This project was originally developed using Ionic 3 and Angular 5 as part of a learning program.

Some dependency alerts reported by GitHub Dependabot are related to legacy versions used in the course and are maintained for historical reference.

---

# Learning Context

This project was developed as part of the following training program:
```bash
https://www.udemy.com/course/spring-boot-ionic/
```
---

# Author

Thiago Reis Lima  
Software Engineer

LinkedIn
```bash
https://www.linkedin.com/in/thiago-lima-2a5896166/
```
