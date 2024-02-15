# HR_Analysis
Your client is a large MNC and they have 9 broad verticals across the organisation. One of the problem your client is facing is around identifying the right people for promotion (only for manager position and below) and prepare them in time. Currently the process, they are following is:
* employee_id: Unique ID for employee
* department: Department of employee
* region: Region of employment (unordered)
* education:Education Level
* gender: Gender of Employee
* recruitment_channel: Channel of recruitment for employee
* no_of_trainings: no of other trainings completed in previous year on soft skills, technical skills etc.
* age: Age of Employee
* previous_year_rating: Employee Rating for the previous year
* length_of_service: Length of service in years
* KPIs_met >80%: if Percent of KPIs(Key performance Indicators) >80% then 1 else 0
* awards_won?: if awards won during previous year then 1 else 0
* avg_training_score: Average score in current training evaluations
* is_promoted: (Target) Recommended for promotion

# Problem Statement: 
Predict whether a potential promotee at checkpoint in the test set will be promoted or not after the evaluation process.

# Apporach
This is a type of Binary class Clasiffication problem. The data is highly unbalanced, so the SMOTE teachnique is used to upscale the data. The model was applied eventually.

##  Conclusion
The different models used are Logistic Regression, Descision Trees, Random Forest.
The Logistic Regression Model with 0.49 threashold value gives the best recall value and accuracy. Hence it is the best model

For threashold 0.49 the Recall & Accuracy scores are:
* Recall vlaue Class 0- 0.71
* Recall value Class 1- 0.70
* Accuracy- 71%

