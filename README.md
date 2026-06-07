# Mental Health Support Platform

## Overview

The Mental Health Support Platform is a full-stack web application designed to connect patients with mental health professionals. The platform allows users to register, book appointments, manage consultations, and access prescriptions through a secure and user-friendly interface.

The system aims to improve accessibility to mental health services by providing a streamlined online appointment booking and management solution.

## Features

### Patient Features
- User Registration and Login
- Secure Authentication using JWT
- Book Appointments with Doctors
- View Appointment History
- Access Prescriptions
- Manage Personal Profile

### Doctor Features
- Doctor Dashboard
- View Scheduled Appointments
- Manage Patient Consultations
- Create and Manage Prescriptions
- Track Patient Records

### Security Features
- JWT Authentication
- Password Encryption using Bcrypt
- Rate Limiting
- Input Validation
- Protected Routes
- Secure API Access

## Tech Stack

### Frontend
- React.js
- Vite
- React Router
- React Query
- Axios
- React Hook Form

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- Bcrypt.js

### DevOps & Deployment
- Docker
- Docker Compose
- GitHub Actions CI/CD

## Project Structure

```text
psych-booking/
│
├── frontend/
│   ├── src/
│   ├── pages/
│   ├── hooks/
│   └── utils/
│
├── backend/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── validators/
│   └── tests/
│
├── docker-compose.yml
└── README.md
```

## Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/psych-booking.git
```

### Backend Setup

```bash
cd backend
npm install
npm run dev
```

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

## Environment Variables

Create a `.env` file inside the backend folder:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

## API Modules

- Authentication API
- Doctor Management API
- Appointment Booking API
- Prescription Management API

## Testing

Run backend tests:

```bash
npm test
```

Generate coverage report:

```bash
npm run test:coverage
```

## Future Enhancements

- Video Consultation Integration
- AI-based Mental Health Assistant
- Online Payments
- Appointment Reminders
- Medical Report Upload
- Real-time Chat Support

## Screenshots

Add screenshots of:
- Login Page
- Patient Dashboard
- Doctor Dashboard
- Appointment Booking Page

## Author

**Ashlesha Gawkar**

B.Tech Computer Science Engineering  
MIT World Peace University (MIT-WPU)

## License

This project is developed for educational and learning purposes.
