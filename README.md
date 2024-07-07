# Weather App

This Weather App is a frontend application built using JavaScript to display current weather information for different locations.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [API Integration](#api-integration)
- [Code Explanation](#code-explanation)

## Features

- **Current Weather**: Displays current temperature, weather conditions, humidity, wind speed, etc.
- **Geolocation**: Allows users to grant access to their location for personalized weather information.
- **Search**: Search for weather information by city name.
- **Error Handling**: Displays appropriate error messages if weather data cannot be fetched.
- **Responsive Design**: Ensures usability across desktop and mobile devices.

## Technologies Used

- **JavaScript**: Frontend logic and API integration.
- **HTML**: Structure and layout.
- **CSS**: Styling and design.

## Getting Started

To run this application locally, follow these steps:

1. Clone the repository: `git clone <repository-url>`
2. Open `index.html` in your preferred browser.

Alternatively, you can use a live server extension in your code editor to run the application.

## Usage

- **User Weather**: Automatically fetches weather based on user's geolocation (if granted).
- **Search Weather**: Enter a city name in the search input to fetch weather information for that city.

## Screenshots

![Weather App Screenshot](https://github.com/mohd-momin/WeatherApp/blob/main/assets/WeatherAppScreenshot.png)

## API Integration

The Weather App uses the OpenWeatherMap API to fetch current weather data. You need to sign up for an API key and replace `API_KEY` in the code with your own API key.

## Code Explanation

The provided JavaScript code handles user interactions, API calls, and UI updates for both user weather and search weather functionalities. Here's a breakdown:

- **Tab Handling**: Switches between user weather and search weather tabs.
- **User Weather Handling**: Handles geolocation access, fetches and displays weather data based on user's location.
- **Search Weather Handling**: Fetches and displays weather data based on user input (city name).

Make sure to replace `API_KEY` with your actual OpenWeatherMap API key before running the application.
