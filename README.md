# 🩺 WellTrack – Personal Health & Diet Tracker

<p align="center">
  <b>A Full-Stack Web Application for Personal Health, Nutrition & Fitness Management</b>
</p>

<p align="center">
  Track your health, manage your diet, monitor your progress, and make better lifestyle decisions with WellTrack.
</p>

---

## 📌 About The Project

**WellTrack** is a full-stack personal health and diet tracking web application designed to help users manage their health and fitness activities through a single platform.

It provides features for monitoring daily food intake, calculating health metrics, planning meals, tracking fitness progress, and generating health reports. The application also includes **HealthMate**, a built-in assistant for health and nutrition-related queries.

## ✨ Key Features

- 🔐 **User Authentication** – Secure user registration and login with password hashing and JWT authentication.
- 📊 **Interactive Dashboard** – View important health information and daily statistics in one place.
- 👤 **Health Profile** – Manage personal details, health information, and activity preferences.
- ⚖️ **BMI & Health Calculations** – Calculate BMI, BMR, TDEE, and estimated daily calorie requirements.
- 🥗 **Diet Tracking** – Record daily food intake and monitor nutritional values.
- 🍎 **Food Library** – Explore a nutrition dataset containing information about different food items.
- 📅 **7-Day Meal Planner** – Organize meals and manage meal-planning preferences.
- 📈 **Progress Tracking** – Monitor weight changes and daily health records.
- 📄 **Health Reports** – Generate printable health and progress reports.
- 🤖 **HealthMate Assistant** – Get assistance with health and nutrition-related questions.
- 💧 **Water & Activity Tracking** – Maintain daily records of water intake and physical activity.

## 🖥️ Application Modules

| Module | Description |
|---|---|
| Dashboard | Displays health statistics and daily information |
| Authentication | Handles registration, login, and user access |
| Health Profile | Manages personal health information |
| Diet Tracker | Records food consumption and nutrition |
| Food Library | Provides food and nutrition information |
| Meal Planner | Supports 7-day meal planning |
| Progress | Tracks health and fitness progress |
| Health Reports | Generates printable reports |
| HealthMate | Provides health and nutrition assistance |

## 🛠️ Technologies Used

### Frontend
- ⚛️ React.js – Component-based user interface development.
- ⚡ Vite – Fast frontend development server and build tool.
- 🟨 JavaScript – Application functionality and logic.
- 🎨 CSS3 – Styling and responsive user interface.
- 🧩 Lucide React – Icons and visual elements.

### Backend
- 🟢 Node.js – JavaScript runtime for server-side development.
- 🚀 Express.js – Backend framework for APIs and application routing.

### Database
- 🍃 MongoDB – NoSQL database for storing application data.
- 🔗 Mongoose – Object Data Modeling (ODM) for MongoDB.

### Security & Additional Tools
- 🔑 JSON Web Token (JWT) – Authentication and protected API access.
- 🔒 Bcrypt.js – Secure password hashing.
- 📧 Nodemailer – Email-related functionality.
- ⚙️ Dotenv – Environment variable management.
- 🐍 Python – Food dataset processing.
- 🐙 Git & GitHub – Version control and project management.
- 📦 npm – Package and dependency management.

## 🏗️ System Architecture

WellTrack follows a full-stack client-server architecture.

1. **Frontend Layer:** React handles the user interface and user interactions.
2. **Backend Layer:** Node.js and Express.js process requests, manage application logic, and provide REST API endpoints.
3. **Database Layer:** MongoDB stores user profiles, authentication-related data, preferences, and tracking records.
4. **Shared Logic:** Reusable JavaScript modules support health calculations, meal planning, and assistant functionality.

## 📂 Project Structure

```text
WellTrack/
│
├── public/
│   └── datasets/
│       └── foods-clean.json
│
├── server/
│   ├── models/
│   ├── routes/
│   └── server files
│
├── shared/
│   ├── engine.mjs
│   ├── meals.mjs
│   ├── chat.mjs
│   └── demo.mjs
│
├── scripts/
│   └── build-food-dataset.py
│
├── datasets/
│   └── Food_Nutrition_dataset.csv
│
├── src/
│   └── Frontend application files
│
├── package.json
└── README.md
```

*Note: This is a simplified overview of the main project components.*

## ⚙️ Installation & Setup

Follow these steps to run WellTrack locally.

### Prerequisites

Make sure you have the following installed:

- Node.js
- npm
- MongoDB
- Git

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd WellTrack
```

### 2. Install Frontend Dependencies

From the project root directory, run:

```bash
npm install
```

### 3. Install Backend Dependencies

```bash
cd server
npm install
```

### 4. Configure Environment Variables

Configure the required environment variables in the backend `.env` file according to the project's server configuration.

Make sure MongoDB is running and the database connection is configured correctly.

### 5. Start the Backend Server

From the `server` directory, run:

```bash
npm start
```

The backend API runs at:

`http://localhost:5000`

### 6. Start the Frontend

Open another terminal in the project root directory and run:

```bash
npm run dev
```

The frontend application runs at:

`http://localhost:5173`

Open the frontend URL in your browser to access WellTrack.

## 📸 Project Screenshots

Screenshots of the main application modules can be added here.

Recommended screenshots:

- Dashboard
- Login & Registration
- Health Profile
- Diet Tracker
- Food Library
- Meal Planner
- Progress Tracking
- Health Reports
- HealthMate Assistant

## 🤖 HealthMate Assistant

WellTrack includes a built-in HealthMate assistant that supports health and nutrition-related queries.

An optional Anthropic API integration is available for enhanced assistant functionality. This requires configuring the appropriate API key in the environment.

## 🔒 Security & Data Management

- Passwords are hashed using Bcrypt.js.
- JWT-based authentication is used for protected routes.
- Backend APIs manage access to application data.
- MongoDB stores user and tracking information.
- Environment variables are used for configuration and sensitive credentials.

## ⚠️ Limitations

- Health calculations provide estimates and may not represent exact medical measurements.
- Nutrition information depends on the available food dataset.
- HealthMate's optional external AI integration requires an API key.
- The application is intended for general wellness tracking and does not replace professional medical advice.

## 🚀 Future Enhancements

- Advanced health analytics and visualizations.
- Additional food and nutrition datasets.
- More personalized meal recommendations.
- Enhanced assistant capabilities.
- Additional health tracking features.

## 👨‍💻 Developer

**Alok Gupta**

MCA Student | Full Stack Development

## 📄 License

This project has been developed for academic and educational purposes.

---

<p align="center">
  <b>WellTrack – Track Better. Eat Better. Live Better. 💚</b>
</p>
