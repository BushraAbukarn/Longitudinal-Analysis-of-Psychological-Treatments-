## This project was designed to examine the effectiveness of psychological treatments, specifically Cognitive Behavioral Therapy (CBT) and Mindfulness-Based Cognitive Therapy (MBCT), in alleviating depressive symptoms in diabetic patients. The analysis was conducted using a Mixed Effects Regression Model.
1. Brief introduction about what diabetes is and the difference between the two types of diabetes. Additionally, the brief introduction includes an explanation of the two psychological treatments and their impact on diabetic patients.
2. The data is a longitudinal dataset, patients were monitored over the course of one year, with their Beck Depression Inventory (BDI) scores—indicating the severity of depressive symptoms—measured at three key points: pre-treatment, post-treatment, and at the nine-month follow-up. The response variable is the BDI score, while the predictors include treatment group, gender, age, education level, type of diabetes, comorbidities, and neuroticism. This dataset is sourced from the study titled "What Works Best for Whom.
3. Data preparation involved conducting data cleaning, modification, and pivoting to ready the dataset for detailed analysis and visualization. This process included transforming the data into a long format, which required converting variables such as "BDIpre," "BDIpost," and "BDI9fu" into individual observations. Additionally, the variable containing these observations was renamed to "Month" and converted into numeric values.
4. The normality of the response variable BDI was assessed using the Shapiro-Wilk test and visualized with a histogram plot.
5. The mixed-effects regression model is a powerful tool for analyzing longitudinal data, making it particularly suitable for evaluating the impact of treatments like Cognitive Behavioral Therapy (CBT) and Mindfulness-Based Cognitive Therapy (MBCT) across diverse patient populations over time. Additionally, this model can highlight the most associated features of depression.
6. The model is used to predict the BDI score of a 45-year-old female in the MBCT post-treatment period, who has type II diabetes, a high level of education, no comorbidities, and a neuroticism level of 35
7. The results show that the estimated average BDI score decreases by 40% for each additional month of psychological treatment. This indicates that psychological treatments have a significant impact on alleviating depressive symptoms in diabetic patients over time.
