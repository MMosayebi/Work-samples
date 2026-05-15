# Project Heart Attack Prediction

**Dataset:** [heart.csv](https://github.com/MMosayebi/Work-samples/tree/bce1181b342160a2e3bd582daf075fff7b6ce8bc/Heart%20Attack/Dataset).
The data is based on patient records from a hospital.

**Dataset Inforamtion:** [Data Information.txt](https://github.com/MMosayebi/Work-samples/blob/bce1181b342160a2e3bd582daf075fff7b6ce8bc/Heart%20Attack/Data%20Information.txt)

**File:** [Heart Attack.ipynb](https://github.com/MMosayebi/Work-samples/blob/bce1181b342160a2e3bd582daf075fff7b6ce8bc/Heart%20Attack/Heart%20Attack.ipynb)

## Project Goal
Predict the likelihood of a heart attack for patients using factors such as:
- Age, gender, cholesterol level, and other medical indicators

## Exploratory Data Analysis (EDA)
- The age range of patients is mostly **between 40 and 70 years**

## Model Selection
Since the target variable is **binary (0 and 1)** , the recommended model is **Logistic Regression**.

## Data Preprocessing
- **Normalization:** Used `StandardScaler` from scikit-learn to improve model accuracy

## Model Training & Optimization
- **Train/Test Split:** 75% train – 25% test  
- **Hyperparameter Tuning:** `GridSearchCV`  
- **Final Accuracy:** **83%**

## Evaluation Metrics

### Confusion Matrix & Classification Report
The model has been trained optimally with minimal error.

- **False Negatives (FN):** 2  
  → The model incorrectly predicted **2 patients** as having zero chance of a heart attack.

### Jaccard Score
This metric helps determine whether the model performs better for:
- Patients with **higher risk**
- Patients with **lower risk**  

**Result:** Better performance for patients with a higher risk of heart attack.

## Custom Threshold for Real-World Use

To reduce the risk of False Negatives (patients wrongly told they are safe):

- **If predicted probability > 40%** → Patient is likely to have a heart attack  
- **If predicted probability is between 35% – 40%** → Patient is in the **FN risk zone** → requires further testing

> This custom threshold helps prevent critical misses while balancing false alarms.
