# 🚀 Mars Photos App

A modern Android app built with **Jetpack Compose** that displays photos taken by NASA’s Mars rovers. Developed as part of **Unit 5: Get data from the internet** in the [Android Basics with Compose](https://developer.android.com/courses/android-basics-compose/unit-5) course by Google.

This app uses Retrofit to fetch data from a RESTful web service, parses it using Kotlinx Serialization, and displays it in a clean, responsive UI built with Compose.

---

## 🌠 Overview

- 📸 Displays a gallery of photos sent back by NASA's Mars rovers.
- 🔗 Fetches data using a **REST API** (represented here by a fake backend).
- 🔌 Uses **Retrofit** for networking and **Kotlin coroutines** for background operations.
- 🧱 Structured using **MVVM architecture** with a clean separation of concerns.
- 🧪 Includes unit tests with coroutine test utilities.

---

## 📚 Based on: Android Basics with Compose - Unit 5

**Topics Covered:**
- RESTful API basics
- JSON data parsing with Kotlinx Serialization
- Using Retrofit in Compose apps
- MVVM + Repository pattern
- Error handling and testability

---

## 🔗 API Reference

The app uses a simulated Mars API, modeled after the real [NASA Mars Rover Photos API](https://api.nasa.gov/).

### Example Endpoint:
GET /photos

### Sample Response:
```json
[
  {
    "id": "1",
    "img_src": "https://mars.nasa.gov/image.jpg"
  },
  {
    "id": "2",
    "img_src": "https://mars.nasa.gov/image2.jpg"
  }
]
```
In production, this would correspond to:
https://api.nasa.gov/mars-photos/api/v1/rovers/curiosity/photos?sol=1000&api_key=DEMO_KEY

---

## 📷 App Screenshot
![WhatsApp Image 2025-06-18 at 16 26 04_2afc4f8f](https://github.com/user-attachments/assets/5bdec684-f8fd-4d12-b488-6cd3bb57850c)
