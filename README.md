Sure, here's the corrected version of your README file:

---

# ML-ANN

Predicting whether bank customers will leave the bank or not based on various data related to them.

## Overview

This project utilizes Artificial Neural Network (ANN) implemented with libraries such as scikit-learn, Keras, TensorFlow, NumPy, and Pandas.

## Steps Involved

1. **Data Preprocessing**:
   - Label encoding and one-hot encoding for categorical features.
   - Handling missing values and feature transformation using column transformers.

2. **Data Splitting**:
   - Splitting the dataset into training and testing sets.

3. **Building ANN**:
   - Constructing an ANN with 2 hidden layers, employing rectifier activation functions for hidden layers and sigmoid for the output layer.

4. **Training ANN**:
   - Training the ANN model with 100 epochs.

5. **Model Evaluation**:
   - Evaluating the model's performance using accuracy metric and confusion matrix from scikit-learn.

## Directory Structure

```
ML-ANN/
│
├── README.md
├── dataset.csv
├── preprocess_data.py
├── train_ann.py
└── requirements.txt
```

## Usage

1. Clone the repository:

   ```
   git clone https://github.com/virat0311/ML-ANN.git
   ```

2. Install the required dependencies:

   ```
   pip install -r requirements.txt
   ```

3. Preprocess the dataset:

   ```
   python preprocess_data.py
   ```

4. Train the ANN model:

   ```
   python train_ann.py
   ```
