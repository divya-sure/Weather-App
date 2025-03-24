Weather Application

Live URL :

to see the live result just click here - https://divya-sure-weather-app.netlify.app/

🌦 Overview

This is a simple Weather Application built using HTML, CSS, and JavaScript. It fetches real-time weather data using an external API and displays it in a user-friendly interface. The application is fully responsive, making it accessible across different screen sizes.

🚀 Features

- Current Weather Data: Fetches real-time weather information.
- 7-Day Forecast: Displays upcoming weather conditions.
- Search Functionality: Users can search for weather updates of any city.
- Responsive Design: Works on all devices (mobile, tablet, and desktop).
- API Integration: Uses WeatherAPI to retrieve weather data.

🛠️ Technologies Used

HTML: Structure of the application.
CSS: Styling and responsive design.
JavaScript: Fetching and displaying data dynamically.
Weather API: To retrieve weather information.

📌 API Configuration

Sign up on WeatherAPI to get an API key.

Replace YOUR_API_KEY in script.js:

const apiKey = "YOUR_API_KEY";
const apiUrl = `https://api.weatherapi.com/v1/forecast.json?key=${apiKey}&q=city&days=7`;

📱 Responsive Design

Uses CSS Media Queries to ensure the UI adapts to different screen sizes.
Mobile-first approach for better accessibility.

⚠️ Troubleshooting

If the app doesn’t display data, check:
API key validity.
Browser console for CORS errors.
Network connection.

💡 Future Enhancements

Dark mode support.
More detailed weather insights (humidity, wind speed, UV index).
Option to save favorite locations.

📜 License

This project is open-source and free to use under the MIT License.

Developed by Sure Venkata Naga Divya 🚀

