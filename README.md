**🌦️ Weather App – React**

A simple, clean, and responsive React-based weather app that allows users to check real-time weather conditions by entering a city name. Built using React, CSS, and the OpenWeatherMap API.

**📸 Demo**

Live Site: https://your-deployed-link.render.com


**🚀 Features**

🌍 Search weather by city name

🌡️ Display temperature in Celsius

☁️ Show weather conditions with relevant icons

💧 Show humidity and wind speed

📱 Fully responsive design

⚡ Real-time API data using fetch

**🛠️ Tech Stack**

React (Vite or CRA)

CSS3

OpenWeatherMap API

JSX

Fetch API

**🔐 API Key**

To use this app, you need an API key from OpenWeatherMap:

Sign up and get your free API key.

In your project, create a .env file and add:

env

Copy

Edit

VITE_API_KEY=your_openweathermap_api_key

**📦 Installation & Setup**

bash

Copy

Edit

git clone https://github.com/ketananand76/weather_app.git

cd weather_app

npm install

npm run dev   # or npm start if CRA

For production build:

bash
Copy
Edit
npm run build

**🧩 Project Structure**

java
Copy
Edit

**weather_app**/
├── public/
├── src/
│   ├── components/
│   ├── App.jsx
│   ├── index.js
│   └── ...
├── .env
├── package.json
└── README.md

**🌐 Deployment**

This project is deployed on Render. For static deployment:

Set build command to: npm run build

Set publish directory to: build (CRA) or dist (Vite)

**🙌 Acknowledgments**

OpenWeatherMap API

React Documentation

**📄 License**

This project is licensed under the MIT License.
