# 🌦️ Weather Forecast Application

A full-stack weather forecasting application built using React.js, Node.js, Express.js, and the OpenWeatherMap API.

## 📌 Project Overview

The Weather Forecast Application retrieves real-time weather information for any city using the OpenWeatherMap API. The frontend is developed using React.js and the backend is built with Node.js and Express.js.

## 🚀 Features

- Search weather by city name
- Real-time temperature display
- Humidity information
- Wind speed details
- Weather description
- Backend API proxy for security
- Error handling
- Dynamic UI updates

## 🛠️ Technologies Used

### Frontend
- React.js
- CSS
- Axios

### Backend
- Node.js
- Express.js
- dotenv
- CORS

### API
- OpenWeatherMap API

## 📂 Project Structure

Weather-App/
├── backend/
│   ├── server.js
│   └── .env
│
└── frontend/
    ├── public/
    ├── src/
    │   ├── App.js
    │   ├── App.css
    │   └── index.js

## ⚙️ Installation

### Backend

```bash
cd backend
npm install
node server.js
Frontend
Bash
cd frontend
npm install
npm install axios
npm start
🔑 Environment Variables
Create a .env file:
Environment
PORT=5000
API_KEY=YOUR_OPENWEATHER_API_KEY
🌐 API Endpoint
GET /api/weather/:city
Example:
http://localhost:5000/api/weather/Chennai⁠�
🔒 Security Features
API key stored in environment variables
Backend proxy protects API key
Error handling implemented
🔮 Future Enhancements
5-day forecast
Dark mode
Weather icons
Geolocation support
Responsive design
👨‍💻 Author
RAKSHITHA S
B.Tech Information Technology
Panimalar Engineering College
📜 License
This project is developed for educational purposes.
