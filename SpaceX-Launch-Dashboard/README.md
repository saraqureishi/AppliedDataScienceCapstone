# SpaceX Falcon 9 — First Stage Landing Prediction

Predicting whether the SpaceX Falcon 9 first stage will land successfully — the key driver of launch cost. Completed as the capstone project for the **IBM Data Science Professional Certificate**.

## Overview
SpaceX advertises Falcon 9 launches at ~$62M versus ~$165M for other providers, largely because it reuses the first stage. This project predicts landing success to estimate launch cost and understand the factors behind it.

## What I did
- **Data collection** — gathered launch data via the SpaceX REST API and web scraping (Wikipedia).
- **Data wrangling** — cleaned the data and engineered a binary landing-outcome label.
- **Exploratory data analysis** — explored trends by launch site, orbit, payload mass and year using SQL, pandas, and visualisations.
- **Interactive visual analytics** — built maps with Folium and an interactive dashboard with Plotly Dash.
- **Machine learning** — trained and tuned classification models (Logistic Regression, SVM, Decision Tree, KNN) with GridSearchCV, and compared accuracy to find the best predictor.

## Tech & tools
Python · pandas · NumPy · scikit-learn · SQL · Matplotlib · Seaborn · Folium · Plotly Dash

## Files
- `lab_jupyter_launch_site_location.ipynb` — launch-site analysis and Folium maps
- `spacex_dash_app.py` — interactive Plotly Dash dashboard
- (analysis notebooks for data collection, EDA, and ML modelling)

## Key takeaways
- Landing success has improved over time and varies clearly by launch site, orbit, and payload mass.
- The best classification model predicted landing outcomes with strong accuracy, showing these features are genuinely predictive.
