# Seniero Web Application

## Overview
Full-stack web application for connecting young volunteers with elderly people to provide services and assistance. Frontend is built with Angular, backend with Spring Boot, and it uses a SQL database to manage users and tasks.

Figma Design Link: https://www.figma.com/proto/EQba7BaTZGWYIEtM0LBrI0/USP-Projekat?node-id=1-427&starting-point-node-id=1%3A427&t=YPxNabzCXbqTXmeq-1

## Getting Started

### 1. Clone the project
git clone <repository-url>

### 2. Frontend Setup
cd front
npm install
npm start
- Runs at http://localhost:4200

### 3. Backend & Database Setup
1. Import the SQL database into SQL Workbench.
2. If your database password is different, update it in:
backend/src/main/java/db/DB.java
