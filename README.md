ECG-Based Heart Attack Detection Using CNN
A deep learning project for automatic classification of ECG (Electrocardiogram) signals to detect cardiac abnormalities including heart attack patterns using Convolutional Neural Networks.
 GitHub: github.com/sasighanta/Ecg-Classification

 Overview
This project focuses on classifying ECG heartbeat signals into different categories using deep learning, achieving 98% accuracy on the test dataset. The model can detect normal and abnormal heartbeat patterns for healthcare applications.

 Features

 ECG Signal Classification — Automatically classifies heartbeats into multiple categories
 Deep Learning Model — CNN-based architecture for high accuracy classification
 Performance Evaluation — Accuracy, precision, recall and confusion matrix analysis
 Model Comparison — Compared CNN with traditional ML approaches (SVM, Random Forest)
 98% Accuracy — Achieved on MIT-BIH Arrhythmia dataset


 Tech Stack
LayerTechnologyLanguagePythonDeep LearningTensorFlow, KerasMachine LearningScikit-learnData ProcessingNumPy, PandasVisualizationMatplotlib, SeabornEnvironmentGoogle Colab, Kaggle

 Dataset
This project uses the Heartbeat ECG Dataset available on Kaggle.

Dataset Source: kaggle.com/datasets/shayanfazeli/heartbeat
Dataset is not stored in this repository
Downloaded dynamically inside the notebook using Kaggle utilities during runtime
Keeps repository lightweight following standard ML practices


 Methodology

Data Preprocessing — ECG signal cleaning and normalization
Feature Extraction — Extracting meaningful features from heartbeat signals
Model Building — CNN architecture for sequence classification
Model Training — Training with optimized hyperparameters
Evaluation — Accuracy, precision, recall, F1-score metrics
Comparison — Benchmarked against traditional ML models


 Project Structure
Ecg-Classification/
├── notebooks/
│   └── Ecg_Classification.ipynb   ← Main notebook
├── data/                           ← Dataset placeholder
├── models/                         ← Saved model files
├── requirements.txt
└── README.md

 How to Run
1️⃣ Clone Repository
bashgit clone https://github.com/sasighanta/Ecg-Classification.git
2️⃣ Install Dependencies
bashpip install -r requirements.txt
3️⃣ Run on Google Colab

Open notebooks/Ecg_Classification.ipynb in Google Colab
Connect Kaggle API for dataset download
Run all cells sequentially


 Results
ModelAccuracyCNN (Deep Learning)98%Traditional ML~85-90%

 Future Improvements

Real-time ECG signal classification
Mobile app integration
Multi-lead ECG analysis
Larger dataset training


👨‍💻 Author
Sasi Sai Tulasi Ghanta
GitHub • LinkedIn
