
# 🌤️ Weather App

This is a simple and stylish weather application that fetches and displays current weather information for any city in India using the OpenWeatherMap API.

## 🚀 Features

- Search for weather by city name
- Real-time weather updates with temperature and description
- Displays weather icon
- User-friendly interface with responsive design

## 🛠️ Technologies Used

- **HTML5** – For the basic structure
- **CSS3** – For beautiful, responsive styling
- **JavaScript (ES6)** – For dynamic content and API interaction
- **OpenWeatherMap API** – For geocoding and current weather data

## 📂 Project Structure

```

weather-app/
├── index.html       # Main HTML structure
├── styles.css       # App styling and layout
├── script.js        # Core JavaScript logic (fetch & display)
└── README.md        # Project documentation

````

## 🧪 How It Works

1. User enters a city name and clicks **Search**.
2. The app uses the **OpenWeatherMap Geocoding API** to get the latitude and longitude.
3. It then calls the **Current Weather API** to fetch weather data.
4. Weather info is displayed dynamically in a styled card.

## ⚙️ Setup Instructions

1. Clone or download the repository.
2. Open `index.html` in your browser.
3. Replace the API key in `script.js` with your own from [OpenWeatherMap](https://openweathermap.org/api).

```js
const apiKey = "YOUR_API_KEY_HERE";
````

## 📝 Notes

* Works only for Indian cities due to hardcoded country code (`91`).
* Temperature is shown in Celsius (converted from Kelvin).
* Minimal error handling is included for empty or invalid input.

## 📄 License

This project is licensed under the MIT License.

