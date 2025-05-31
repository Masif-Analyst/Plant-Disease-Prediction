# Plant Disease Prediction

A web-based application for detecting plant leaf diseases using a Convolutional Neural Network (CNN) trained on the PlantVillage dataset. Built with Python, TensorFlow, and Streamlit, it allows users to upload leaf images and receive real-time disease predictions with treatment recommendations. Achieves 92% accuracy across 38 disease classes for 14 crop species.

## Features
- Upload JPEG/PNG leaf images for disease detection.
- CNN model with 92% accuracy, trained on PlantVillage dataset.
- Streamlit-based web interface for real-time predictions and recommendations.
- Image preprocessing: resizing, normalization, and data augmentation.
- Deployed on Streamlit Cloud for global accessibility.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Masif-Analyst/Plant-Disease-Prediction.git

Plant-Disease-Prediction/
│
├── data/
│   ├── dataset_info.md             # Description of PlantVillage dataset and preprocessing steps
│   └── sample_images/             # Sample leaf images for testing (subset of PlantVillage)
│
├── models/
│   ├── trained_model.h5           # Trained CNN model file
│   └── model_architecture.json    # JSON file describing the CNN architecture
│
├── src/
│   ├── preprocessing.py           # Image preprocessing functions (resizing, normalization, augmentation)
│   ├── model_training.py          # Script for training the CNN model
│   ├── prediction.py              # Script for disease prediction from images
│   └── app.py                    # Streamlit web application script
│
├── tests/
│   ├── test_preprocessing.py      # Unit tests for preprocessing functions
│   ├── test_prediction.py         # Unit tests for prediction functions
│   └── test_data/                # Test images and expected outputs
│
├── docs/
│   ├── Final_Report.pdf           # PDF version of the project report
│   ├── diagrams/                 # UML, DFD, and other diagrams (e.g., image4.jpeg, image5.jpeg, etc.)
│   └── user_manual.md            # User guide for running the application
│
├── requirements.txt               # Python dependencies
├── README.md                     # Main repository documentation
├── LICENSE                       # License file (e.g., MIT License)
└── .gitignore                    # Git ignore file for excluding unnecessary files
