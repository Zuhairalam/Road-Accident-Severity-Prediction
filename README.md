# Road Accident Severity Prediction

A machine learning web app to predict the severity of road accidents, built as part of my guided learning journey in data science and machine learning.

---

## About the Project

Road accidents are a major public safety concern. This project uses a real-world road accident dataset and an Sklearn Pipeline to classify accident severity into three categories — **Slight Injury**, **Serious Injury**, or **Fatal Injury** — based on factors like driver details, road conditions, weather, and vehicle type. A Streamlit web app is included for interactive predictions.

---

## Tools & Libraries Used

- **Python**
- **Pandas** — data loading and manipulation
- **Matplotlib** — data visualization
- **Scikit-learn** — imputation, encoding, scaling, pipeline, model training
- **Imbalanced-learn** — handling class imbalance via RandomOverSampler
- **Streamlit** — interactive web app
- **Pickle** — model saving and loading
- **Jupyter Notebook** — development environment

---

## Project Files

| File | Description |
|------|-------------|
| `Road_accident_Project.ipynb` | Main notebook with data preprocessing, pipeline building, and model training |
| `Road_Accident_Project_app.py` | Streamlit web app for interactive accident severity prediction |
| `Road Accident Project.pkl` | Saved trained Sklearn pipeline model |
| `10 pipe dataset.csv` | Dataset used for training |
| `10 pipe img.png` | Pipeline diagram displayed in the app |

---

## Steps Followed

1. Loaded and explored the road accident dataset
2. Extracted hour of day from the time column
3. Encoded the target column (accident severity) using Label Encoding
4. Handled class imbalance using RandomOverSampler
5. Split data into training and testing sets (80/20)
6. Built an Sklearn Pipeline with:
   - Missing value imputation (SimpleImputer)
   - Categorical encoding (OneHotEncoder)
   - Feature scaling
7. Trained a classification model
8. Built a Streamlit app for real-time severity prediction

---

## Prediction Output

The app predicts one of three severity levels:
- **Slight Injury**
- **Serious Injury**
- **Fatal Injury**

---

## Note

This project was built as a guided learning project while learning machine learning concepts. The goal was to understand Sklearn Pipelines, handling imbalanced datasets, and building an end-to-end ML web app with Streamlit.

---

## Author

**Zuhair Alam**
B.Tech — Automobile Engineering (Electric & Hybrid Vehicles)
Aligarh Muslim University
[LinkedIn](https://www.linkedin.com/in/zuhair-alam-54196a395)
