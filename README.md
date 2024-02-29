# Credit Card Fraud Detection using Autoencoder

This project implements an autoencoder neural network for detecting fraud in credit card transactions. The autoencoder is trained on a dataset of credit card transactions labeled as normal or fraudulent. The model learns to reconstruct normal transactions and identify anomalies in the data, which are indicative of fraud.

## Setup
- Python 3.x
- Required packages: pandas, numpy, matplotlib, seaborn, scikit-learn, keras

## Usage
1. Install the required packages using pip install -r requirements.txt.
2. Run the code in a Jupyter notebook or any Python environment that supports the required libraries.

## Dataset
Download the Credit Card Fraud Detection dataset from the provided [link](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).

## Workflow

1. Exploration:
- Data is loaded and explored to understand its distribution and characteristics.

2. Data Preparation:
- Features are preprocessed, and the dataset is split into training and testing sets.

3. Building the Model:
- An autoencoder neural network is constructed with an encoding layer, hidden layers, and a decoding layer.

4. Training:
- The autoencoder is trained on the training dataset with the goal of reconstructing normal transactions accurately.

5. Evaluation:
- The model's performance is evaluated using the testing dataset.
- Metrics such as Mean Squared Error (MSE), Precision-Recall curve, ROC curve, and confusion matrix are used to assess the model's performance.

6. Results:
- The model's ability to detect fraud is visualized and analyzed using various plots and metrics.

## Results
The model achieves good performance in detecting fraudulent transactions, with a high area under the Precision-Recall curve and ROC curve. The confusion matrix shows a good balance between true positives and false positives.


