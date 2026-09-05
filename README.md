# Rock vs Mine Prediction

A Machine Learning project that predicts whether an object is a **Rock or a Mine** using sonar signal data.

## Project Overview

This project uses the **Sonar dataset** to train a machine learning model to classify objects as either Rock (`R`) or Mine (`M`) based on sonar signal measurements.

## Dataset

The dataset contains sonar signal readings collected from objects. Each sample contains multiple numerical features representing the sonar signal, along with a label indicating whether the object is a Rock or a Mine.

## Model

**Machine Learning Algorithm:** Logistic Regression

The model is trained on the sonar dataset and evaluated using separate training and testing data.

## Results

| Dataset       |   Accuracy |
| ------------- | ---------: |
| Training Data | **83.42%** |
| Test Data     | **76.19%** |

The model achieved **76.19% accuracy on the test data**, which indicates its performance on previously unseen samples.

## Technologies Used

* Python
* Google Colab
* NumPy
* Pandas
* Scikit-learn
* Logistic Regression

## Project File

The complete implementation is available in the Jupyter Notebook:

`rock_vs_mine.ipynb`

## How to Run

1. Open the notebook in Google Colab.
2. Upload or provide the required dataset.
3. Run the notebook cells sequentially.
4. The model will train and display its accuracy on the training and test datasets.
