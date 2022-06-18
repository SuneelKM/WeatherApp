# Project 2 - Weather App

## Project Description
A simple Android application that allows users to recieve live weather data.

## Technologies Used
* Kotlin
* Android Studio - Chipmunk
* MVVM Design
* RxKotlin
* Room DB 
* Retrofit2 
* Mockito
* JUnit 
* Google Places SDK 
* Firebase Crashlytics
* Timber Tree logger

## APIs Used
* OpenWeather One Call API 3.0 to get live weather data
* OpenCage Geocoding API for reverse geocoding
* Google cloud API key for Google Place Autocomplete and Google Geocoding

## Screenshots

<img src = "https://github.com/SuneelKM/AndroidWeatherApp/blob/master/Screenshot/image.png" width=1200 height=450>

## Features
* Detect your current location based on your IP address
* Has bottom navigation with three pages:
  - Today page: - Contains current weather details for users current location and searched location
  - Weekly page: - Contains weather details for the next 8 days
  - Location page: - Can insert or deleted favourite locations
* Search bar uses Google's Places Autocomplete, so user can start typing a location and autocomplete will provide a list of place predictions
* Can convert the temperature units from Celsius to Fahrenheit
* Dynamic weather icons that correspond to the weather details


## To run the app
* Get the required API keys mentioned aboved.
* Clone the Repo
* Open the Repo in Android Studio. Gradle sync will fail.
* In the local.properties file, under sdk.dir line enter your API keys as show below:
  - googleApi = "Your Google Cloud API key"
  - weatherApiKey = "Your OpenWeather One Call API 3.0 Key"
  - openCageDataKey = "Your OpenCageDataKey"
* Rebuild your Gradle
* Enjoy!!
* Optional: To link the app to google crashlytics, you can signup for google crahlytics and paste your google-services.json in the app folder.
