# Automatic Radiology Report Generation from Chest X-Rays

## Project Overview
This project aims to automate the generation of radiology reports from chest X-ray images using deep learning models. It leverages CNN (CheXNet), LSTM, and Multi-Head Attention (MHA) for accurate disease prediction and report generation.

## Features
- Preprocessing of X-ray images using CLAHE.
- EfficientNet-based feature extraction.
- CheXNet-LSTM model for report generation.
- Flask-based web interface for image upload and result visualization.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/AG8.git
   cd AG8

Install dependencies:

pip install -r requirements.txt
Usage
Run the Flask application:

python app.py
Open http://localhost:5000 in your browser.
Upload chest X-ray images to generate reports.
Model Architecture
Preprocessing: CLAHE enhancement for improved image clarity.
Feature Extraction: EfficientNet for extracting meaningful features.
Report Generation: CheXNet-LSTM model with Multi-Head Attention.
Results
The model was evaluated using BLEU scores and showed high accuracy in generating meaningful radiology reports.

Future Scope
Enhancing the dataset for more diverse reports.
Optimizing model performance for real-time processing.
Extending the model for multi-disease classification.
