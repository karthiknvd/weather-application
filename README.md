# 🌦️ Weather Application

A simple, clean, and responsive **Weather Application** that fetches real-time weather data using the **OpenWeather API**.
This was built as a **college project**, using **Spring Boot (Backend)** and **HTML/CSS/JS (Frontend)**.

👉 **Live Demo (Frontend Only):**
🔗 [https://karthiknvd.github.io/weather-application/](https://karthiknvd.github.io/weather-application/)

> ⚠️ **Note:**
> GitHub Pages only hosts static files, so the **Spring Boot backend will NOT work** on the live site.
> Only the frontend UI is visible on GitHub Pages.
> To use the backend, run the project locally.

---

## 🚀 Features

* 🌤️ Real-time weather updates
* 📍 Search weather by city name
* 📊 Temperature, humidity, and wind details
* 🌈 Clean and user-friendly UI
* ⚡ Fast API response using OpenWeather
* 🖥️ Frontend + Backend (Spring Boot)

---

## 🛠️ Tech Stack

### **Frontend**

* HTML5
* CSS3
* JavaScript

### **Backend**

* Spring Boot
* Java
* REST Controller
* API Integration with OpenWeather

### **External API**

* 🌐 **OpenWeatherMap API**

---

## 📡 How It Works

1. User enters a city name
2. Frontend sends a request to the Spring Boot backend
3. Backend calls **OpenWeather API** with the API key
4. JSON weather data returns
5. Frontend displays the weather details

---

## 🔧 Running Locally (Backend + Frontend Working)

### 1️⃣ Clone the repo

```
git clone https://github.com/karthiknvd/weather-application.git
```

### 2️⃣ Open backend project in IntelliJ or Eclipse

Run the Spring Boot application:

```
mvn spring-boot:run
```

### 3️⃣ API Key Setup

Inside `application.properties` (or wherever you used it):

```
openweather.api.key=YOUR_API_KEY
```

### 4️⃣ Open `index.html` in browser

Your weather app will now work fully with backend support.

---

## 🌐 Live Version (Frontend Only)

GitHub Pages link:
**[https://karthiknvd.github.io/weather-application/](https://karthiknvd.github.io/weather-application/)**

> ⚠️ As mentioned, **backend features won’t work** here because GitHub Pages does not support Java/Spring Boot servers.

---

## 🧩 Folder Structure

```
weather-application/
│── backend/         # Spring Boot project
│── frontend/        # HTML, CSS, JS files
│── README.md
│── ...
```

---

## 📜 License

This project is for educational purposes and free to use.
