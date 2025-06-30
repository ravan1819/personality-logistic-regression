 # Personality Prediction using Logistic Regression

This project uses a dataset of behavioral and psychological traits to predict whether a person is an **Introvert (0)** or **Extrovert (1)** using **Logistic Regression**. It includes data preprocessing, exploratory data analysis (EDA), model training, and evaluation.

---

## 📁 Project Structure

---


---

## 📊 Features Used

| Feature                     | Description                                        |
|----------------------------|----------------------------------------------------|
| `Time_spent_Alone`         | Average time spent alone per day                  |
| `Stage_fear`               | Binary (Yes/No) – Fear of public speaking         |
| `Social_event_attendance`  | Frequency of attending social events              |
| `Going_outside`            | Frequency of going outside                        |
| `Drained_after_socializing` | Binary (Yes/No) – Feels drained after socializing |
| `Friends_circle_size`      | Number of close social contacts                   |
| `Post_frequency`           | Frequency of social media posts                   |
| `Personality`              | Target variable (Introvert = 0, Extrovert = 1)    |

---

## ✅ Steps Performed

- ✔️ Removed missing values & duplicates  
- ✔️ Encoded binary columns and target label  
- ✔️ Performed EDA: KDE plots, pair plots, heatmaps, and boxplots  
- ✔️ Trained logistic regression model and evaluated with AUC, accuracy, ROC, and feature weights  

---

## 📷 Exploratory Data Analysis

### ✅ Distributions of Numeric Features

![Time Spent Alone](images/time_spent_alone_dist.png)  
![Social Event Attendance](images/social_event_attendance_dist.png)  
![Going Outside](images/going_outside_dist.png)  
![Friends Circle Size](images/friends_circle_size_dist.png)  
![Post Frequency](images/post_frequency_dist.png)

---

### ✅ Binary Feature Distributions

![Stage Fear](images/stage_fear_count.png)  
![Drained After Socializing](images/drained_after_socializing_count.png)

---

### ✅ Boxplots by Personality

![Boxplot - Time Spent Alone](images/time_spent_alone_box.png)  
![Boxplot - Social Events](images/social_event_attendance_box.png)  
![Boxplot - Going Outside](images/going_outside_box.png)  
![Boxplot - Friends Circle Size](images/friends_circle_size_box.png)  
![Boxplot - Post Frequency](images/post_frequency_box.png)

---

### ✅ Correlation & Pairwise Feature Relationships

![Correlation Heatmap](images/correlation_heatmap.png)  
![Pair Plot](images/pair_plot.png)

---

## 🧠 Model Evaluation & Results

### ✅ Performance Summary

| Metric       | Value |
|--------------|-------|
| Accuracy     | **93%** |
| ROC-AUC      | **0.96** |

---

### ✅ Confusion Matrix

![Confusion Matrix](images/confusion_matrix.png)

---

### ✅ ROC Curve

![ROC Curve](images/roc_curve.png)

---

### ✅ Feature Importance (Logistic Coefficients)

![Feature Importance](images/feature_importance.png)

---

## 🚀 How to Run

1. **Clone this repo:**

```bash
git clone https://github.com/yourusername/personality-logistic-regression.git
cd personality-logistic-regression

