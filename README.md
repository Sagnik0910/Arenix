# Arenix - Gaming Demand Forecasting & Analytics Platform

Arenix is a Flask-based machine learning web application built to forecast gaming demand and analyze player activity trends. The project uses historical game data, Steam-related context, predictive modeling, and interactive dashboard pages to help understand demand patterns in the gaming market.

## Project Overview

The gaming industry changes quickly, with player interest shifting based on trends, releases, pricing, popularity, and engagement. Arenix focuses on using data analytics and machine learning to identify demand patterns and provide useful insights through a clean web dashboard.

This project combines data preprocessing, model training, prediction logic, visual analytics, and a Flask frontend into one end-to-end application.

## Key Features

- Gaming demand forecasting using machine learning
- Flask-based web dashboard
- Steam data collection and snapshot scripts
- Live training data preparation
- Model training and validation workflow
- Game catalog support
- Demand comparison and dashboard pages
- Model evaluation report
- Responsive HTML/CSS frontend
- Basic automated tests using Pytest
- Deployment-ready files for Render

## Tech Stack

- **Python**
- **Flask**
- **Pandas**
- **Scikit-learn**
- **HTML**
- **CSS**
- **Pytest**
- **Render**
- **Steam API / Steam data context**

## Project Structure

```text
Arenix/
│
├── app.py
├── demand_model.py
├── train_model.py
├── validate_model_report.py
├── build_live_training_data.py
├── collect_steam_snapshots.py
├── run_daily_pipeline.py
├── game_catalog.py
├── model_data.csv
├── requirements.txt
├── Procfile
├── render.yaml
├── runtime.txt
├── pytest.ini
│
├── model/
│   ├── final_demand_model.pkl
│   └── training_report.json
│
├── static/
│   └── style.css
│
├── templates/
│   ├── home.html
│   ├── dashboard.html
│   └── compare.html
│
├── tests/
│   ├── test_app.py
│   └── test_live_training_data.py
│
└── arenix_screenshot_01.png ... arenix_screenshot_09.png
