# AI Habit Tracker

AI-powered full-stack habit tracking application built with the MERN stack and Google Gemini AI.

## Features

- JWT Authentication
- Habit creation and management
- Daily habit completion tracking
- Streak calculations
- Heatmap analytics
- AI-generated weekly reports
- Personalized habit suggestions
- Recovery plans for broken streaks
- AI-powered habit analysis chat
- Morning motivation generation

---

# Tech Stack

## Frontend
- React
- Vite
- Axios
- Tailwind CSS

## Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication

## AI Integration
- Google Gemini API

---

# Project Structure

```bash
backend/
frontend/
```

---

# Environment Variables

Create a `.env` file inside the backend folder:

```env
PORT=8000

MONGO_URI=your_mongodb_uri

JWT_SECRET=your_secret

JWT_EXPIRES_IN=30d

GEMINI_API_KEY=your_gemini_api_key

GEMINI_MODEL=gemini-2.5-flash

CLIENT_URL=http://localhost:5173
```

---

# Installation

## Backend

```bash
cd backend
npm install
npm run dev
```

## Frontend

```bash
cd frontend/ai-habit-tracker-ui-boilerplate-code
npm install
npm run dev
```

---

# Seed Demo Data

```bash
cd backend
npm run seed
```

---

# API Routes

## Auth
- POST `/api/auth/register`
- POST `/api/auth/login`
- GET `/api/auth/me`

## Habits
- GET `/api/habits`
- POST `/api/habits`
- PUT `/api/habits/:id`
- DELETE `/api/habits/:id`

## Logs
- POST `/api/logs`
- GET `/api/logs/today`
- GET `/api/logs/heatmap`

## AI
- POST `/api/ai/weekly-report`
- POST `/api/ai/suggest-habits`
- POST `/api/ai/recovery-plan`
- POST `/api/ai/chat`
- GET `/api/ai/morning`

---

# Future Improvements

- Docker support
- Mobile app
- OAuth login
- Email reminders
- Real-time notifications
- Habit sharing system

---

# Author

Aylin Günay
