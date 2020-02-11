# BAIT 509 Final Project

#### Contributors: Anh Nguyen, Suguna Menon, Raymond Hu

This project uses data related to the applicants' profile to predict his/her chance of admission in a specific graduate school.

*Business question*: The business problem of our client, Education Consultant Agency (ECA), is to predict how likely a student will be admitted into a desired university. This is useful for ECA’s clients to shortlist their targeted universities with their profiles. In addition, with the model, ECA’s clients can know which areas are important to admission so that they should focus on improving.


##### Features:
- *CGPA* (Undergraduate GPA (out of 10)) - Numeric 
- *GRE Scores* (out of 340) - Numeric
- *TOEFL Score* (out of 120) - Numeric
- *University Rating* (Different tiers that universities belong to (1=strongest tier, 5=weakest tier)) - Numeric
- *SOP* (Statement of Purpose strength, as rated by agency (out of 5)) - Numeric
- *LOR* (Letter of Recommendation strength, as rated by agency (out of 5)) - Numeric
- *Research* (Research Experience (1 = have experience, 0 = no experience)) - Numeric

##### Target:
*Chance* - Admission category of 5 levels (very low, moderately low, medium, moderately high, very high)

##### Files:

- *Admission_Predict.csv* - dataset (Source: https://www.kaggle.com/mohansacharya/graduate-admissions)
- *project_final_v3.ipynb* - Includes code for the end to end implementation of the prediction pipeline
- *BAIT 509 Final Project.pdf* - Report summarizing the results

##### Summary:
We have trained the dataset using three classifiers - Decision Tree, Random Forest, kNN. Based on the best accuracy obtained, we chose kNN as our final model for predictions and Random Forest to get the feature importance. 
