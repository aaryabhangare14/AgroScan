## Project Structure

```text
AgroScan/
│
├── static/              # CSS, JS, Images
├── webpage/             # Frontend pages
├── uploads/             # Uploaded images
├── train/               # Training dataset
├── test/                # Testing dataset
├── valid/               # Validation dataset
│
├── server.js            # Backend server
├── loginin.py           # Login module
├── requirements.txt     # Python dependencies
├── package.json         # Node.js dependencies
│
├── train_plant_disease.ipynb
├── Test_plant_diseases.ipynb
│
└── README.md
```
🌱 AgroScan - AI Powered Plant Disease Detection System
Problem Statement

Farmers often face difficulties in identifying crop diseases at an early stage, leading to reduced productivity and crop losses.

Solution

AgroScan uses Machine Learning and Deep Learning techniques to analyze plant leaf images and detect diseases accurately. The system provides disease predictions and helps farmers take preventive actions.

Key Features
🌿 Plant disease detection using Deep Learning
📷 Image upload and analysis
🤖 AI-based prediction model
📊 User-friendly web interface
🔐 User authentication
📁 Dataset training and testing pipeline

Technologies Used:
Python
TensorFlow / Keras
OpenCV
Flask
HTML, CSS, JavaScript
Node.js
MySQL

Team Role
Developed and trained deep learning models for plant disease classification.
Built frontend and backend integration.
Implemented image upload and prediction functionality.
Managed dataset preprocessing and model evaluation.

## Dataset

This project uses the **New Plant Diseases Dataset** from Kaggle.

**Dataset Link:** https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset

The dataset contains approximately 87,000+ images of healthy and diseased plant leaves across 38 classes and is widely used for plant disease classification research.

Due to GitHub storage limitations, the dataset is not included in this repository.

### Download Dataset

1. Visit the Kaggle dataset link above.
2. Download and extract the dataset.
3. Place the dataset folders in the project directory as shown below:

AgroScan/
├── train/
├── valid/
├── test/
├── webpage/
├── static/
└── server.js

### Note

The dataset belongs to its original authors and is distributed through Kaggle. Please follow the dataset's license and usage terms before using it.
