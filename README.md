# Automated Identification of Herbarium Species

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.11-green.svg)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.15-orange.svg)](https://www.tensorflow.org/)

## Overview
This project implements an **automated system for identifying herbarium plant species** using image classification techniques. Users can upload an image of a plant specimen, and the system predicts the species with high accuracy. This project leverages **deep learning models** and can serve as a digital assistant for botanists, researchers, and plant enthusiasts.

## Features
- Upload images of herbarium specimens and get species predictions.
- High-accuracy classification model trained on multiple plant species.
- Simple and user-friendly interface for interacting with the model.
- Optional web interface for real-time usage.
- Easily extendable to add more species or integrate into existing systems.

## Technology Stack
- **Backend:** Python, FastAPI
- **Frontend:** HTML/CSS/JavaScript (optional for web app)
- **Model:** EfficientNetB3 (or your specific trained model)
- **Environment:** Jupyter Notebook for model training and testing
- **Dependencies:** 
  - `tensorflow`
  - `keras`
  - `opencv-python`
  - `numpy`
  - `pandas`
  - `fastapi`
  - `uvicorn`
  - `pillow`

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/herbarium-species-identifier.git
   cd herbarium-species-identifier
2. Create a virtual environment, activate it, and install dependencies in a single step:
   ```bash
   python -m venv venv
    # Activate the environment
    source venv/bin/activate   # Linux/Mac
    venv\Scripts\activate      # Windows
    # Install dependencies
    pip install -r requirements.txt
