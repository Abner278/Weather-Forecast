# Weather-Forecast

The "Weather Forecast " is a modern, responsive web application built with HTML, CSS (including Tailwind CSS), and JavaScript. It provides real-time weather information and forecasts for user-specified cities.

Features

Real-Time Weather Data-
Displays current city name, temperature (°C), rain chance, and animated weather icon (e.g., ☀️).  

 Hourly Forecast-
Shows a 6-hour forecast with time, temperature, and weather icons.
Includes navigation arrows (⬅️ ➡️) to scroll through hourly slots.

Air Conditions Overview-
Summarizes wind speed (km/h), rain probability (%), and snow probability (%).
Presented in hoverable cards with emojis (💨, 🌧️, ❄️).

7-Day Forecast-
Lists daily weather with day names, average temperatures, and icons.
Features a line chart (via Chart.js) for temperature trends.

City Search-
Search for any city worldwide via an input field (Enter key trigger).
Handles errors with user alerts for invalid entries.

Theme Toggle-
Switches between dark (default) and light modes.
Button updates with 🌙 (dark) or 🌞 (light) emojis.

Map Integration-
Map button (🗺️) links to Zoom Earth for satellite weather views.

Responsive Design-
Adapts to all screen sizes (desktop and mobile).
Optimized layout, font sizes, and spacing using Tailwind CSS.

Dynamic Data Fetching-
Fetches current weather and 5-day forecasts from OpenWeatherMap API.
Robust error handling for API requests.

Visual Enhancements-
Animated weather icon, hover effects, and smooth transitions.
Dark-themed UI with gradients and shadows.

Time Zone Support-
Displays local time for the selected city based on API timezone data.

Error Handling-
User-friendly alerts for failed API calls or invalid inputs.
Console logging for debugging.

Technologies Used-
HTML5: Structure and semantics.
 CSS3: Styling with Tailwind CSS and custom rules.
JavaScript: Interactivity and API integration.
Chart.js: 7-day forecast charting.
OpenWeatherMap API: Weather data source.

