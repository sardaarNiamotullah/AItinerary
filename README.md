## The project is currently LIVE at [travel-aitinerary.vercel.app](https://travel-aitinerary.vercel.app/)!

## [CLICK HERE](https://youtu.be/QWFeunya20k) to see the video demo of the project


### Go through the README.md of [backend](https://github.com/sardaarNiamotullah/travel_itinerary-backend) to set the backend up in your local machine

**Don not forget to add this line to your seetings.py**
```bash
ALLOWED_HOSTS = [
    "travel-itinerary-backend-6j4k.onrender.com",
    "localhost",  # This will cover both localhost:8000 and localhost:5173
    "127.0.0.1",  # Also good to add the loopback IP for local development
]
```


### Go through the README.md of [frontend](https://github.com/sardaarNiamotullah/travel_itinerary-frontend) to set the backend up in your local machine

**Don't forget to set the baseURL to localhost in your local machine**
   ```bash
   // src/lib/axios.ts
   baseURL: "http://localhost:8000/api",
   ```

### To see the whole project github repo [CLICK HERE](https://github.com/sardaarNiamotullah/AItinerary)


### Project Description
The AI Travel Itinerary Builder is a full-stack web application that generates weather-aware travel itineraries for any destination. By integrating real-time weather data and AI-powered recommendations via the Groq API, the app provides personalized day-wise travel plans tailored to current weather conditions.

### Key Features:
- Weather-Aware Itineraries: Suggests indoor activities on rainy days or outdoor adventures when the weather is clear.
- AI-Powered Recommendations: Uses the Groq API to generate culturally relevant and practical travel plans.
- Simple Interface: Clean React.js frontend with intuitive input fields for destination and travel date.
- RESTful Backend: Django-powered API handles weather data fetching and AI integration.

### Technologies Used

Backend:
- Python 3.9+
- Django 3+ with Django REST Framework
- Weather API: [Specify your chosen API, e.g., OpenWeatherMap/WeatherAPI]
- Groq API for AI itinerary generation

Frontend:
- React.js (Create React App or Vite)
- Axios for API communication
