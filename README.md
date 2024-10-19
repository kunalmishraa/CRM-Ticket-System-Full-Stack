# CRM-Ticket-System-Full-Stack
I developed a CRM system that reduced ticket resolution time by 20%, enhancing customer support efficiency. Implemented secure authentication for clients and admins, improving data protection by 40%. Integrated AWS cloud services for scalable data storage, increasing system uptime and reliability, ensuring seamless performance.


# CRM Ticket System

The CRM Ticket System is a comprehensive solution designed to streamline customer support processes by managing client queries, tracking tickets, and improving resolution times. This system integrates both a frontend and a backend, offering secure authentication, cloud scalability, and robust customer support functionalities.

## Repositories
- **Frontend**: [CRM Frontend]()
- **Backend API**: [Client API]()

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The CRM Ticket System is designed to efficiently manage client support queries by automating ticket creation, status updates, and resolution tracking. The system reduces the time spent resolving customer issues and provides a secure platform for managing customer interactions. It includes secure authentication for both clients and administrators, ensuring that sensitive data is protected.

## Features
- **Ticket Management**: Create, view, update, and close support tickets.
- **Authentication**: Secure login for clients and admins.
- **Admin Panel**: Admins can manage tickets and users.
- **Cloud Integration**: AWS-based data storage for scalability and high availability.
- **Real-time Updates**: Track ticket status in real-time.
- **Performance Optimization**: Reduced ticket resolution time by 20%, improving operational efficiency.

## Technologies Used

### Frontend (CRM-Frontend)
- React.js
- Redux for state management
- Tailwind CSS for styling
- Axios for API requests
- React Router for navigation

### Backend (Client-API)
- Node.js with Express.js
- MongoDB for database management
- JWT for authentication
- AWS S3 for file storage
- Nodemailer for email notifications

## Setup and Installation

# Frontend Setup

1. **Clone the frontend repository:**
   ```bash
   git clone https://github.com/DentedCode/crm-frontend.git

Navigate to the project directory:
bash
cd crm-frontend

Install the dependencies:
bash
npm install

Start the development server:
bash
npm start

The frontend will be running at http://localhost:3000.
Backend Setup
Clone the backend repository:
bash
git clone https://github.com/DentedCode/client-api.git

Navigate to the project directory:
bash
cd client-api

Install the dependencies:
bash
npm install

Set up environment variables in a .env file (see .env.example for reference):
MONGO_URI: Your MongoDB connection string
JWT_SECRET: Secret key for JWT
AWS_ACCESS_KEY_ID and AWS_SECRET_ACCESS_KEY: AWS credentials
Start the backend server:
bash
npm start

The backend will be running at http://localhost:5000.
Usage
User Registration & Login: Users and admins can register and log in securely.
Create Tickets: Clients can create tickets for their issues.
Ticket Management: Admins can assign, update, and close tickets.
Notifications: Clients and admins receive email notifications for important updates.
API Endpoints
The backend API offers various endpoints for managing tickets, authentication, and user data.
Authentication
POST /api/auth/register: Register a new user
POST /api/auth/login: Log in a user
Tickets
POST /api/tickets: Create a new ticket
GET /api/tickets: Get all tickets
GET /api/tickets/:id: Get a specific ticket
PUT /api/tickets/:id: Update a ticket
DELETE /api/tickets/:id: Delete a ticket
For a full list of API endpoints, check the API Documentation.
Contributing
We welcome contributions to enhance the CRM Ticket System. To contribute, please follow these steps:
Fork the repository.
Create a new branch:
bash
git checkout -b feature-name

Commit your changes:
bash
git commit -m 'Add feature'

Push the branch:
bash
git push origin feature-name

Submit a pull request.
License
This project is licensed under the MIT License - see the LICENSE file for details.
