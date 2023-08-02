# Weather App using OpenWeather API

The Weather App is a web application that fetches real-time weather data from the OpenWeather API and presents it to the user in a user-friendly UI.
Features


    - Display the current weather conditions including temperature, humidity, wind speed, and weather description.
    - Allow users to search for weather data of different cities.
    - Automatically detect and display the weather data of the user's current location (optional).
    - Responsive design to ensure a seamless experience across devices.

### Live: https://check-today-weather.netlify.app/

## Weather App Screenshot 📷
![screenshot-check-today-weather netlify app-2023 08 02-16_40_09](https://github.com/PrinceSinghhub/Check-Weather-App/assets/71000042/6d298b16-3373-4b01-b875-56c470ab4cfd)
![dgdd](https://github.com/PrinceSinghhub/Check-Weather-App/assets/71000042/0a43d9d1-8ad5-404b-916e-cf2eb078f582)

You can see a live demo of the Weather App here.
## Video 🎥
https://github.com/PrinceSinghhub/Check-Weather-App/assets/71000042/fdab936d-a00d-45cd-9c4f-ebbe3768c828

# Technologies Used

    - HTML, CSS, and JavaScript for the frontend user interface.
    - OpenWeather API to fetch real-time weather data.
    - (Optional) Geolocation API to detect the user's current location.

## How to Use

    - Clone the repository:

## bash

git clone https://github.com/yourusername/weather-app.git

    - Navigate to the project directory:

bash

## cd weather-app

    - Open index.html in your preferred web browser.

    - Enter the name of the city you want to check the weather for in the search box.

    - Press the "Search" button to fetch and display the weather data for the specified city.

    - (Optional) Allow the app to use your device's location to automatically fetch the weather data for your current location.

## API Key Setup

To use the OpenWeather API, you need to sign up on their website to obtain an API key. Once you have the API key, create a file named config.js in the project directory and store your API key in it as follows:

#E javascript

// config.js
const API_KEY = 'YOUR_API_KEY_HERE';

Replace 'YOUR_API_KEY_HERE' with your actual API key.

### Note: Do not share your API key publicly or commit it to version control. Use environment variables or other secure methods to manage the API key in production.
