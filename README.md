# Weather-app
This is a Weather Application built using Node.js, Express, hbs is used as the templating engine to obtain weather information.

Visit via https://ashish-weather-website.herokuapp.com/

Check out the Live Demo

## Getting Started

• Developed a web application where users can type in a street address, city name or zip code and get real-time weather data instantly displayed on their screen. 

• Integrated OpenWeatherMap API for fetching the location coordinates and weather data of the given location is determined using Map Box Api.

1. Firstly it calls Map Box Api for geo information of entering location.

2. Then it calls OpenWeatherMap Api with geo location information for weather information.

`Give Address -> Get Weather data address->Geocode(API)->OpenWeatherMapAPI->Output`

## Features
- Forcast using the OpenWeatherMap API
- Geocoding using the Mapbox API
- Inputs from Command Line Interface (CLI)

## Run locally

To Use: Clone the repository. CD to the repository folder and run the following command in your terminal:
git clone https://github.com/ashishshah1995/node-weather-website

Now you need to install the dependencies

npm install

Now you can run it locally

node src/app.js
Open http://localhost:3000 to view it in the browser.


REQUIREMENTS: You need to have NodeJS installed in your machine. You also have to create an API key at Open Weather Map and import it and pass in the key into the query URL.









