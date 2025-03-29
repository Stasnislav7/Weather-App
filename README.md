Weather App

Description

This application allows users to retrieve real-time weather information for a specified city using the OpenWeatherMap API. It displays the current temperature, weather conditions, humidity, wind speed, and a multi-day weather forecast.

Features

Enter a city name to fetch weather data

Display temperature, weather conditions, humidity, and wind speed

Show a multi-day weather forecast

Interactive UI with weather-related icons

Error message displayed if the city is not found

Displays a weather-related image on the website

Technologies Used

HTML, CSS, JavaScript – Frontend development

OpenWeatherMap API – Fetching weather data

Installation & Setup

Clone the repository:

git clone https://github.com/your-username/weather-app.git
cd weather-app

Create a apikey.js file and add your API key:

export const apiKey = 'YOUR_API_KEY_HERE';

Open index.html in a browser or use Live Server in VS Code.

Project Structure

weather-app/
│── assets/
│   ├── weather/ (weather icons)
│── css/
│   ├── styles.css
│── js/
│   ├── script.js
│   ├── apikey.js
│── index.html
│── README.md

Usage

Enter a city name in the search field

Click the "Search" button or press Enter

View the current weather and forecast

A relevant weather image is displayed on the website

Possible Issues

If the API key is invalid, the server requests will fail.

If the city name is incorrect, the app will display a "City Not Found" section.

Author
Stanislav

