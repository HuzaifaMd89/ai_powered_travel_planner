# 🌍 AI-Powered Personalized Travel Planner

## 📌 Project Overview
This is a **backend-only AI-powered travel assistant** that generates **custom travel itineraries** based on user preferences like:
- **Budget** (low, medium, high)
- **Interests** (Food, Adventure, Nature, Culture, etc.)
- **Destination** and **Travel Dates**

It integrates **real-time travel data** for:
✅ **Attractions & Sightseeing**  
✅ **Weather Forecast**  
✅ **Flights & Hotels**  

---

## ⚙️ Tech Stack
- **Backend:** Flask (Python)
- **LLM:** OpenAI GPT-4 (or Mistral-7B)
- **APIs:** OpenWeather, Skyscanner, TripAdvisor, Yelp, or Here Places API
- **Database:** PostgreSQL / Firebase (optional)
- **Deployment:** Render / AWS / Vercel

---

## 🚀 Setup & Installation

### 1️⃣ Install Dependencies
```bash
pip install flask openai requests
```

### 2️⃣ Set API Keys (Replace with Your Own Keys)
Edit `app.py` and replace the placeholder API keys:
```python
OPENAI_API_KEY = "your_openai_api_key"
TRIPADVISOR_API_KEY = "your_tripadvisor_api_key"
HERE_API_KEY = "your_here_api_key"
YELP_API_KEY = "your_yelp_api_key"
WEATHER_API_KEY = "your_weather_api_key"
SKYSCANNER_API_KEY = "your_skyscanner_api_key"
```

---

## 📡 Running the API Server
Start the Flask server:
```bash
python app.py
```

---

## 📜 License
MIT License - Free to use & modify.

🚀 **Happy Traveling!** 🌍

