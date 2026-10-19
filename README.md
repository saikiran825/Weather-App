# Weather App 🌦️

A simple and responsive weather application built with **HTML, CSS, and JavaScript**. Search for a city to view its current temperature, humidity, wind speed, and weather conditions.

## Features

- Search for weather by city name
- Display current temperature in Celsius
- Show humidity and wind speed
- Change the weather icon based on conditions such as clear skies, clouds, rain, drizzle, and mist
- Display an error message when the city name is invalid
- Simple interface with weather-dependent background styling

## Built With

- **HTML5** — page structure
- **CSS3** — layout and styling
- **JavaScript** — application logic and API requests
- **OpenWeatherMap API** — weather data

## Project Structure

```text
Weather-App/
├── index.html
├── style.css
├── app.js
└── images/
    ├── search.png
    ├── clouds.png
    ├── clear.png
    ├── rain.png
    ├── Drizzle.png
    ├── mist.png
    ├── humidity.png
    └── wind.png
```

Make sure the CSS and JavaScript filenames in `index.html` match your actual filenames. The image files should be placed in the `images` folder, with filenames matching those used in `app.js` and `index.html`.

## How to Run

1. Download or clone this repository.
2. Make sure all project files and the `images` folder are in the correct locations.
3. Configure your OpenWeatherMap API key in `app.js`.
4. Open `index.html` in a browser, or run the project using a local development server.
5. Enter a city name and click the search button.

## API Setup

This project uses the OpenWeatherMap Current Weather API.

1. Create an account at [OpenWeatherMap](https://openweathermap.org/).
2. Generate an API key.
3. Replace the API key in `app.js` with your own key.
4. Keep your API key private. If you publish this project on GitHub, avoid committing a real API key; use a safer backend or another suitable approach to protect it.

## What I Learned

- Connecting a frontend project to a weather API using `fetch()`
- Using `async/await` for asynchronous JavaScript
- Reading JSON data from an API response
- Updating HTML elements through the DOM
- Handling invalid city searches
- Changing icons and styles dynamically based on weather conditions

## Future Improvements

- Add a search action when the user presses **Enter**
- Improve error handling for network and API-key errors
- Add a loading indicator
- Improve the mobile layout and accessibility
- Move API requests behind a backend to protect the API key

## Author

**Sai kiran**
saikiran8025@gmail.com

Feel free to explore the project and suggest improvements.
