# Sleep Health Prediction
### Project Overview
This project analyses a dataset containing demographic, lifestyle, and health-related variables, including physical activity level, stress level, sleep patterns, BMI, blood pressure, and sleep disorders.
With rising awareness of lifestyle-related health challenges, analysing sleep health data provides an opportunity to uncover insights that can inform healthier habits and preventive care. 
The findings from this analysis can help individuals, fitness app developers, and health researchers in tracking and improving sleep health outcomes.

### Objectives
- To evaluate the factors that most strongly predict sleep health scores.
- To explore the relationship between lifestyle and sleep disorders.
- To build an interactive dashboard that allows stakeholders to explore trends, risk factors, and potential interventions related to sleep health.
- To provide insights that can be applied in fitness apps, wearable devices, and digital health platforms to promote better sleep health and preventive care.

### Methodology
- **Data Collection**: Collected sleep health and lifestyle dataset from Kaggle.
- **Data cleaning & preprocessing**: Performed initial exploration on Excel, renamed some columns, fixed spelling errors for consistency, and handled missing values using Python.
- **Exploratory Data Analysis (EDA)**: Analysed distribution of health metrics and demographics using Matplotlib. Investigated correlations between predictors and sleep health. Normalised and standardised predictor features for further analysis.
- **Predictive Modelling**: Created a new column “Sleep Health Score” from sleep duration and sleep quality columns and used machine learning models (multiple linear regression and polynomial regression) to identify the most significant predictors of sleep health.
- **Dashboard building**: Used Looker Studio to visualise relationship between lifestyle, demographics, health metrics and sleep performance.
- **Tools Used**: Excel, Pandas, Numpy, Scikit-learn, Matplotlib, JupyterLab, Looker Studio, Google Slides.

### Key Findings
<img width="954" height="613" alt="Screenshot 2025-08-16 002511" src="https://github.com/user-attachments/assets/0135dca3-ff09-4fa7-a2c2-8ff50fe700b2" />


- High stress level and high diastolic BP decreases sleep health
- Physical activity and systolic BP increases sleep health 
- Age has a strong correlation with sleep performance as well

### Insights and Recommendations
- Lifestyle choices affect our health more than we realise and sleep health is one of the most important components of our wellbeing. Poor sleep health leads to depression, obesity, cardiovascular disorders, etc. 
- Technology has made it easier to track vital health metrics. With wearable devices and fitness apps, we can now track daily steps, heart rate, BP, sleep duration and sleep quality, but there’s a missing piece.

### Use Case
- Through predictive modelling, we know just how much physical activity is needed to get a good night’s rest.
- To implement the findings from this analysis, fitness app developers and wearable tech companies can now add a feature that predicts a user’s sleep health score and provide them with actionable steps to take to improve their sleep score.
- This will be a game changer not just for the tech companies behind these devices but for preventive care as a whole. 

### Conclusion
Good sleep doesn’t happen by chance. A healthier lifestyle promotes better sleep – reduced stress, daily walks, a good diet, normal blood pressure and heart rate – it all comes together to help us sleep better. 
Failure to maintain a healthy lifestyle, like a good diet and daily walks, leads to increased weight, which leads to high BP and other issues that cause sleep disorders.
Maintaining a healthy lifestyle can be hard but good sleep starts with better insights. What if your device not only shows you what’s important to your health but also reinforces you to sleep better and live healthier? 

### Useful Links
- Interactive dashboard: https://lookerstudio.google.com/reporting/e22d0e93-93b0-4c72-9615-a4258c8d7404
- Slide presentation: https://docs.google.com/presentation/d/15l8nipVG7s4nat31H6qQCNWogTNllPmjZj8EykbK4o0/edit?usp=sharing
