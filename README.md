# 🪨 Rock vs Mine Prediction

A Machine Learning classification project that predicts whether an object is a **Rock** or a **Mine** using sonar signal data.

## 📌 Project Overview

The objective of this project is to build a machine learning model capable of classifying objects based on sonar signal measurements.

The project uses the sonar dataset and applies **Logistic Regression** to distinguish between:

* `R` → Rock
* `M` → Mine

## 📊 Dataset

The dataset contains:

* **208 samples**
* **60 numerical features**
* **1 target column**

The 60 features represent sonar signal measurements, while the final column contains the class label.

## 🔄 Machine Learning Workflow

1. Load the sonar dataset
2. Explore the dataset
3. Separate features and target labels
4. Split the data into training and testing sets
5. Use stratified sampling to preserve the class distribution
6. Train a Logistic Regression model
7. Evaluate the model using accuracy
8. Use the trained model to make predictions on new sonar data

The dataset is divided using a **90/10 train-test split** with stratification.

## 🤖 Model

**Logistic Regression**

The model is implemented using Scikit-learn's `LogisticRegression` classifier.

## 📈 Model Evaluation

The model is evaluated on both training and test data using **accuracy score**.

| Dataset       |   Accuracy |
| ------------- | ---------: |
| Training Data | **83.42%** |
| Test Data     | **76.19%** |

The model achieved **76.19% accuracy on the test dataset**.

## 🔍 Prediction

The trained model can also classify a new sonar signal by reshaping the input data and passing it to the model for prediction.

The notebook includes an example prediction that classifies an input sonar signal as either a **Rock** or a **Mine**.

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn
* Logistic Regression
* Google Colab

## 📂 Project Structure

```text
rock-vs-mine-prediction/
│
├── rock_vs_mine_prediction.ipynb
└── README.md
```

## ▶️ How to Run

The project can be run using **Google Colab**.

1. Open the notebook in Google Colab.
2. Upload the required sonar dataset.
3. Run the notebook cells sequentially.
4. The model will train on the dataset.
5. Training and testing accuracy will be calculated.
6. You can provide sonar signal values to generate a Rock/Mine prediction.

## 🚀 Future Improvements

* Compare Logistic Regression with other classification algorithms
* Add a confusion matrix
* Evaluate precision, recall, and F1-score
* Perform feature scaling
* Tune model hyperparameters
* Compare model performance using cross-validation

## 👨‍💻 Author

**Harshul Sharma**
