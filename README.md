Project URL : https://login-app-blue-phi.vercel.app/ <br/>
Project Brief Explanation URL :  https://www.loom.com/share/b7cc8b5ee550444facb87d7362a20bec

# Login Application (React + Node.js)

## Overview

This project is a simple Login Application built using **React** for the frontend and **Node.js with Express** for the backend.
It allows users to log in using a username and password, validates credentials through a backend API, and redirects the user to a Welcome page upon successful login.

This project was developed as part of a **Full-Stack Developer technical assignment**.

---

## Tech Stack

**Frontend**

* React
* React Hooks
* Axios
* React Router

**Backend**

* Node.js
* Express
* CORS


---

## Features

* Login page with username and password fields
* Backend API for credential validation
* Navigation to Welcome page after successful login
* Error message for invalid credentials
* Username stored in localStorage for subsequent logins
* Proper HTTP status codes used in backend responses

---
## Installation and Setup

### 1. Clone the repository

git clone https://github.com/eshwarrao123/login-app.git

cd login-app

### 2. Run Backend

cd backend

npm install

node server.js

The backend server will run on:

http://localhost:5000

### 3. Run Frontend

Open another terminal:

cd frontend

npm install

npm start

The React app will run on:

http://localhost:3000

---

## Login Credentials

Use the following credentials to test the application:

Username: admin
<br/>
Password: admin

---

## API Endpoint

POST /login

Request Body

{
"username": "admin",
"password": "admin"
}

Response

200 OK → Login successful <br/>
401 Unauthorized → Invalid credentials

---

