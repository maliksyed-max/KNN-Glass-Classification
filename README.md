# KNN-Glass-Classification# Glass Type Classification using KNN

## 📌 About the Project

This project uses the K-Nearest Neighbors (KNN) machine learning algorithm to classify different types of glass based on their chemical composition.

The dataset contains numerical features such as refractive index and the concentration of different chemical elements present in the glass.

## 🎯 Objective

- Classify glass into different glass types.
- Analyze the relationship between chemical composition and glass type.
- Apply the K-Nearest Neighbors (KNN) classification algorithm.
- Evaluate the classification performance on unseen data.
- Gain practical experience with supervised machine learning.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## 📊 Dataset

The dataset contains chemical properties of glass samples.

Important features include:

- RI - Refractive Index
- Na - Sodium
- Mg - Magnesium
- Al - Aluminum
- Si - Silicon
- K - Potassium
- Ca - Calcium
- Ba - Barium
- Fe - Iron

The target variable represents the type of glass.

## 🔎 Methodology

1. Load the glass dataset.
2. Understand the dataset and its features.
3. Separate input features and the target variable.
4. Split the data into training and testing sets.
5. Apply the K-Nearest Neighbors (KNN) classification algorithm.
6. Make predictions on the test data.
7. Evaluate the classification performance.
8. Analyze the results.

## 🤖 About KNN

K-Nearest Neighbors (KNN) is a supervised machine learning algorithm used for classification and regression.

For classification, KNN identifies the nearest data points to a new sample and assigns the class that is most common among its nearest neighbors.

## ▶️ How to Run

Install the required libraries:

```bash
pip install pandas numpy matplotlib scikit-learn openpyxl
```

Run the program:
```
python KNN-Glass.py
```

📂 Project Files
- KNN-Glass.py - Python implementation of the KNN classification algorithm.
- glass.xlsx - Glass dataset used for classification.
- 
📚 Key Learning
This project provided practical experience with:
- Data preprocessing
- Feature selection
- Train-test splitting
- KNN classification
- Machine learning model evaluation
- Working with real-world chemical composition data
