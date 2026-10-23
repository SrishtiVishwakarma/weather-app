# 🌦️ Weather App

A simple and responsive Weather App that allows users to check the current weather of any city. It fetches real-time weather information using the OpenWeatherMap API and displays the temperature, humidity, wind speed, and weather conditions.

## ✨ Features

- 🔍 **Search by City:** Enter a city name to check its current weather.
- 🌡️ **Temperature:** Displays the temperature in Celsius.
- 💧 **Humidity:** Shows the current humidity percentage.
- 💨 **Wind Speed:** Displays the wind speed.
- 🌤️ **Weather Icons:** Changes the weather icon according to the current weather conditions.
- ⚠️ **Error Handling:** Displays an error message when an invalid city name is entered.

## 🛠️ Technologies Used

- **HTML5** – Structures the application.
- **CSS3** – Styles the weather card and its elements.
- **JavaScript** – Handles user interactions and API requests.
- **OpenWeatherMap API** – Fetches real-time weather data.
- **Fetch API** – Retrieves weather information from the API.

## 📁 Project Structure

```text
Weather-App/
│
├── index.html
├── weather.css
├── weather.js
└── images/
    ├── search.png
    ├── clouds.png
    ├── clear.png
    ├── rain.png
    ├── drizzle.png
    ├── mist.png
    ├── humidity.png
    └── wind.png
```

## 🚀 How to Run the Project

1. Clone this repository:

   ```bash
   git clone YOUR_REPOSITORY_URL
   ```

2. Open the project folder in your code editor.

3. Make sure all the required images are present inside the `images` folder.

4. Configure your OpenWeatherMap API key in `weather.js`.

5. Open `index.html` in your browser, or use the **Live Server** extension in VS Code.

6. Enter a city name in the search box and click the search button to view its weather information.

## 🔑 API Configuration

This project uses the OpenWeatherMap Current Weather Data API.

API endpoint:

```text
https://api.openweathermap.org/data/2.5/weather
```

The application requests