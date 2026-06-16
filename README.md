# The Closet Fashion Assistant

## 📌 About

**The Closet Fashion Assistant** is an AI-powered smart outfit recommendation system that solves the daily challenge of deciding what to wear. It acts as a Utility-Based Agent that considers weather conditions, occasion suitability, personal style preferences, and outfit repetition avoidance.

---

## ✨ Features

- Real-time weather integration (OpenWeatherMap API)
- KNN Machine Learning for outfit acceptance prediction
- 6 occasion types with filtering
- Weighted utility scoring (Weather 35%, Occasion 30%, Style 20%, Diversity 15%)
- A* Search Algorithm for optimal outfit selection
- Wear history tracking (JSON storage)
- Modern GUI with Tkinter

---

## 🛠️ Tech Stack

| Component | Technology |
|-----------|------------|
| Language | Python 3.14 |
| ML Library | scikit-learn 1.8.0 (KNN) |
| Data Processing | pandas 3.0.2, numpy 2.4.2 |
| GUI Framework | Tkinter |
| Weather API | OpenWeatherMap |
| Data Storage | JSON, CSV |

---

## 🤖 Agent Design

**Agent Type**: Utility-Based Agent

**PEAS Analysis**:
- **Performance**: User acceptance rate, weather/occasion accuracy
- **Environment**: Desktop application, digital wardrobe, real-time weather
- **Actuators**: Display recommendations, update wear history
- **Sensors**: Weather API, user input, wardrobe dataset

---

## 📊 ML Model (KNN)

| Parameter | Value |
|-----------|-------|
| k (neighbors) | 5 |
| Distance Metric | Euclidean |
| Algorithm | Ball Tree |
| Accuracy | 51% |
| F1-Score | 0.608 |

---

## 🔍 A* Search Algorithm

Total outfit combinations: **162 × 159 × 179 = 4,610,682** possibilities

---

## 📁 Repository Contents

- Complete project report
- ML Component Plan
- Algorithm Design Plan
- Agent Design & Environment Analysis
- Dataset (closet_fashion_dataset.csv)
- Jupyter Notebook with demo

---

## 👤 Developer

**Simaab Malik**  
SAP ID: 54910  
BS Software Engineering 
Riphah International University  
**Supervisor**: Ma'am Shumaila Qayyum  
**Session**: Spring 2026 - 6th Sem

---

## 📄 License

Educational Project - Artificial Intelligence Course

---

*For complete details, refer to the project report.*
