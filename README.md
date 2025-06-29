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

> Replace XX and YY with actual values from your results.

---

## 📷 Visual Highlights

<p align="center">
  <img src="images/roc_curve.png" width="400"/>
  <br/>
  <em>ROC Curve for Personality Classification</em>
</p>

---

## 🚀 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/personality-logistic-regression.git
   cd personality-logistic-regression
