# 🌤️ Simple Weather App

A lightweight weather application built with **HTML, CSS, and JavaScript** that fetches real-time weather data from the **OpenWeather API**. Enter a city name to see the current temperature, humidity, wind speed, and weather icon.

![Weather App Preview](https://github.com/C00L1N/Basic-Weather-App/blob/main/Preview%20Weather%20App.png?raw=true)

## ✨ Features
- 🔎 Search weather by city name
- 🌡️ Shows temperature, humidity, and wind speed
- 🖼️ Dynamic weather icons based on conditions
- ❌ Error handling for invalid city names

## 🛠️ Built With
- **HTML5** – structure
- **CSS3** – styling
- **JavaScript (Fetch API)** – dynamic data fetching
- **OpenWeather API** – real-time weather data

## 🚀 How to Run Locally

1. Clone this repository
   ```
   git clone https://github.com/yourusername/weather-app.git
   ```
   ```
   cd weather-app
   ```
2. Open `index.html` in your browser
3. Replace the `apiKey` in `script.js` with your OpenWeather API key  
   ```
   const apiKey = "YOUR_API_KEY_HERE";
   ```

## 🧠 How It Works
- Takes user input for a city name
- Sends a **GET request** to OpenWeather API
- Parses the JSON response
- Updates the DOM dynamically with:
  - City name
  - Temperature
  - Humidity
  - Wind speed
  - Weather icon

## 📡 API Reference
- **Base URL:** `https://api.openweathermap.org/data/2.5/weather`
- **Parameters:**
  - `q` → City name
  - `appid` → Your API key
  - `units=metric` → Celsius temperature

## 🙏 Thanks To
Special thanks to GreatStack from Youtube for the original tutorial and inspiration for this project!
Here is the link if you want to see the tutorial for yourself  
[![Watch the tutorial on YouTube](https://img.youtube.com/vi/MIYQR-Ybrn4/0.jpg)](https://youtu.be/MIYQR-Ybrn4?si=9SjuBucw0aZYb5eJ)





