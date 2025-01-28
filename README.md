# SRM_GeoMaps


This project is a simple Flask-based GPS chatbot application that integrates the Google Maps API to provide directions, recommendations, and other location-based functionalities. The chatbot leverages text input, voice commands, and fuzzy matching to enhance user experience.

## Features

- **Chatbot Directions**: Users can ask for directions to predefined destinations, and the chatbot responds with step-by-step instructions.
- **Nearby Recommendations**: Based on the user's current location, the app provides recommendations for nearby locations.
- **Voice Input**: Users can give commands using voice input, which is converted to text for processing.
- **Google Maps Integration**: Embeds maps and generates routes using the Google Maps Directions API.
- **Predefined Destinations**: The app has a list of predefined destinations that can be expanded as needed.

## Tech Stack

- **Backend**: Flask (Python)
- **API**: Google Maps API
- **Voice Processing**: SpeechRecognition and gTTS (Google Text-to-Speech)
- **Geolocation**: Geopy for distance calculations
- **Text Matching**: FuzzyWuzzy for improved destination matching
- **Frontend**: HTML templates rendered with Flask

