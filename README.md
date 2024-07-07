# WeatherApp

WeatherApp is a Java-based application that provides real-time weather information for a given location using the Open-Meteo API.

## Features
- Fetches weather data based on the user's location input.
- Provides real-time temperature, weather conditions, humidity, and wind speed.
- Uses the Open-Meteo API for accurate weather information.

## How It Works
1. The user inputs the name of a location.
2. The application fetches the geographical coordinates (latitude and longitude) of the location using the Open-Meteo Geocoding API.
3. Using these coordinates, the application retrieves weather data from the Open-Meteo Weather API.
4. The application parses the JSON response and extracts relevant weather information.
5. The weather data is displayed to the user.

## Requirements
- Java 8 or higher
- JSON.simple library

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
