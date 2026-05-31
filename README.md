# AI-Powered Auto Fake Detection System

## Overview

The AI-Powered Auto Fake Detection System is a Flask-based web application designed to detect fake news articles and manipulated images 
using Artificial Intelligence and Machine Learning techniques. The system provides users with a simple interface to verify the authenticity 
of news content and images.

## Features

* Fake News Detection using Machine Learning models
* Fake Image Detection using Error Level Analysis (ELA)
* User Registration and Login Authentication
* Secure Password Hashing with Flask-Bcrypt
* Session Management
* Database Integration using SQLAlchemy
* Email Notification Support
* Responsive User Interface
* AI Model Integration with TensorFlow and Keras

## Technology Stack

### Frontend

* HTML5
* CSS3
* JavaScript
* Bootstrap

### Backend

* Python
* Flask

### Database

* SQLite
* SQLAlchemy ORM

### AI & Machine Learning

* TensorFlow
* Keras
* NumPy
* Pillow
* OpenCV

## Project Workflow

### Fake News Detection

1. User enters news content.
2. Text is preprocessed and cleaned.
3. The trained machine learning model analyzes the content.
4. The system predicts whether the news is Real or Fake.
5. Results are displayed to the user.

### Fake Image Detection

1. User uploads an image.
2. Error Level Analysis (ELA) is performed on the image.
3. AI model extracts manipulation patterns.
4. The system classifies the image as Authentic or Manipulated.
5. Results are displayed instantly.

## Key Highlights

* Combines NLP and Image Forensics in a single platform.
* Demonstrates real-world application of AI for misinformation detection.
* Provides an interactive and user-friendly interface.
* Designed for educational and research purposes.

## Future Enhancements

* Real-time news verification using external APIs.
* Multi-language support.
* Advanced Transformer-based NLP models.
* Improved image forensic analysis.
* Cloud deployment and scalability improvements.

## Installation

```bash
git clone https://github.com/yourusername/AI-Fake-News-Detection-System.git
cd AI-Fake-News-Detection-System

pip install -r requirements.txt

python app.py
```

## Author

Srishanth Srigadde

AI & Full Stack Development Enthusiast
