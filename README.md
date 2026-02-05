# E-Waste Recycling Locator

A full-stack web application that allows users to register, log in, and schedule e-waste pickup requests with proper backend validation and database storage.

This project focuses on frontend–backend integration, REST APIs, database handling, and runtime validations.

---

## Features

### User Management
- User registration and login
- Auto-generated User ID
- Forgot password (account reset)

### Pickup Scheduling
- Schedule e-waste pickup with:
  - City and exact location
  - Multiple item types (Laptop, Mobile, TV, etc.)
  - Custom item entry using “Other”
  - Preferred date and time slot
- Backend validations:
  - Pickup date must be in the future
  - Pickup time allowed between 9 AM and 7 PM
  - Service restricted to Hyderabad

### Backend Processing
- User ID verification before scheduling pickup
- Server-side input validation
- Error handling for invalid requests
- Data stored using MongoDB

---

## Tech Stack

**Frontend**
- HTML
- CSS
- JavaScript

**Backend**
- Node.js
- Express.js
- MongoDB (Mongoose)

---

## Project Structure

E-waste-recycling-Locator/
├── index.html
├── styles.css
├── server.js
└── README.md


---

## Setup Instructions

1. Install dependencies  
```bash
npm install
Start MongoDB locally

mongodb://127.0.0.1:27017/ewaste
Run the server

node server.js
Open in browser

http://localhost:3000
API Endpoints
POST /api/register-login – User registration and login

POST /api/forgot-password – Reset account

POST /schedule-pickup – Schedule e-waste pickup

Learning Outcomes
Built an end-to-end web application

Implemented REST APIs using Express

Worked with MongoDB schemas and queries

Performed server-side validation

Understood real-world application workflows


Author
Sameela Rathnagari
B.E – Computer Science and Engineering
Mahatma Gandhi Institute of Technology, Hyderabad

LinkedIn: https://www.linkedin.com/in/sameela-rathnagari-374779354
