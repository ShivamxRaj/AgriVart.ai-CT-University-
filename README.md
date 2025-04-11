# AgriVart.ai-CT-University-

# 🌿 Smart Irrigation System - AgriVart.AI

An intelligent and responsive Smart Irrigation System designed to revolutionize farming practices using AI. This project helps farmers optimize water usage based on real-time weather conditions, soil moisture data, and crop requirements, leading to higher productivity and sustainability.

---

## 🚀 Key Features

- 🌦️ **AI-Powered Irrigation Advice** – Smart recommendations using real-time weather and soil data.
- 🌱 **Soil Moisture Moni
- toring** – Integrate your soil sensor data for precision irrigation.
- ☔ **Rain Forecast Integration** – Avoid overwatering by checking the local rain forecast.
- 📱 **Responsive Design** – Fully mobile-friendly and desktop-ready for farmers in the field.
- 🌐 **Multilingual Voice Assistant** – Voice-based interaction in Hindi, Punjabi, and more (Planned).
- 📊 **Data Visualization** – Real-time stats and trends for better farm decisions.

---

## 🏗️ Project Structure

```
AgriVart.AI/
├── backend/
│   ├── app.py                 # Flask backend application
│   ├── requirements.txt       # Python dependencies
│   ├── .env                   # Environment variables (API keys)
│   └── .env.example           # Example environment variables
├── frontend/
│   ├── irrigation.html        # Main HTML file
│   ├── irrigation.css         # Custom styles
│   ├── irrigation.js          # App logic
│   ├── styles.css             # Global styles
│   └── script.js              # Global JavaScript
└── README.md
```

---

## 🧪 Setup & Installation

### Backend (Flask + Python)

1. Navigate to backend:
```bash
cd backend
```
2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Create a `.env` file:
```bash
OPENCAGE_API_KEY=your_opencage_api_key
OPENWEATHER_API_KEY=your_openweather_api_key
```
4. Run the server:
```bash
python app.py
```

### Frontend

1. Open `irrigation.html` in your browser.
2. OR serve it using Live Server (VSCode Extension) for dynamic functionality.

---

## 🔗 API Endpoints

### ✅ GET `/api/health`
Health check to verify backend is running.

### 💧 POST `/api/irrigation-advice`
Get dynamic irrigation recommendations.

**Request**
```json
{
  "location": "New York, NY",
  "moisture": 45,
  "rain": false
}
```
**Response**
```json
{
  "location": "New York, NY",
  "coordinates": {
    "latitude": 40.7128,
    "longitude": -74.0060
  },
  "weather": {
    "main": { "temp": 22.5, "humidity": 65 },
    "wind": { "speed": 3.2 },
    "weather": [{ "main": "Clear" }]
  },
  "soil_moisture": 45,
  "rain_forecast": false,
  "advice": "Current conditions are optimal. Maintain regular irrigation schedule."
}
```

---

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python, Flask
- **APIs**: OpenCage Geocoding API, OpenWeather API
- **Design**: CSS Variables, Transitions, Hover Effects
- **Voice** *(Planned)*: Google Speech-to-Text + Gemini/GPT API

---

## 💡 Future Enhancements

- 🤖 AI Crop Doctor – Upload images of crops and detect diseases instantly
- 🗣️ Voice-based Crop Advice in regional languages
- 📡 IoT sensor integration for real-time soil and weather tracking
- 📍 Geolocation-based irrigation alerts

---

## 🧠 Why It Matters

By using AI to monitor and suggest optimal irrigation schedules, farmers can:

- 💧 Save up to 40% water
- 📈 Increase crop yield
- 🕒 Save time with automation
- 🌾 Become climate-resilient

---

## 📜 License

MIT License - [![IMG-20250411-WA0005](https://github.com/user-attachments/assets/d3f0e895-b42d-442d-84d5-d0b9b5b685a3)
![IMG-20250411-WA0004](https://github.com/user-attachments/assets/e9829f08-ebd0-4bb2-8367-4b10d1a84a28)
![IMG-20250411-WA0011](https://github.com/user-attachments/assets/d399e50f-f139-42b5-a500-8d6f06d4989a)
![IMG-20250411-WA0010](https://github.com/user-attachments/assets/7bebd6f0-73ed-4722-a586-8f91073bea72)
![IMG-20250411-WA0009](https://github.com/user-attachments/assets/7e05fca1-c603-4b6a-b457-1d7a318b738f)![Screenshot 2025-04-11 110521](https://github.com/user-attachments/assets/7bdfbdab-92d1-457e-9e84-351670d58429)

![IMG-20250411-WA0008](https://github.com/user-attachments/assets/b1b3a9ad-b0f8-4778-876d-b0b0e67b8b85)
![IMG-20250411-WA0007](https://github.com/user-attachments/assets/d8c50bb1-a5bb-47bc-acd7-de373da2ac6e)
![IMG-20250411-WA0006](https://github.com/user-attachments/assets/6f4d9300-cf22-4cb0-9f90-dd7d3552fae7)
GitHub Repository](https://github.com/ShivamxRaj/AgriVart.ai-CT-University)
 image 
 

---

Made with ❤️ for CT University Hackathon 🚜

 image
