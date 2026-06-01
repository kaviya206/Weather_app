# Weather_app

# 🌤️ Kaviya's Weather

A modern weather application that delivers live weather information through an intuitive and visually engaging interface. The application leverages real-time weather and geolocation services to provide accurate weather conditions for the user's current location or any searched city worldwide.

## Overview

Serene Weather is a lightweight client-side web application designed to provide a seamless weather-checking experience. The application combines real-time weather forecasting, location services, and geocoding APIs to present accurate weather information with an elegant user interface.

## Key Features

* Real-time weather information
* Automatic location detection using browser geolocation
* Global city search with autocomplete suggestions
* Reverse geocoding for human-readable location names
* Responsive design for desktop and mobile devices
* Dynamic weather visualization using condition-based icons and emojis
* Fast, lightweight, and fully client-side architecture
* No backend server required

## Preview

<img width="1920" height="866" alt="output1" src="https://github.com/user-attachments/assets/3fb638ed-3a9a-4096-b0e4-882a69ad0753" />

<img width="1920" height="864" alt="output2" src="https://github.com/user-attachments/assets/b2444938-b29d-4fc6-b4e1-4695a35741dd" />



## Technologies Used

### Frontend

* HTML5
* CSS3
* JavaScript (ES6)
* Tailwind CSS
* Lucide Icons

### APIs and Services

#### Open-Meteo Weather API

The application uses the Open-Meteo Weather API to retrieve live weather information, including:

* Current temperature
* Weather condition codes
* Day and night indicators
* Forecast-based meteorological data

Example endpoint:

```text
https://api.open-meteo.com/v1/forecast
```

Why it was chosen:

* Free to use
* No API key required
* High-quality global weather coverage
* Fast response times

#### Open-Meteo Geocoding API

The geocoding service converts user-entered city names into geographical coordinates (latitude and longitude).

Example endpoint:

```text
https://geocoding-api.open-meteo.com/v1/search
```

Functionality:

* City search
* Location suggestions
* Latitude and longitude retrieval
* Global location support

#### BigDataCloud Reverse Geocoding API

Used to convert GPS coordinates into readable location names.

Example endpoint:

```text
https://api.bigdatacloud.net/data/reverse-geocode-client
```

Functionality:

* Reverse geocoding
* City name identification
* Region and locality detection

#### Browser Geolocation API

The browser's built-in Geolocation API is used to determine the user's current position.

Example:

```javascript
navigator.geolocation.getCurrentPosition()
```

Functionality:

* Current location access
* Latitude and longitude retrieval
* Personalized weather experience

## System Workflow

1. User opens the application.
2. Browser requests location permission.
3. Geolocation API retrieves coordinates.
4. Open-Meteo Weather API fetches weather data.
5. BigDataCloud API converts coordinates into a location name.
6. Weather information is displayed in the user interface.
7. Users can search for other cities using the Open-Meteo Geocoding API.

## Project Structure

```text
SereneWeather/
│
├── index.html
└── README.md
```

## Live Demo

Deployed Application:

https://weather-appkav.vercel.app/

## Future Enhancements

* 7-Day Weather Forecast
* Hourly Weather Forecast
* Interactive Weather Charts
* Progressive Web App (PWA) Support
* Dark Mode
* Weather Alerts and Notifications
* Multi-language Support
* Weather History Tracking

## Author

**Kaviya R**

Electronics and Communication Engineering Student with interests in Web Development, Artificial Intelligence, Cloud Technologies, and Emerging Digital Solutions.
