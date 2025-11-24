# Human Activity Recognition Using Machine Learning

This project focuses on classifying different gym exercises using wearable sensor data.  
The goal is to recognize activities such as bench press, squat, shoulder press, etc., using accelerometer and gyroscope readings.

The work is based on my M.Tech academic project and associated research report.

---

## 📌 Project Overview

- The dataset contains motion sensor readings collected during different gym workouts.
- Each activity has multiple samples recorded using accelerometer and gyroscope sensors.
- Several machine learning algorithms were evaluated for classifying activities.
- Models were compared using accuracy, precision, recall, and F1-score.

---

## 📝 Steps Performed in the Project

- Loaded and cleaned sensor dataset  
- Handled missing values and normalized features  
- Encoded the activity labels  
- Split data into training and testing sets  
- Trained multiple ML models including:
  - Logistic Regression  
  - Random Forest  
  - Decision Tree  
  - Support Vector Machine (SVM)  
- Compared performance of each model  
- Selected the best model based on evaluation metrics  

---

## 📊 Results Summary

- The machine learning models were able to distinguish different gym activities with high accuracy.
- Random Forest and SVM models performed the best among all tested algorithms.
- The results can be useful for fitness monitoring, exercise tracking, and posture detection systems.

---

## 🔧 Tools & Libraries

- Python  
- Pandas  
- NumPy  
- scikit-learn  
- Matplotlib / Seaborn (for visualization)

---

## 📂 Files Included in This Repository

| File Name                          | Description |
|------------------------------------|-------------|
| `gym_activity_recognition.ipynb`   | Jupyter notebook containing data preprocessing, model training, and evaluation |
| `Gym_Activity_Recognition_Report.pdf` | Research paper describing dataset, methodology, and results |
| `README.md`                        | Project documentation |

---

## 📍 Dataset Information

- Contains accelerometer + gyroscope readings  
- Features include X/Y/Z axis motion data  
- Labeled according to workout type  
- Dataset used only for academic purposes

---

## 👨‍💻 Author

**Dhruv Kukadiya**  
M.Tech – AI & Data Science  
VIT Bhopal University

