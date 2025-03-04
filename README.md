# Doctor Search & Appointment Booking System

## Overview

This project is a MERN Stack application that allows patients to search for doctors and book appointments. Doctors can  manage their appointments. The system includes authentication, search functionality, booking management, and notifications.

## 1. User Authentication & Role Management

-JWT-based authentication for Doctors and Patients.

-Secure password hashing with bcrypt.

-Patients can register/login and book appointments.

-Doctors can register/login and manage appointments.

## 2. Doctor Search & Profile Management

-Patients can search for doctors by:

-Specialty (e.g., Cardiologist, Dermatologist)

-Doctor’s Name (Partial match search)

-Individual Doctor Profile Page with:

-Name, Specialty, And Experience.
## 3. Appointment Booking System
-Patients can book an available slot with a doctor.

-Notifications for bookings.
## 4. Web Interface (Frontend)

-Patient Portal:

-Search for doctors.

-Book appointments.

Doctor Dashboard:
-View upcoming appointments.

-Built with React.js and Tailwind CSS.

-Redux/Context API for state management.
## 5. Deployment & Documentation

-Backend deployed on: Vercel

-Frontend deployed on: Vercel

-Live Demo: https://doctor-appointment-z2xh.vercel.app/

-Detailed documentation included.

## Tech Stack
| Category |Technology |
|----------|----------|
| Backend | Node.js, Express.js, MongoDB, Mongoose  | 
| Frontend  |React.js, Tailwind CSS, Redux/Context API   | 
| Authentication | JWT, bcrypt.js | 
| Database  |MongoDB   | 

## Installation & Setup

## Backend Setup

1.Clone the repository

git clone https://github.com/chandu-uias/DoctorAppointment.git

cd DoctorAppointment/backend

2.Install dependencies:

  npm install
  
3.Set up environment variables in .env file:

  MONGO_URI=your_mongodb_connection_string
  
  JWT_SECRET=your_secret_key


4.Start the backend server:

  npm run dev/npm start

## Frontend Setup

Navigate to the frontend folder:

cd ../frontend

Install dependencies:

npm install

Start the frontend server:

npm start/npm run dev

## API Endpoints

| Method  | Endpoint              | Description                      |
|---------|----------------------|----------------------------------|
| POST    | /api/auth/register   | Register a new user             |
| POST    | /api/auth/login      | Login user and return JWT token |


