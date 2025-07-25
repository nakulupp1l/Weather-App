# 🌦 Weather App

A sleek and responsive weather application that provides real-time weather information based on your current location or by searching for any city in the world. Built using HTML, CSS, and JavaScript with OpenWeatherMap API integration.

## 🚀 Features

* 🔍 **Search by City** – Get current weather conditions for any city.
* 📍 **Your Weather** – Uses your geolocation to fetch and display weather data.
* 📦 **Session Storage** – Saves coordinates to session storage to avoid repeated permission requests.
* 🎨 **Responsive UI** – Designed for a smooth user experience with a clean and modern interface.
* 🌀 **Live Weather Details**:

  * Temperature (°C)
  * Wind speed (m/s)
  * Humidity (%)
  * Cloudiness (%)
  * Weather description with icon
  * Country flag based on selected location

## 🛠 Tech Stack

* **Frontend**: HTML, CSS, JavaScript
* **API**: [OpenWeatherMap API](https://openweathermap.org/api)
* **Fonts**: Merriweather Sans (Google Fonts)
* **Icons/Images**: Local asset images (e.g., loading spinner, icons for wind/humidity/clouds)

## 🧱 Project Structure

```
├── index.html          # Main HTML file
├── index.js            # JavaScript logic for API calls & UI updates
├── style.css           # All styling (responsive design, layout, themes)
├── assets/             # Icons, loading gif, background images
```

## 🗝 API Key Setup

1. Sign up at [OpenWeatherMap](https://home.openweathermap.org/users/sign_up) and get your API key.
2. Replace the placeholder API key in `index.js`:

   ```js
   const API_KEY = "adde09590fc1c3ec4536476d5eb66d37";
   ```

## 📦 How to Run Locally

1. Clone the repository or download the files.
2. Ensure all files (`index.html`, `style.css`, `index.js`, and `assets/`) are in the same directory structure.
3. Open `index.html` in your browser.

## 📌 Notes

* Make sure location permissions are granted in the browser to use the "Your Weather" tab.
* Handles city not found errors gracefully with a dedicated UI.
* Fully responsive for mobile and desktop devices.

## ✨ Future Improvements

* Add 5-day forecast support.
* Theme toggling (light/dark mode).
* Store and display weather history.
* PWA support for offline access.

## 📄 License

This project is open-source and free to use. Attribution is appreciated.

---