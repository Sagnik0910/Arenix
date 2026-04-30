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

- Python
- Flask
- Pandas
- Scikit-learn
- HTML
- CSS
- Pytest
- Render
- Steam API / Steam data context

## Project Structure

```text
Arenix/
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
├── model/
│   ├── final_demand_model.pkl
│   └── training_report.json
├── static/
│   └── style.css
├── templates/
│   ├── home.html
│   ├── dashboard.html
│   └── compare.html
├── tests/
│   ├── test_app.py
│   └── test_live_training_data.py
└── arenix_screenshot_01.png ... arenix_screenshot_09.png
Screenshots
Home Page


Dashboard View


Analytics View


Model & Insights


Additional Screenshots










How To Run Locally
Clone the repository:
git clone https://github.com/Sagnik0910/Arenix.git
cd Arenix
Install dependencies:
pip install -r requirements.txt
Run the Flask application:
python app.py
Open the app in your browser:
http://127.0.0.1:5000
Machine Learning Workflow
The project follows a basic ML workflow:

Collect or prepare gaming-related data
Clean and process the dataset
Train the demand forecasting model
Save the final trained model
Generate a training report
Use the model inside the Flask dashboard
Display predictions and insights through frontend pages
Testing
Run tests using:

pytest
The test files check core app behavior and live training data functionality.

Deployment
The project includes deployment files for Render:

Procfile
render.yaml
runtime.txt
These files help deploy the Flask application as a web service.

Future Improvements
Add more real-time Steam API integrations
Improve model accuracy with larger datasets
Add user authentication
Add more interactive charts
Include advanced game comparison filters
Deploy the live dashboard publicly
Add SQL-based data storage for historical tracking
Author
Sagnik Guha

GitHub: Sagnik0910

License
This project is created for learning, portfolio building, and data analytics practice.
