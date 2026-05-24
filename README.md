#  ECG-Based Heart Attack Detection Using CNN

A deep learning project for automatic classification of ECG (Electrocardiogram) signals to detect cardiac abnormalities including heart attack patterns using Convolutional Neural Networks.

 **GitHub:** [github.com/sasighanta/Ecg-Classification](https://github.com/sasighanta/Ecg-Classification)

---

##  Overview

This project focuses on classifying ECG heartbeat signals into different categories using deep learning, achieving **98% accuracy** on the test dataset. The model can detect normal and abnormal heartbeat patterns for healthcare applications.

---

##  Features

-  **ECG Signal Classification** — Automatically classifies heartbeats into multiple categories
-  **Deep Learning Model** — CNN-based architecture for high accuracy classification
-  **Performance Evaluation** — Accuracy, precision, recall and confusion matrix analysis
-  **Model Comparison** — Compared CNN with traditional ML approaches (SVM, Random Forest)
-  **98% Accuracy** — Achieved on MIT-BIH Arrhythmia dataset

---

##  Tech Stack

| Layer | Technology |
|-------|-----------|
| Language | Python |
| Deep Learning | TensorFlow, Keras |
| Machine Learning | Scikit-learn |
| Data Processing | NumPy, Pandas |
| Visualization | Matplotlib, Seaborn |
| Environment | Google Colab, Kaggle |

---

##  Dataset

This project uses the **Heartbeat ECG Dataset** available on Kaggle.

- **Dataset Source:** [kaggle.com/datasets/shayanfazeli/heartbeat](https://www.kaggle.com/datasets/shayanfazeli/heartbeat)
- Dataset is **not stored** in this repository
- Downloaded dynamically inside the notebook using Kaggle utilities during runtime
- Keeps repository lightweight following standard ML practices

---

##  Methodology

1. **Data Preprocessing** — ECG signal cleaning and normalization
2. **Feature Extraction** — Extracting meaningful features from heartbeat signals
3. **Model Building** — CNN architecture for sequence classification
4. **Model Training** — Training with optimized hyperparameters
5. **Evaluation** — Accuracy, precision, recall, F1-score metrics
6. **Comparison** — Benchmarked against traditional ML models

---

##  Project Structure

```
Ecg-Classification/
├── notebooks/
│   └── Ecg_Classification.ipynb   ← Main notebook
├── data/                           ← Dataset placeholder
├── models/                         ← Saved model files
├── requirements.txt
└── README.md
```

---

## ⚙️ How to Run

### 1️⃣ Clone Repository
```bash
git clone https://github.com/sasighanta/Ecg-Classification.git
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Run on Google Colab
- Open `notebooks/Ecg_Classification.ipynb` in Google Colab
- Connect Kaggle API for dataset download
- Run all cells sequentially

---

##  Results

| Model | Accuracy |
|-------|---------|
| CNN (Deep Learning) | **98%** |
| Traditional ML | ~85-90% |

---

##  Future Improvements
- Real-time ECG signal classification
- Mobile app integration
- Multi-lead ECG analysis
- Larger dataset training

---

## 👨‍💻 Author

**Sasi Sai Tulasi Ghanta**  
[GitHub](https://github.com/sasighanta) • [LinkedIn](https://linkedin.com/in/sasighanta)

---

