# PASQCO

**PASQCO** is an edtech platform that enables students to prepare for examinations by answering multiple-choice questions (MCQs) based on school topics and levels. Designed by a student, for students — PASQCO transforms learning into a smart, interactive experience.

---

## 🚀 Features

- 🎯 Topic and level-based MCQs
- 🧠 Real-time answering system
- 📊 Live performance results
- 💬 Comments based on performance
- 📈 User progress tracking and analysis

---

## 🛠 Tech Stack

- **Frontend**: React (JavaScript)
- **Backend**: Node.js + Express
- **Database**: MongoDB
- **Authentication**: JWT
- **Package Manager**: Yarn

---

## 🧪 System Design Overview

### 🖥️ Frontend

- Built with React
- Communicates with backend via REST API
- Handles user session, routing, and real-time interaction

### 🧳 Backend (API Server)

- Built using Express
- Routes:
  - `/api/auth` - Handles login/signup
  - `/api/questions` - Fetches and submits questions
  - `/api/results` - Records and analyzes user responses
- Middleware: Auth protection using JWT

### 💾 Database (MongoDB)

- `users`: Stores student profiles, progress, and authentication
- `questions`: Holds categorized MCQs based on topics and levels
- `results`: Stores user attempts, scores, and performance feedback

### ⚙️ Performance Engine (planned)

- Auto-grades MCQs
- Analyzes performance metrics
- Suggests focus areas and generates comments

---

## 📂 Project Structure
