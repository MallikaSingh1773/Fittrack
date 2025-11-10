# **FitTrack**

## **Overview**

**FitTrack** is an advanced fitness tracking platform built using the **MERN (MongoDB, Express, React, Node.js) Stack**. It empowers users to monitor their fitness journey with real-time insights, personalized AI recommendations, and interactive progress tracking.

Along with traditional fitness logging, **FitTrack integrates VAPI-based AI assistance** that interacts with users, answers their health-related queries, suggests diets, and even generates customized daily/weekly fitness reports.

---

## **Tech Stack**

* **Frontend:** React.js
* **Backend:** Node.js, Express.js
* **Database:** MongoDB
* **State Management:** Context API / Redux
* **Authentication:** JWT
* **AI Integration:** VAPI for conversational fitness assistance & report generation

---

## **Key Features**

### 🔐 **User Authentication**

Secure signup/login with JWT-based authentication.

### 🏋️ **Workout Tracking**

Add, edit, and monitor daily workouts with detailed stats.

### 🍎 **Diet Management**

Track meals, calories, macros, and get AI-powered nutrition suggestions.

### 📊 **Progress Reports**

Visual dashboards showing weekly/monthly improvements.

### 🎯 **Goal Setting**

Set fitness goals and monitor progress with reminders & insights.

### 🤖 **AI Fitness Bot (VAPI Integration)**

FitTrack includes an intelligent bot that:

* Chats with the user in real-time
* Suggests personalized diet and workout plans
* Generates weekly fitness reports
* Notifies users about missed goals
* Helps maintain consistency with motivational prompts

This makes FitTrack feel like a personal trainer—always available, interactive, and tailored to your needs.

---

## **Installation & Setup**

### **Prerequisites**

Make sure you have:

* Node.js (v16 or higher)
* MongoDB
* Git installed

---

### **1. Clone the Repository**

```sh
git clone https://github.com/MallikaSingh1773/Fittrack.git
cd Fittrack
```

### **2. Backend Setup**

```sh
cd backend
npm install
npm start
```

Backend runs at: **[http://localhost:5000](http://localhost:5000)**

### **3. Frontend Setup**

```sh
cd frontend
npm install
npm start
```

Frontend runs at: **[http://localhost:3000](http://localhost:3000)**

---

## **API Endpoints**

| Method | Endpoint              | Description        |
| ------ | --------------------- | ------------------ |
| GET    | `/api/workouts`       | Fetch all workouts |
| POST   | `/api/workouts`       | Add a new workout  |
| GET    | `/api/diet`           | Fetch diet plans   |
| POST   | `/api/users/login`    | User login         |
| POST   | `/api/users/register` | User registration  |

---

## **Contributing**

Contributions are welcome!
Fork the repository, make your changes, and submit a pull request.


If you want, I can also rewrite this in a **GitHub README format**, **portfolio format**, or a **short version** for LinkedIn/project description.
