# Quiz-Platform-With-Leaderboard

## 📌 Intern Details
* **Domain:** Full Stack Web Development
* **Intern ID:** CITS2364
* **Name:** Jamili Lahari
* **Duration:** 6 Weeks
* **Organization:** CodTech IT Solutions

## 🚀 Project Overview
A Full Stack Quiz Platform designed to provide an engaging and interactive quiz-taking experience. The application features dynamic quiz questions, real-time score tracking, and a global leaderboard that updates instantly to encourage competitive and fun learning.

## ✨ Features
* **Interactive Quiz Interface:** Multiple-choice questions with countdown timers and immediate score feedback.
* **Live Leaderboard:** A global ranking system that displays top-performing users dynamically based on score and time.
* **User Accounts:** Secure registration and login to keep track of quiz history and highest scores.
* **Admin Controls:** Simple dashboard layout to create, edit, or delete quiz categories and questions.

## 🛠️ Tech Stack
* **Frontend:** React, CSS3 / Tailwind CSS, JavaScript (ES6)
* **Backend:** Node.js, Express.js
* **Database:** MongoDB

## 🏃 How to Run the Project
1. **Clone the repository:**
   ```bash
   git clone https://github.com
   cd Quiz-Platform-With-Leaderboard
   ```

2. **Set up the backend:**
   ```bash
   cd backend
   npm install
   ```
   * Create a `.env` file in the `backend` folder and add your configuration:
     ```env
     PORT=5000
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_secret_encryption_key
     ```
   * Start the server:
     ```bash
     npm start
     ```

3. **Set up the frontend:**
   ```bash
   cd ../frontend
   npm install
   npm start
   ```

4. **Access the application:**
   * Open your browser and navigate to `http://localhost:3000`.
