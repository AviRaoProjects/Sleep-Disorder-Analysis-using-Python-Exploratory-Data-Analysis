# Sleep Disorder Analysis using Python (EDA Project)

## Overview
This project explores lifestyle, demographic, and health-related factors linked to **sleep disorders**.  
Using Python-based Exploratory Data Analysis (EDA), the goal is to uncover how variables such as **stress level, BMI category, sleep duration, physical activity, and health indicators** influence sleep health.

## Objectives
- Analyze factors affecting sleep quality and sleep disorders.
- Understand correlations among stress, BMI, sleep duration, and physical activity.
- Visualize patterns using Python libraries.
- Identify insights that can help understand risk factors.

## Dataset Information
The dataset includes:
- **Demographics** → Age, Gender, BMI Category  
- **Health Metrics** → Sleep Duration, Quality of Sleep, Stress Level, Heart Rate, BP  
- **Lifestyle** → Physical Activity Level  
- **Target Variable** → Sleep Disorder (Yes/No)
Rows: *Varies depending on dataset*  
Columns: *Typically around 10–12*

## Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Jupyter Notebook
- 
## Exploratory Data Analysis

### Load Dataset
```python
import pandas as pd

df = pd.read_csv("Sleep_health_and_lifestyle_dataset.csv")
df.head()
```
Key Insights
High stress levels strongly correlate with sleep disorders.
Overweight/Obese BMI groups show higher sleep disorder prevalence.
Low physical activity is associated with poor sleep health.
Sleep duration and sleep quality are major indicators of sleep disorder risk.

Conclusion
Sleep disorders are influenced by a combination of lifestyle and health factors.
Managing stress, maintaining a healthy BMI, and improving physical activity may reduce sleep-related problems.

How to Use
```
pip install pandas numpy matplotlib seaborn
jupyter notebook
```
Author
Avinash Vidyasagar Rao  
Data Analyst | Python | SQL | Power BI  
GitHub: https://github.com/AviRaoProjects
