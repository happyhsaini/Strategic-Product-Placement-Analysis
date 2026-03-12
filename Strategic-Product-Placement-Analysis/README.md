# Strategic Product Placement Analysis

This is a Flask web application that displays a dashboard for Strategic Product Placement Analysis.

## Project Structure

Strategic-Product-Placement-Analysis
│
├── app.py
├── requirements.txt
├── templates
│   └── index.html
├── static
│   ├── css
│   ├── js
│   └── images
└── Dashboard

## Run Locally

pip install -r requirements.txt
python app.py

Open:
http://127.0.0.1:5000

## Deploy on Render

Build Command:
pip install -r requirements.txt

Start Command:
gunicorn app:app