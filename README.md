Hey there! We're diving into an exciting project focused on creating a super-smart predictive model to evaluate credit risk. Through the magic of machine learning, our goal is to predict how creditworthy applicants are based on their personal data and past credit records. This project isn't just about numbers; it's about using technology to make better decisions and reduce risks in the lending world. By blending data science with financial know-how, we're on a mission to shake up the traditional credit assessment process and bring in more accurate and efficient ways to evaluate credit. 
Objective: The objective of the project is to build a BEST model WITH MAXIMUM ACCURACY that predicts whether an individual is eligible for Credit Card Approval or not.

OVERVIEW:
- Banking / Financial Institutions play a significant role in providing financial services.
- To maintain the integrity, banks/institutions must be careful when investing in customers to avoid financial loss.
- Before giving credit to borrowers, the bank must come to know about the potential of customers.
- The term credit scoring determines the relation between defaulters and loan characteristics.

APPROACH DESIGN:
- Preparation of data
- Applying models
- Comparing the applied models
- Evaluation of models
- Analyze the best model

DATASETS OVERVIEW:
- Application Table
Contains applicant-level personal and demographic information.
- ID – Unique identifier for each applicant (primary key).
- AMT_INCOME_TOTAL – Total annual income of the applicant.
- OCCUPATION – Applicant’s occupation type or profession.
- OWN_HOUSE – Indicates if the applicant owns a house/apartment (Yes/No or 1/0).
- OWN_CAR – Indicates if the applicant owns a car (Yes/No or 1/0).
- DAYS_EMPLOYED – Number of days the applicant has been employed (negative values may represent time before application).
- DOB – Date of Birth of the applicant (used to calculate age).
- WORK_PHONE – Indicates if the applicant has a work phone number (Yes/No or 1/0).
- FAM_MEMBERS – Number of family members dependent on the applicant.

-Credit Table
Contains applicant’s credit-related history data.
- ID – Unique identifier linking back to the applicant in the Application table (foreign key).
- MONTHS_BALANCE – Month of the credit record relative to the application date (e.g., -1 is last month, -2 is two months before, etc.).
- STATUS – Credit status code for that month (e.g., 0 = no DPD, 1+ = days past due, C = closed, X = no loan for the month).

<img width="506" height="213" alt="image" src="https://github.com/user-attachments/assets/527dcc89-69ce-413c-b5f4-4be1534825f5" />

CLASSIFICATION MODELS APPLIED ON THE DATA:
- LOGISTIC REGRESSION
- SUPPORT VECTOR MACHINES
- DECISION TREE CLASSIFIER
- RANDOM FOREST CLASSIFIER


CONFUSION MATRIX OF LOGISTIC REGRESSION:
- <img width="200" height="158" alt="image" src="https://github.com/user-attachments/assets/12836707-61df-4318-8933-4ec6d1a5f181" />


CONFUSION MATRIX OF SUPPORT VECTOR MACHINES:
- <img width="201" height="159" alt="image" src="https://github.com/user-attachments/assets/83d21e38-7511-4e25-a53a-b46b9e497e60" />


CONFUSION MATRIX OF DECISION TREE CLASSIFIER:
- <img width="201" height="157" alt="image" src="https://github.com/user-attachments/assets/61f774a2-6734-4347-8431-9bcf84830b51" />


CONFUSION MATRIX OF RANDOM FOREST CLASSIFIER:
- <img width="189" height="147" alt="image" src="https://github.com/user-attachments/assets/4556e8c5-dbc7-49c5-8b00-a7789542cdd9" />

CONCLUSION:
In conclusion, with a remarkable accuracy of 97%, the Random Forest algorithm outperformed Logistic Regression, Support Vector Machines, and Decision Trees for predicting credit card approval outcomes. Therefore, we've chosen Random Forest as our model of choice, poised to enhance credit evaluation accuracy and streamline the approval process for financial institutions.
