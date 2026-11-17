# WellTrack – Personal Health & Diet Tracker

WellTrack is a full-stack web application designed to help users monitor and manage their personal health, nutrition, diet, and fitness progress through a single platform.

The application provides tools for tracking daily food intake, monitoring health metrics, planning meals, and viewing progress through reports and dashboards.

## Key Features

- **User Authentication:** Secure registration and login with password hashing and JWT-based authentication.
- **Personal Health Profile:** Manage personal health information and activity preferences.
- **Dashboard:** View important health and nutrition information in one place.
- **BMI & Calorie Calculation:** Calculate BMI, BMR, TDEE, and estimated daily calorie requirements.
- **Diet Tracker:** Record daily food intake and monitor nutritional information.
- **Food Library:** Explore a food dataset containing nutritional information.
- **Meal Planner:** Plan meals using a 7-day meal-planning feature.
- **Progress Tracking:** Monitor changes in weight and other daily health records.
- **Health Reports:** Generate printable health and progress reports.
- **HealthMate Assistant:** Get assistance with health and nutrition-related queries through the built-in assistant.

## Technology Stack

### Frontend
- React.js
- JavaScript
- HTML5
- CSS3
- Vite
- Lucide React

### Backend
- Node.js
- Express.js

### Database
- MongoDB
- Mongoose

### Additional Tools & Libraries
- Git and GitHub
- Python
- JSON Web Token (JWT)
- Bcrypt.js
- Nodemailer
- Dotenv

## Project Architecture

The project follows a full-stack architecture:

- **Frontend:** Provides the user interface and handles user interactions.
- **Backend:** Handles application logic, authentication, and API requests.
- **Database:** Stores user information, health profiles, preferences, and tracking records.

## Project Modules

1. User Authentication
2. Dashboard
3. Health Profile
4. Diet Tracking
5. Food Library
6. Meal Planning
7. Progress Tracking
8. Health Reports
9. HealthMate Assistant

## Installation and Setup

### Prerequisites

- Node.js and npm
- MongoDB
- Git

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd WellTrack
```

### 2. Install Frontend Dependencies

```bash
npm install
```

### 3. Install Backend Dependencies

```bash
cd server
npm install
```

Configure the required backend environment variables before starting the server. Refer to the project's server configuration.

### 4. Start the Backend

```bash
npm start
```

### 5. Start the Frontend

Open another terminal in the project root directory and run:

```bash
npm run dev
```

The frontend development server runs at:

`http://localhost:5173`

The backend API runs at:

`http://localhost:5000`

Make sure MongoDB is running before starting the application.

## HealthMate Assistant

WellTrack includes a built-in HealthMate assistant for health and nutrition-related queries. An optional Anthropic API integration can also be configured using an API key.

## Important Note

The health calculations and nutritional information provided by this application are estimates for general wellness purposes and should not be considered professional medical advice.

## Project Status

The major application modules have been implemented. Further improvements, testing, and documentation can be carried out as part of future development.

## Author

**Alok Gupta**

MCA Student | Software Development

## License

This project is developed for academic and educational purposes.
