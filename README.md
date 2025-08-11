# Waze_Churn_Prediction_Model
Google's Advanced Data Analytics Course Project
(Waze is a navigation app owned by Alphabet)

Goal: 
Develop a churn prediction model using Python to help prevent churn and improve user retention, helping Waze make data-driven decisions about product development. The model helps to identify specific factors that contribute to churn and answer questions such as: 

Who are the users most likely to churn?, Why do users churn? When do users churn? etc.

Some insights include:
- Overall churn rate is ~17%, and the rate is consistent between iPhone users and Android users.

- Users who drive very long distances on their driving days are more likely to churn, but users who drive more often are less likely to churn. The reason for this discrepancy needs further investigation.
  
- Distance driven per driving day had a positive correlation with user churn. The farther a user drove on each driving day, the more likely they were to churn.
Number of driving days had a negative correlation with churn. Users who drove more days of the last month were less likely to churn.

- Some data was erroneous or problematic and yielded unlikely or even impossible values. For ex. driven_km_drives column (Max: 15,420km driven/day, seems physically impossible)





