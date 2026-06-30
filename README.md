# Weather Info WebAPP

A real-time, retro CRT terminal-style Weather Dashboard built with vanilla HTML, CSS, and asynchronous JavaScript.

## Features
- **Asynchronous Data Fetching**: Utilizes the modern `Fetch API` with `async/await` to retrieve real-time weather data from the public Open-Meteo REST API.
- **Robust Error Handling**: Implements comprehensive error handling to gracefully manage failed network requests, invalid city names, and API connection issues.
- **Dynamic JSON Parsing**: Parses and dynamically renders complex nested JSON response objects (coordinates, temperature, humidity, wind speed, and weather codes).
- **Interactive Search Functionality**: Allows users to retrieve live weather conditions for any city globally via terminal-like text inputs.
- **Retro CRT Aesthetic**: Custom styled terminal screen featuring scanline overlays, terminal boot sequence animations, and dynamic ASCII weather art.

## Live Link
https://weather-khaki-beta.vercel.app/

## Terminal Commands
- `weather <city>` — Fetch and display live weather metrics (temperature, feels like, humidity, wind speed) for a specific city.
- `clear` — Clear the terminal screen.
- `help` — Show the list of available commands.
- *(Note: You can also just type a city name directly and press Enter to search).*

## Technologies Used
- **HTML5**: Semantic structure for the terminal dashboard.
- **CSS3**: Custom retro theme styling, CRT animations, and responsive layout.
- **JavaScript (ES6+)**: Asynchronous fetching, DOM manipulation, and event handling.
