# Weather App

## Description
A Weather App that provides weather details for a specific location.

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/Girijaray07/Weather-App.git
   cd weather-app
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Create a `.env` file and add your OpenWeatherMap API key:
   ```sh
   API_KEY=your_api_key_here
   ```

## Usage
1. Start the application:
   ```sh
   node App.js
   ```
2. Open your browser and visit:
   ```sh
   http://localhost:3000
   ```
3. Enter a location in the search bar and click 'Submit' to retrieve weather details.

## API Integration
The app fetches weather data using the OpenWeatherMap API:
```sh
https://api.openweathermap.org/data/2.5/weather?q={city name}&appid={API key}
```
Make sure to replace `{API key}` with your actual API key.

## Dependencies
- axios
- dotenv
- ejs
- express

## Author
Girija Ray