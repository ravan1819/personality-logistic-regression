 # Personality Prediction using Logistic Regression

This project uses a dataset of behavioral and psychological traits to predict whether a person is an **Introvert (0)** or **Extrovert (1)** using **Logistic Regression**. It includes data preprocessing, exploratory data analysis (EDA), model training, and evaluation.

---

## 📁 Project Structure

---

## 📊 Features Used

| Feature | Description |
|--------|-------------|
| `Time_spent_Alone` | Average time spent alone per day |
| `Stage_fear` | Binary (Yes/No) - Fear of public speaking |
| `Social_event_attendance` | Frequency of attending social events |
| `Going_outside` | Frequency of going outside |
| `Drained_after_socializing` | Binary (Yes/No) - Feeling exhausted after socializing |
| `Friends_circle_size` | Number of close social contacts |
| `Post_frequency` | Frequency of social media posts |
| `Personality` | Target variable (Introvert = 0, Extrovert = 1) |

---

##  Steps Performed

- ✅ Handled missing values and duplicates
- ✅ Encoded categorical variables (Yes/No → 1/0, Introvert/Extrovert → 0/1)
- ✅ EDA: Histograms, KDE plots, Pair plots, Correlation Heatmaps
- ✅ Logistic Regression:
  - Accuracy & AUC Score
  - Confusion Matrix
  - ROC Curve
  - Feature Importance plot

---

## 📈 Model Performance

| Metric | Value |
|--------|--------|
| Accuracy | *93%* |
| ROC-AUC  | *0.96* |

---

## 📷 Visual Highlights

<p align="center">
  <img src="images/roc_curve.png" width="400"/>
  <br/>
  <em>ROC Curve for Personality Classification</em>
</p>

---![Accuracy](https://github.com/user-attachments/assets/91fe67df-89f0-49d1-9131-8b4ff3e6569d)
![Confusin_Matrix](https://github.com/user-attachments/assets/1b7b7adf-172e-41b5-b691-54eac8ca808f)
![ROC](https://github.com/user-attachments/assets/868dc3cd-a70e-4cef-855f-cfb67da7d7f3)



## 🚀 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/personality-logistic-regression.git
   cd personality-logistic-regression
