# CodTech_Task_4 - Machine Learning Model Implementation

This project is a part of my internship at *CodTech*. 
The objective is to Build a sentiment classification model to predict whether product reviews are positive or negative using Python and Scikit-learn.

---

## 📝 Project Overview
This project implements a classification model using the Logistic Regression algorithm on a given dataset (`dataset.csv`).The goal is to accurately predict the target variable based on input features.

---

## 🛠 Tools Used
- Pandas, NumPy
- Scikit-learn
- CountVectorizer
- Logistic Regression
- Jupyter Notebook

---

## 📁 Files
- dataset.csv – Contains reviews & sentiment labels
- task4_sentiment_analysis.ipynb – Main notebook with full implementation

---

## 📌 Steps
1. Import libraries  
2. Load dataset  
3. Preprocess data (null drop, label encode)  
4. Vectorize text  
5. Split data  
6. Train Logistic Regression model  
7. Evaluate performance  
8. Predict custom reviews  
9. Conclude findings

---

## ▶ How to Run
1. Open the notebook in Jupyter or VS Code  
2. Run cells sequentially  
3. Enter custom review at the end when prompted

---

## 📈 Sample Output

Enter a review to analyze: This product is amazing!

✅ Predicted Sentiment: Positive

---

Enter a review to analyze: Worst experience ever. Totally disappointed.

❌ Predicted Sentiment: Negative

---

## Implementation

- **Data Loading:** The dataset is loaded using pandas.
- **Preprocessing:** Features and target variables are separated. Data is split into training and testing sets with an 80-20 ratio.
- **Feature Scaling:** StandardScaler is used to normalize the feature data.
- **Model Building:** Logistic Regression model from scikit-learn is trained on the scaled training data.
- **Prediction:** The model predicts target labels on the test set.

---

## Evaluation

- **Accuracy:** The model achieved an accuracy of approximately 87% on the test data.
- **Confusion Matrix:** Shows the number of correct and incorrect predictions for each class.
- **Classification Report:** Includes precision, recall, and F1-score for both classes, confirming balanced performance.

---

## Sample Output

Accuracy: 0.87
Confusion Matrix:
[[50  5]
 [ 7 38]]

Classification Report:
              precision    recall  f1-score   support

           0       0.88      0.91      0.89        55
           1       0.88      0.84      0.86        45

    accuracy                           0.87       100
   macro avg       0.87      0.87      0.87       100
weighted avg       0.87      0.87      0.87       100

---

## Conclusion

The logistic regression model effectively classifies the data with good accuracy and balanced precision and recall for both classes. Data preprocessing and scaling contributed significantly to model performance.

For future work, hyperparameter tuning and exploring more advanced models can further enhance results. This project serves as a foundational implementation of classification tasks using scikit-learn in Python.

---

 ##🙋‍♀ Submitted By

*Name:* Antima Samokhu Prajapati  
*Internship:* CodTech  
*Task:* 4 – Machine Learning Model Implementation


