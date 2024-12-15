# Company Trip Lottery System

A professional lottery system for managing company employee trips.

## Features

- Employee Management
- Trip Management
- Lottery Drawing System
- Results Display
- History Tracking

## Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   cd client && npm install
   ```

3. Create a .env file in the root directory with:
   ```
   PORT=5000
   MONGODB_URI=your_mongodb_uri
   JWT_SECRET=your_secret_key
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

## Technologies Used

- Backend: Node.js, Express
- Frontend: React
- Database: MongoDB
- Authentication: JWT
- Real-time updates: Socket.io

## API Endpoints

### Employees
- GET /api/employees - Get all employees
- POST /api/employees - Add new employee

### Trips
- GET /api/trips - Get all trips
- POST /api/trips - Add new trip

### Lottery
- POST /api/lottery/draw - Start new lottery draw
- GET /api/lottery/results - Get lottery results
