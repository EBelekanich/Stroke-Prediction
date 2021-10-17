# Stroke-Prediction
## Purpose
Strokes are a leading cause of long-term disability and death 
Every 40 seconds, someone suffers from a stroke in the U.S
Understanding risk factors can help with prevention and awareness 
Distinguish high risk patients 
Catching early symptoms can mitigate long-lasting effects
Predict chances of having a stroke

## Data Sources and Variables
Project data was obtained from Kaggle.com

Original file type was Comma Separated File (CSV)

The data contains 5110 observations with 12 attributes

Each row in the data set provides relevant information about the patient

- **gender :** "Male", "Female" or "Other"
- **age :** age of the patient
- **hypertension :** 0: if the patient doesn't have hypertension 1: if the patient has hypertension
- **heart disease :** 0: if the patient doesn't have any heart diseases 1: if the patient has a heart disease
- **ever_married :** "No" or "Yes"
- **Residence_type :** "Rular" or "Urban"
- **avg_glucose_level :** average glucose level in blood
- **bmi :** body mass index
- **smoking_status :** "formerly smoked", "never smoked", "smokes" or "unkown"
- **stroke :**  1 if the patient had a stroke or 0 if not

## Exploraratry Data Analysis
Data Pre-Processing

- Obtaining Statistics
- Replacing Missing Values 
- Removing Unnecessary Variables

Traning and Testing Data Split
- 60/40 Ratio
- Random State Selection
