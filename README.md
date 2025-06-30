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

## 📷 Visual Highlights`

<p align="center">
  <img src="images/roc_curve.png" width="400"/>
  <br/>
  <em>ROC Curve for Personality Classification</em>
</p>

---
![Accuracy](https://github.com/user-attachments/assets/91fe67df-89f0-49d1-9131-8b4ff3e6569d)
![Confusin_Matrix](https://github.com/user-attachments/assets/1b7b7adf-172e-41b5-b691-54eac8ca808f)
![ROC](https://github.com/user-attachments/assets/868dc3cd-a70e-4cef-855f-cfb67da7d7f3)
![Screenshot (51)](https://github.com/user-attachments/assets/beae07c8-ba2f-40cc-9486-91e6215b58fb)
![Screenshot (52)](https://github.com/user-attachments/assets/4501e121-9640-4244-bf59-c41a3340343d)
![Screenshot (53)](https://github.com/user-attachments/assets/d381cd28-ca4d-46f5-88f2-f850fa574958)
![Screenshot (56)](https://github.com/user-attachments/assets/6175d02f-2cc0-4990-98e2-5d8a0ae3795c)
![Screenshot (57)](https://github.com/user-attachments/assets/b03def77-4b50-4772-abda-d4103619a102)
![Screenshot (58)](https://github.com/user-attachments/assets/fc17a584-6b9f-4810-b8a1-e9e420679c07)
![Screenshot (59)](https://github.com/user-attachments/assets/3f2d7639-517e-4e36-bff1-1bfa383c157b)
![Screenshot (60)](https://github.com/user-attachments/assets/3c4bc430-50c0-4a3e-8f54-80f167782476)
![Screenshot (61)](https://github.com/user-attachments/assets/0306f2f4-6746-42f8-9f15-65de57457091)
![Screenshot (62)](https://github.com/user-attachments/assets/01937ec9-4e9b-4061-8454-8f739bdc32c4)
![Screenshot (63)](https://github.com/user-attachments/assets/a467ed7c-33ed-41f2-81df-98ba3817db55)
![Screenshot (64)](https://github.com/user-attachments/assets/1892bbca-c939-4f58-858f-4f44159479e1)
![Screenshot (65)](https://github.com/user-attachments/assets/1822c1ff-a3aa-4295-8553-7089550f4a59)
![Screenshot (66)](https://github.com/user-attachments/assets/fde2ea19-32c6-4611-9bb3-cf7d69e4a64f)
![Screenshot (67)](https://github.com/user-attachments/assets/d196e84f-51ee-46b5-b2a0-4f584036c747)
![Screenshot (69)](https://github.com/user-attachments/assets/359cdc19-708d-4eed-8ba4-079db536ac15)
![Screenshot (70)](https://github.com/user-attachments/assets/c85bd82e-e8c3-42d8-ad8d-19215e78e0ee)
![Screenshot (71)](https://github.com/user-attachments/assets/7e552441-ee2c-4ca9-b135-131a9d994fe3)
![Screenshot (72)](https://github.com/user-attachments/assets/92013a09-f401-4d0d-b5ee-de531358d1c2)
![Screenshot (75)](https://github.com/user-attachments/assets/7d98621a-9a16-47cb-9442-83ca729fe12a)
![Screenshot (78)](https://github.com/user-attachments/assets/a925d7ea-94ba-4347-a3a0-4ef321537ca6)
![Screenshot (79)](https://github.com/user-attachments/assets/7b83450f-8264-464d-8c1b-95de3b7129bb)



## 🚀 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/personality-logistic-regression.git
   cd personality-logistic-regression
