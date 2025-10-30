# CityPulse-Real-Time-Urban-Insights-Dashboard
A live, data-driven web dashboard that displays real-time weather, air pollution, and traffic data for major Pakistani cities using multiple APIs. Built with HTML, CSS, and JavaScript — powered by OpenWeatherMap and Google Maps APIs.
# 🌆 CityPulse – Real-Time Urban Insights Dashboard

**CityPulse** is a modern, interactive, and data-driven web dashboard that provides live insights into **weather conditions**, **air quality (pollution)**, and **traffic status** for major cities across Pakistan.  
The app combines multiple APIs and visualizations to give users a clean, smart, and real-time overview of city life.

---

## 🚀 Features

- 🌦️ **Live Weather Updates**
  - Shows temperature, humidity, wind speed, and condition icon.
  - Auto-refreshes data every few minutes.
  - Uses [OpenWeatherMap API](https://openweathermap.org/api).

- 🌫️ **Air Pollution Monitoring**
  - Displays live AQI (Air Quality Index) data.
  - Color-coded interface (Good → Hazardous).
  - Uses OpenWeatherMap Air Pollution API.

- 🚗 **Traffic Visualization**
  - Live Google Maps with traffic layer.
  - City-based map overlay with congestion view.
  - Uses Google Maps Traffic API.

- 📊 **Interactive Charts**
  - Temperature and pollution trends displayed using Chart.js.
  - Smooth animated transitions between updates.

- 🧭 **Responsive Dashboard**
  - Clean glassmorphism UI.
  - Fully responsive for desktop and mobile screens.
  - Minimal, futuristic design aesthetic.

---

## 🧰 Tech Stack

| Category | Tools / Technologies |
|-----------|----------------------|
| **Frontend** | HTML5, CSS3, JavaScript (ES6) |
| **Libraries** | Chart.js, Font Awesome, GSAP (optional) |
| **APIs** | OpenWeatherMap API, Google Maps API |
| **Hosting** | [Vercel](https://vercel.com/) |
| **Version Control** | Git + GitHub |

---

## 🗂️ Folder Structure
citypulse-dashboard/
│
├── index.html # Main dashboard page
├── style.css # Styling and layout
├── script.js # JavaScript logic for APIs and UI
├── /assets # Icons, images, and design assets
└── /data # Optional JSON or static city list


---

## ⚙️ How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/citypulse-dashboard.git


cd citypulse-dashboard

Open index.html in your browser using Live Server (VS Code extension).

Create a free API key from:

OpenWeatherMap

Google Maps Platform

Replace YOUR_API_KEY in script.js with your actual key.
Supported Cities

✅ Karachi
✅ Lahore
✅ Islamabad
✅ Rawalpindi
✅ Peshawar
✅ Quetta

💡 Future Enhancements

AI-based weather and AQI prediction

Voice command (“Show Lahore’s weather”)

Dark / Light mode toggle

Data caching for offline mode
