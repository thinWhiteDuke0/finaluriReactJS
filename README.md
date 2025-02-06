# Weather App (Vite + ReactJS)

## Project Overview
This is a simple and responsive weather application built with **Vite** and **ReactJS**. It uses the **OpenWeather API** to fetch current weather information based on the city name entered by the user. The app also provides visual weather icons and essential details like temperature, humidity, and wind speed.

## Features
- Search weather data by city name
- Display current weather conditions
- Visual icons for different weather conditions
- Responsive and user-friendly UI

## Tech Stack
- **Vite:** Fast development environment for modern web applications
- **ReactJS:** Frontend library for building interactive user interfaces
- **OpenWeather API:** Weather data source
- **CSS:** Styling and layout

## Installation

1. Clone the repository:
    ```bash
    git clone <repository-link>
    cd weather-app
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Create a `.env` file in the project root and add your OpenWeather API key:
    ```env
    VITE_WEATHER_API_KEY=your_api_key_here
    ```

4. Run the application:
    ```bash
    npm run dev
    ```

5. Open the app in your browser at [http://localhost:5173](http://localhost:5173).

## Usage
1. Enter a city name in the search bar and press the search icon.
2. View the current temperature, location, weather condition, humidity, and wind speed.
3. Default weather for "Egypt" is loaded on initial page load.

## Project Structure
```
src
├── assets         # Weather icons and images
├── components      # Reusable components
├── hooks           # Custom hooks (if any)
├── pages           # Application pages
├── styles          # CSS files
└── App.jsx         # Main app component
```

## Environment Variables
| Variable           | Description              |
|--------------------|---------------------------|
| `VITE_WEATHER_API_KEY` | Your OpenWeather API key |

## API Integration
- Base URL: `https://api.openweathermap.org/data/2.5/weather`
- Query Parameters:
  - `q`: City name
  - `units`: Measurement unit (`metric` for Celsius)
  - `appid`: API key

Example Request:
```
https://api.openweathermap.org/data/2.5/weather?q=London&units=metric&appid=YOUR_API_KEY
```

## Screenshots
1. **Initial View (Default City)**
2. **Search Functionality in Action**

## License
This project is licensed under the MIT License.

## Contributions
Feel free to fork the project, submit pull requests, or report issues. Happy coding!

## Acknowledgements
- [OpenWeather API](https://openweathermap.org/) for weather data
- Vite and ReactJS community for robust tooling

