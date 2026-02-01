# NBA Shot Selection Prediction

## Project Overview
This project focuses on predicting whether a basketball shot will be successful based on shot location, game situation, and player-related factors. The objective is to use machine learning to support data-driven decision-making in sports analytics and improve shot selection strategies.

---

## Problem Statement
The goal of this project is to build a machine learning classification model that predicts whether a shot attempt will result in a score or a miss. The prediction is based on contextual information such as shot distance, location on the court, game period, and remaining time.

---

## Dataset
- Shot-level basketball data containing details of each shot attempt  
- Includes information such as:
  - Shot location (x, y coordinates)
  - Shot distance
  - Game period and remaining time
  - Opponent and game context
- **Target Variable**:
  - `1` → Shot made  
  - `0` → Shot missed  

---

## Exploratory Data Analysis (EDA)
- Analyzed dataset structure, data types, and missing values  
- Studied shot distribution by distance and court location  
- Examined relationships between game context and shot success  
- Identified class imbalance in shot outcomes  

---

## Data Preprocessing & Feature Engineering
- Handled missing values and inconsistent records  
- Encoded categorical variables where required  
- Scaled numerical features for model compatibility  
- Selected relevant features influencing shot success  

---

## Machine Learning Models
The following classification models were trained and evaluated:
- Logistic Regression  
- Random Forest Classifier  
- Gradient Boosting Classifier  

---

## Model Evaluation
Models were evaluated using standard classification metrics:
- Accuracy  
- Precision  
- Recall  
- F1-score  
- Confusion Matrix  

The best-performing model was selected based on balanced performance across these metrics.

---

## Results
The final model is capable of predicting shot success probability with reliable performance. The insights derived from the model can help coaches and analysts design more effective offensive strategies and improve shot selection.

---

## Challenges Faced
- Class imbalance between made and missed shots  
- High correlation among spatial shot features  
- Selecting an optimal model that generalizes well  

These challenges were addressed through careful preprocessing and model comparison.

---

## Conclusion
This project demonstrates how machine learning can be applied to sports analytics to predict shot outcomes and support strategic decision-making. The approach highlights the value of data-driven analysis in competitive sports environments.

---

## Author
**Ajith M**  
Aspiring AI/ML Engineer
