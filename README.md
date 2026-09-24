# 🌦️ Weather

**Weather** is a premium, competition-grade web application that reimagines the standard weather app. Built entirely with vanilla HTML, CSS, and JavaScript in a single file, it features a modern Bento Box UI, dynamic real-photography backgrounds, and advanced meteorological data visualization.

## ✨ Key Features

### 🎨 Premium UI/UX
* **Bento Box Grid Layout:** Inspired by modern OS designs (iOS 18, Samsung One UI), organizing data into a clean, asymmetrical, and highly readable grid.
* **Dynamic Real Photography:** The hero card features high-resolution, curated Unsplash photographs that dynamically change based on current weather conditions (Clear, Rain, Snow, Fog, etc.).
* **Glassmorphism & Micro-interactions:** Smooth CSS transitions, frosted glass effects, and hover states make the app feel "alive" and tactile.

### 🌡️ Advanced Meteorological Data
* **Animated SVG Wind Gauge:** A custom-built, fully animated compass that visually displays wind speed (via a filling progress ring) and direction (via a smoothly rotating arrow).
* **Comprehensive Metrics:** Goes beyond basic temperature to include Apparent Temperature (Feels Like), UV Index, Dew Point, and Visibility.
* **Instant Unit Toggle:** Switch between Celsius and Fahrenheit instantly. *Technical flex: The app fetches data in Celsius and uses client-side math to convert to Fahrenheit, resulting in zero-latency toggling without extra API calls.*

### 🎭 4 Advanced Themes
Users can seamlessly switch between four distinct, fully-themed aesthetics:
1. **Aurora (Default):** Dark, frosted glass with vibrant blue accents.
2. **Solar:** Clean, bright, minimal light mode.
3. **Obsidian:** Pure black AMOLED theme (saves battery on OLED screens).
4. **Neon:** A unique cyberpunk aesthetic with vibrant pink/purple accents.

### 📍 Smart Location Services
* **Global Search:** Type any city in the world to instantly fetch its weather.
* **Native Geolocation:** One-click button to fetch the weather for your exact current location using the browser's GPS API.


## 🛠️ Tech Stack

* **Frontend:** Pure HTML5, CSS3 (Variables, Grid, Flexbox, Backdrop-filter), Vanilla JavaScript (ES6+). *No frameworks, no build steps, no `node_modules`.*
* **Weather API:** [Open-Meteo API](https://open-meteo.com/) (Free, open-source, no API key required, highly accurate).
* **Geocoding API:** [Open-Meteo Geocoding](https://geocoding-api.open-meteo.com/) (Translates city names to coordinates).
* **Imagery:** [Unsplash](https://unsplash.com/) (High-quality, free photography).
* **Typography:** [Inter](https://fonts.google.com/specimen/Inter) via Google Fonts.

## 📖 Usage Guide

1. **Search:** Type a city name (e.g., "Tokyo", "New York") in the top search bar and press `Enter` or click the magnifying glass.
2. **My Location:** Click the crosshair icon (📍) to allow browser location access and fetch weather for your current coordinates.
3. **Change Units:** Click the `°C` or `°F` pill toggle in the top right of the hero card.
4. **Change Theme:** Click the sun icon (☀️) in the top right to open the theme dropdown and select your preferred aesthetic.

---

## 🧠 Design Philosophy & Technical Highlights

* **Zero-Dependency Architecture:** By avoiding React, Vue, or heavy CSS frameworks, the app loads instantly and has a microscopic footprint. It proves that modern, premium UI can be achieved with native web standards.
* **Client-Side State Management:** Temperature conversion and theme switching are handled entirely in the browser's memory, ensuring the UI never blocks or waits on network requests during user interactions.
* **Meteorological Accuracy:** The app specifically requests the `wind_speed_10m` and `wind_direction_10m` parameters, adhering to the World Meteorological Organization (WMO) standard for surface wind measurements.

---

## 🗺️ Future Roadmap

* [ ] Add a 7-day daily forecast card.
* [ ] Implement CSS-only animated weather backgrounds (e.g., falling rain/snow particles using CSS keyframes).
* [ ] Add air quality index (AQI) and pollen tracking.
* [ ] PWA (Progressive Web App) support for offline caching and mobile home-screen installation.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE). 

*Weather data provided by Open-Meteo. Photography provided by Unsplash.*

## To use it open the link

https://github.com/alexos01/Weather
