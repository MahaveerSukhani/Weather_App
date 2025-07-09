☀️ Simple Weather App (React Native)

A lightweight and responsive Weather App built with React Native, designed to display real-time weather data based on the user's location or city search. This app fetches weather data using a public API and presents it in a clean and user-friendly interface.

🚀 Features

📍 Get current weather based on user’s location (via GPS)

🔍 Search weather by city name

🌡️ Displays temperature, humidity, weather description, and more

📱 Clean and responsive UI compatible with both Android and iOS

🌙 Light and dark mode (optional)

🛠️ Tech Stack
React Native

OpenWeatherMap API (or similar weather API)

React Hooks for state and side-effects

* React-Native-Vector-Icons


📦 Installation
bash
Copy
Edit
git clone https://github.com/your-username/simple-weather-app.git
cd simple-weather-app
npm install
expo start

🔑 API Key Setup

* Go To https://openweathermap.org/api To Get An API KEY

* Replace This Line ( App.js - Line : 42 )

```javascript
   fetch('https://samples.openweathermap.org/data/2.5/weather?q=London,uk&appid=***********************')  
```

* With ( Replace The Stars With Your API KEY )

```javascript
   fetch('http://api.openweathermap.org/data/2.5/weather?q='+this.state.city+'&appid=***')  
```

## Sample Preview

<img src="https://user-images.githubusercontent.com/61349423/95949981-6401bb00-0e11-11eb-93ce-6bdc7960f11e.gif" width="250" height="500">



📄 License
This project is licensed under the MIT License.

# Weather App In React Native

### This is A Simple Weather App Made Using React Native

### Installing

> Clone This Repo

> Run npm install

> TODO

> Run The App

## TODO 



## Built With

* React Native
* React-Native-Vector-Icons
* OpeanWeatherMap

## Tutorial To Get API KEY

[OpneWeatherMap API KEY]

## Sample Preview

<img src="https://user-images.githubusercontent.com/61349423/95949981-6401bb00-0e11-11eb-93ce-6bdc7960f11e.gif" width="250" height="500">


## Authors

* **Belgin Android** - *All Works* - [Belgin Android](https://github.com/Belgin-Android)

## Issues ?

* Contact Me At [Instagram](https://www.instagram.com/letonations/)

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc

