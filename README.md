
# Weather App

A web app to get weather information based on the user's location or any city name. The app provides detailed weather data including current temperature, feels-like temperature, sunrise and sunset times, wind speed, cloudiness, and humidity.

## Features

- **Your Weather**: Automatically fetches and displays the weather report for the user's current location based on their coordinates.
- **Search by City**: Allows users to search for the weather of any city by entering the city name.
- **Weather Data**: Provides the following details:
  - Current temperature
  - Feels-like temperature
  - Sunrise time
  - Sunset time
  - Wind speed
  - Cloudiness
  - Humidity

## Demo

You can view a live demo of the application [here](https://tauqueer-weather-app.netlify.app/).

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/tauqueeralam42/weather-web-app.git
   ```
2. Navigate to the project directory:
   ```sh
   cd weather-web-app
   ```

3. Open `index.html` in your browser to run the app.

## Usage

1. Allow location access when prompted by the browser to get weather information for your current location.
2. Enter a city name in the search bar to get weather information for a specific city.

## API

This app uses the [OpenWeatherMap API](https://openweathermap.org/api) to fetch weather data. You need to sign up and get an API key.

1. Sign up at [OpenWeatherMap](https://home.openweathermap.org/users/sign_up).
2. Get your API key.
3. Replace the `YOUR_API_KEY` placeholder in your JavaScript code with your actual API key:
   ```javascript
   const API_KEY = 'YOUR_API_KEY';
   ```
4. Use the following endpoints to fetch weather data:
   - For current location based on coordinates:
     ```javascript
     `https://api.openweathermap.org/data/2.5/weather?lat=${lat}&lon=${lon}&appid=${API_KEY}&units=metric`
     ```
   - For a specific city:
     ```javascript
     `https://api.openweathermap.org/data/2.5/weather?q=${city}&appid=${API_KEY}&units=metric`
     ```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## Contact

For any questions or suggestions, feel free to reach out.

- GitHub: [tauqueeralam42](https://github.com/tauqueeralam42)
- Email:tauqueeralam42@gmail.com
