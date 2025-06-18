# Music Genre Classification

A machine learning project to classify songs into different genres using audio features extracted from the GTZAN dataset. The models are trained using extracted features like MFCC, Chroma, Spectral Contrast, Tonnetz, and more.

---

## Repository Structure

- `notebook/`: Contains the implementation code for training and evaluating ML/DL models.
- `dataset/`: Contains `dataset_info.md` with source and feature details of the GTZAN dataset.
- `results/`: Stores confusion matrix image, evaluation metrics, and model comparison table.
- `requirements.txt`: Lists all Python dependencies used in the project.

---

## Project Overview

This project focuses on building a multi-class classification model that identifies the genre of a music clip based on extracted audio features. Several traditional ML models and a neural network were trained and evaluated.

---

## Work-done

- Audio feature extraction using Librosa
- Classical ML models: Logistic Regression, KNN, Decision Tree, SVM, Naive Bayes, Random Forest, XGBoost
- Deep Learning model (ANN) using TensorFlow
- Model evaluation: Accuracy, Confusion Matrix, Classification report

---

## Workflow Overview

- Preprocessed the dataset and extracted features from .wav files
- Split data into train-test sets
- Trained multiple ML and DL models
- Evaluated performance using accuracy and classification report
- Visualized model predictions using a confusion matrix

---

## Models used

- ML Models: Logistic Regression, KNN, Decision Tree, SVM, Naive Bayes, Random Forest, XGBoost
- Deep Learning: Artificial Neural Network (Keras)
- Evaluation Metrics:
  - Accuracy
  - Classification report
  - Confusion Matrix

---

## Results

Visit the [`results/`](results/) folder for all model's evaluation

---

## Dataset

- Dataset used: [GTZAN Genre Collection](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification)
- Total Samples: 1000
- Classes: 10 genres (e.g., pop, jazz, rock, reggae, metal, etc.)

See [`dataset/dataset_info.md`](dataset/dataset_info.md) for full feature list and source.

---

## How to Run This Project

1. Clone the repository:  
   git clone https://github.com/DarshMatariya/music-genre-classification.git  

2. Navigate to the notebook folder:  
   cd notebook  

3. Open and run the Colab notebook named 'music-genre-classification.ipynb'.


Feel free to open issues or submit pull requests for improvements.  
