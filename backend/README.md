# Backend - Restaurant Management System

This is the backend API for the Restaurant Management System. It is built with Node.js, Express, and MongoDB.

## Features
- User authentication (admin, waiter, chef, customer)
- Menu, table, order, reservation, and feedback management
- Role-based access control
- Email notifications (password reset, etc.)
- System logging

## Setup Instructions

1. **Install dependencies:**
   ```sh
   cd backend
   npm install
   ```
2. **Configure environment variables:**
   - Create a `.env` file in the `backend/` directory with your MongoDB URI and any email credentials needed for Nodemailer.
   - Example:
     ```env
     MONGODB_URI=your_mongodb_connection_string
     SECRET=your_jwt_secret
     USER=your_email@example.com
     PASS=your_email_password
     ```
3. **Start the server:**
   ```sh
   node server.js
   ```

## Folder Structure
- `models/` - Mongoose schemas
- `controllers/` - Business logic
- `routes/` - Express routers
- `middlewares/` - Middleware functions
- `utils/` - Helper utilities (email, logging, etc.)
- `configs/` - Database config

## API Endpoints
- `/user` - User registration and login
- `/admin` - Admin functions
- `/customer` - Customer functions
- `/chef` - Chef functions
- `/waiter` - Waiter functions

---

For frontend setup, see the `frontend/README.md`.
