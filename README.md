# Deep Learning Framework for Automated Waste Segregation

**Course:** Data Science Tools and Techniques (DSTT)  
**Student:** Lubna Saleem Khalid  
**Program:** PhD in Computer Science  
**Instructor:** Dr. Asma Ahmad

## Project Overview
This project develops a deep learning framework for automated waste image classification using a hybrid CNN–RNN–GRU architecture.

The system classifies waste images into six categories:
- Cardboard
- Glass
- Metal
- Paper
- Plastic
- Trash

## Models Implemented
- CNN Baseline
- Hybrid CNN–RNN–GRU
- Hybrid CNN–RNN–GRU (Tuned)
- Hybrid CNN–RNN–GRU (Class Weighted)

## Methodology
1. Dataset exploration and preprocessing
2. Training, validation, and testing split
3. Model implementation and training
4. Hyperparameter experiments
5. Class imbalance handling
6. Model evaluation and comparison
7. Final model selection and prediction pipeline

## Evaluation Metrics
- Accuracy
- Macro Precision
- Macro Recall
- Macro F1-score
- Confusion Matrix
- Inference Latency

## Technologies
Python, TensorFlow/Keras, NumPy, Pandas, Scikit-learn, OpenCV, Matplotlib and Streamlit.

## Repository Files
- `DSTT_Term_Project_Final.ipynb` — Complete project implementation (Part 1 and Part 2).
- `final_waste_segregation_cnn_rnn_gru.keras` — Trained final model.
- `class_labels.json` — Class labels.

## How to Run
Open the notebook in Google Colab or Jupyter Notebook and execute the cells in order.

Install the required dependencies using:

`pip install -r requirements.txt`

## Results
The final selected model achieved 83.79% test accuracy and 84.67% test Macro-F1 in the reported experiment.# DSTT-Waste-Segregation-Deep-Learning
Deep Learning Framework for Automated Waste Segregation Using Hybrid CNN-RNN-GRU Architecture
