# English Premier League Match Outcome Predictor ⚽📊

![EPL Prediction Demo](assets/demo.gif) <!-- Replace with your screenshot/GIF -->

A machine learning model that predicts English Premier League match outcomes (Home Win/Draw/Away Win) using historical match data.

## 🔍 Overview
- Scraped **2020-2021 and 2021-2022 EPL season data**
- Engineered features including **rolling team performance metrics**
- Trained a **RandomForestClassifier** achieving **67.5% accuracy**
- Implements a reproducible data pipeline from scraping to prediction

## 🛠️ Technical Details

### Data Pipeline
```mermaid
graph LR
    A[Web Scraping] --> B[Data Cleaning]
    B --> C[Feature Engineering]
    C --> D[Model Training]
    D --> E[Prediction]
