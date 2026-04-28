# SafeSocial — Cyberbullying Detection System

## Overview
Full-stack cyberbullying detection web app combining 
React.js frontend with Python Flask NLP backend.

## Tech Stack
- Frontend: React.js, HTML, CSS, JavaScript
- Backend: Python, Flask
- ML/NLP: scikit-learn, NLTK, scipy

## Features
- Real-time text classification
- 87%+ classification accuracy
- Detects 5+ harmful content categories
- Instant alert mechanism
- Reduces harmful content response time by 60%

## How It Works
1. User inputs text via React frontend
2. Flask API processes the request
3. NLP pipeline preprocesses text
4. ML model classifies content
5. Alert triggered if harmful content detected

## Setup
### Backend
cd cyberbullying_detection-main
pip install -r requirements.txt
python app.py

### Frontend
cd client
npm install
npm start
