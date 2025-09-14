# 🌤 Weather App

A simple weather application built with **Django**. This project fetches weather data from **OpenWeather API** and displays dynamic background images using **Google Custom Search API**.  

## 🚀 Features
- Search weather by city name
- Display temperature, description, icon, and current date
- Dynamic background image based on the city (via Google Images)
- API keys stored securely in `.env` file

## 🛠 Technologies
- **Backend**: Django (Python)
- **Frontend**: HTML, CSS
- **APIs**:
  - OpenWeather API (for weather data)
  - Google Custom Search API (for city images)

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/username/weatherapp.git
   cd weatherapp


2. python -m venv venv
 source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows


3.  pip install -r requirements.txt

4. Create a .env file in the project root and add your keys:
API_KEY=your_google_api_key
APPID=your_openweather_api_key
SEARCH_ENGINE_ID=your_google_search_engine_id


5. python manage.py migrate
python manage.py runserver

6. 
```weatherapp/
│── weatherapp/        # Main Django project folder
│── templates/         # HTML files
│── static/            # CSS and static files
│── .env               # API keys (not committed to git)
│── requirements.txt   # Dependencies
│── manage.py


