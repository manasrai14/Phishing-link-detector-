# Real-Time Phishing Link Detector

A machine learning-based web application that detects whether a given URL is legitimate or phishing. The application uses a trained ML model to analyse URL-based features and provides real-time predictions through a user-friendly Flask interface.

## Features

- Detects phishing and legitimate URLs
- Real-time URL analysis
- Machine learning-based prediction
- Simple and responsive web interface
- Fast and accurate classification

## Tech Stack

- Python
- Flask
- Scikit-learn
- Pandas
- HTML
- CSS
- JavaScript

## Project Structure

```
├── app.py
├── feature.py
├── convert.py
├── newmodel.pkl
├── DataFiles/
├── templates/
├── static/
└── README.md
```

## Installation

1. Clone the repository

```bash
git clone https://github.com/your-username/phishing-link-detector.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Run the application

```bash
python app.py
```

4. Open your browser and visit:

```
http://127.0.0.1:5000
```

## How It Works

1. Enter a website URL.
2. The application extracts relevant URL features.
3. The trained machine learning model analyses the features.
4. The application predicts whether the URL is **Legitimate** or **Phishing**.

## Future Improvements

- Browser extension integration
- Live URL reputation lookup
- Enhanced feature engineering
- Improved model accuracy

## License

This project is for educational and learning purposes.