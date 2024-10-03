## This project was designed to examine the effectiveness of psychological treatments, specifically Cognitive Behavioral Therapy (CBT) and Mindfulness-Based Cognitive Therapy (MBCT), in alleviating depressive symptoms in diabetic patients. 
### Intro
A brief introduction was provided about what diabetes is and the differences between the two types of diabetes. Additionally, the introduction included an explanation of the two psychological treatments and their impact on diabetic patients.

### Data Source
The data is a longitudinal dataset sourced from the study titled "What Works Best for Whom."

### Data Preparation
Data preparation involved conducting data cleaning, modification, and pivoting to prepare the dataset for detailed analysis and visualization. This process included transforming the data into a long format, which required converting Beck Depression Inventory scores variables "BDIpre," "BDIpost," and "BDI9fu" into individual observations.

The normality of the response variable BDI was assessed using the Shapiro-Wilk test and visualized with a histogram plot.

### Analysis Method
The mixed-effects regression model is a powerful tool for analyzing longitudinal data, making it particularly suitable for evaluating the impact of treatments like Cognitive Behavioral Therapy (CBT) and Mindfulness-Based Cognitive Therapy (MBCT) across diverse patient populations over time. Additionally, this model helped identify significant predictors associated with depression by assessing the statistical significance of their effects through hypothesis testing.

The model was also used to predict the BDI score of a 45-year-old female in the MBCT post-treatment period, who has Type 2 diabetes, a high level of education, no comorbidities, and a neuroticism level of 35.

### Results
The results show that the estimated average BDI score decreases by 40% for each additional month of psychological treatment. This indicates that psychological treatments have a significant impact on alleviating depressive symptoms in diabetic patients over time.
