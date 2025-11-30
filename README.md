# PhishDetect – Phishing URL Detection (ML-Based)

## Project Overview
* Machine learning–based system to detect phishing URLs.
* Extracts lexical, structural, and security-related URL features.
* Uses Gradient Boosting Classifier for high accuracy.
* Lightweight, modular, and scalable architecture.
* Supports real-time URL analysis via CLI or Flask web UI.

## Features
* Real-time phishing detection.
* 30+ URL features extracted automatically.
* Detects zero-day phishing URLs.
* High accuracy (96–98%).
* Flask-based simple user interface.
* Easily integrable into email filters, browsers, or security tools.

## Technology Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib
* **Framework:** Flask
* **Dataset:** PhishTank, OpenPhish, Alexa Top Sites
* **Model Storage:** Pickle (`.pkl`)

## Workflow
1. Dataset collection (phishing + legitimate URLs)
2. Data cleaning and preprocessing
3. URL feature extraction
4. Model training using multiple ML algorithms
5. Selection of best model (Gradient Boosting)
6. Evaluation using accuracy, precision, recall, F1-score, ROC-AUC
7. Real-time prediction
8. Deployment via Flask interface

## Model Performance
* Accuracy: **96–98%**
* F1 Score: **~0.96**
* Fast execution: **Milliseconds per URL**
* High precision + high recall
* Low false positives and false negatives

## How to Run
1. Clone repo
2. Install requirements
3. Run Flask app
4. Input any URL to get prediction

## Project Structure (Brief)
* `dataset/` → Raw + cleaned data
* `models/` → Trained ML model (`model.pkl`)
* `src/` → Code for preprocessing, feature extraction, training
* `app/` → Flask application
* `templates/` & `static/` → UI files

## Future Scope
* Browser extension for real-time alerts
* Add WHOIS & DNS intelligence
* Cloud-based API deployment
* Online learning for evolving phishing patterns
* Security dashboard for analytics

