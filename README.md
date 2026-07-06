# SecureMail AI
## Intelligent Phishing Detection Using Email Intent and Behavioral Analysis
SecureMail AI is an intelligent phishing detection system that integrates machine learning with email intent analysis, URL inspection, sender reputation analysis, and risk scoring to identify phishing emails through an interactive Gradio interface
.
---
## Features
- Machine Learning-based phishing detection
- Email intent detection
- URL analysis
- Sender reputation analysis
- Risk score generation
- Sender relationship graph
- Interactive Gradio dashboard
---
## Project Structure
```
SecureMail_AI/
│
├── app.py
├── predict.py
├── intent_detection.py
├── url_analysis.py
├── sender_analysis.py
├── risk_score.py
├── graph_analysis.py
│
├── phishing_model.pkl
├── vectorizer.pkl
│
├── requirements.txt
└── README.md
```
---
## Software Requirements
- Python 3.11 (Recommended)
- pip
---
## Installation
### Clone Repository
```bash
git clone https://github.com/<YOUR_USERNAME>/SecureMail_AI.git
```
or download the ZIP file and extract it.
---
### Navigate to Project Folder
```bash
cd SecureMail_AI
```
---
### Install Required Libraries
```bash
pip install -r requirements.txt
```
---
### Run the Application
```bash
python app.py
```
---
## Output
The application starts a Gradio server.
Open the URL displayed in the terminal, typically:
```
http://127.0.0.1:7860
```
---
## Technologies Used
- Python
- Machine Learning
- Scikit-learn
- Gradio
- NetworkX
- Matplotlib
- Joblib
- TLDExtract
---
## Machine Learning Pipeline
Dataset
↓
Text Cleaning
↓
TF-IDF Vectorization
↓
Machine Learning Classification
↓
Phishing Prediction
↓
Intent Detection
↓
URL Analysis
↓
Sender Reputation Analysis
↓
Risk Score Generation
↓
Final Security Report
---
## Author

SecureMail AI Project
