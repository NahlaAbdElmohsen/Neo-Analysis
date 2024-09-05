# Neo-Analysis
This is a Machine Learning project about NEO(Nearest earth objects) from NASA dataset
# Introduction
This project contains information about NEOs such as(absolute_magnitude,**is_hazardous**,...etc) and has 2 machine learning models that can accurately predict whether a NEO is
hazardous or not, as the ability to accurately identify dangerous objects could be vital for planetary defense.
# Dataset Description
### where did the data come from?
[kaggle](https://www.kaggle.com/datasets/ivansher/nasa-nearest-earth-objects-1910-2024/data)
### How large is this dataset?
The dataset contains 338,199 records,observed by NASA from 1910 to 2024.
### What steps were taken in this project?
**1.Explore the data**
**2.Cleaning the data:** handing missing value,outliers,..etc
**3.EDA:** making approprite visualization to explore important features and trends
**4.Data preprocessing:** handling imbalanced data to make sure that model will get reliable results
**5.Model training and Evaluation:** trian the two model and evaluate thier accuracy to find the appropriate one
# Analysis goals
To precisely predict if the object is dangerous to Earth or not
# Results and insights
The first model -**Decision Tree**- gives accuracy of 94% and the second model -**Random Forest**- gives acuuracy of 95% 
after applying SMOTE technique on the dataset to handle imbalanced data
# References
[NEO Hazard prediction score 96%](https://www.kaggle.com/code/mohamedelsayedaffan/neo-hazard-prediction-score-96)

Material from MLSC Data Science and Machine learning Bootcamp
