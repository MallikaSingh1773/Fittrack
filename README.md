# FitTrack

## Overview
**FitTrack** is a fitness tracking website built using the **MERN (MongoDB, Express, React, Node.js) Stack**. It helps users monitor their fitness journey by tracking workouts, diet, and progress over time.

## Tech Stack
- **Frontend:** React.js
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **State Management:** Context API / Redux
- **Authentication:** JWT

## Features
- User Authentication (Signup/Login)
- Workout Tracking
- Diet Management
- Progress Reports
- Goal Setting

## Installation & Setup

### Prerequisites
Ensure you have the following installed:
- Node.js (v16 or later)
- MongoDB
- Git

### Steps to Run Locally
1. **Clone the Repository**
   ```sh
   git clone https://github.com/MallikaSingh1773/Fittrack.git
   cd Fittrack
   ```

2. **Backend Setup**
   ```sh
   cd backend
   npm install
   npm start
   ```
   The backend will start running at `http://localhost:5000`

3. **Frontend Setup**
   ```sh
   cd frontend
   npm install
   npm start
   ```
   The frontend will start running at `http://localhost:3000`

## API Endpoints
| Method | Endpoint | Description |
|--------|---------|-------------|
| GET | `/api/workouts` | Fetch all workouts |
| POST | `/api/workouts` | Add a new workout |
| GET | `/api/diet` | Fetch diet plans |
| POST | `/api/users/login` | User login |
| POST | `/api/users/register` | User registration |

## Contributing
Contributions are welcome! If you’d like to contribute, please fork the repository and submit a pull request.
