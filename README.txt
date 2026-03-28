AI Traffic Congestion Predictor & Smart Travel Advisor

#  AI Traffic Congestion Predictor

##  Problem Statement
Traffic congestion is a major issue in urban areas, leading to wasted time, fuel consumption, and increased pollution. People often lack tools to predict traffic conditions before traveling.

## 💡 Solution
This project is an AI-powered web application that predicts traffic congestion levels (Low, Medium, High) based on user inputs such as:
- Time of day
- Day of week
- Weather condition
- Road type

It also provides travel advice based on the prediction.

---

##  AI/ML Approach
- Model: Random Forest Classifier
- Type: Supervised Learning
- Input Features:
  - Hour (0–23)
  - Day (0–6)
  - Weather (Clear/Rain)
  - Road Type (Residential/Highway)
- Output:
  - Traffic Level (Low, Medium, High)

---

##  Tech Stack

### Frontend
- HTML
- CSS
- JavaScript

### Backend
- Python (Flask API)

### AI
- Scikit-learn
- Pandas

---

##  Project Structure

traffic-project/
│
├── app.py
├── model.py
├── traffic_model.pkl
├── requirements.txt
├── Procfile
├── frontend/
│ └── index.html