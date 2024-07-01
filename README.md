# Weather App

This project is a weather application built with React that fetches weather data from the OpenWeatherMap API. It allows users to search for the current weather in any city and displays detailed weather information.

## Features

- Search for current weather by city name
- Display temperature, humidity, wind speed, and location details
- Show weather icons based on the current weather conditions
- Handle loading states and errors gracefully

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/aakilshihafv/WeatherApp
    cd WeatherApp
    ```

2. Install dependencies:
    ```sh
    npm install
    ```

3. Start the development server:
    ```sh
    npm start
    ```

## Usage

- Enter the name of the city you want to search for in the input field.
- Press "Enter" or click the search icon to fetch weather details.
- The weather details will be displayed, including temperature, humidity, wind speed, and location.

## File Structure

- `App.js`: Main application component that handles user input, fetches weather data, and displays the results.
- `WeatherDetails.js`: Component that displays the detailed weather information.
- `assets`: Contains weather icons and other images.
- `App.css`: Styles for the application.

## API Key

The application uses the OpenWeatherMap API to fetch weather data. An API key is required and has been included in the code for demonstration purposes. To use your own API key, replace the `api_key` variable in `App.js` with your key.

## Screenshot

![Weather Design](https://github.com/aakilshihafv/WeatherApp/blob/main/image/Weather%20Design.png)


## Contributing

Feel free to fork this repository, make enhancements, and submit pull requests. Contributions are always welcome!

## License

This project is licensed under the MIT License. See the LICENSE file for details.
# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
