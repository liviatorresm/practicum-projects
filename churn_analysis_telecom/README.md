## Data

| Variable          | Description                                           |
|-------------------|-------------------------------------------------------|
| customerID        | Unique identifier encoded for each customer           |
| BeginDate         | Contract start date                                   |
| EndDate           | Whether the customer canceled the contract or not. Two types of observations:<br>'No' - corresponds to customers who stayed with an active contract<br>Date - the date when the customer left the company |
| Type              | Contract type:<br>Month-to-month - Monthly payment<br>One year - 1-year contract<br>Two year - 2-year contract |
| PaperlessBilling  | Whether the customer has paperless billing            |
| PaymentMethod     | Payment method:<br>Electronic check<br>Mailed check<br>Bank transfer (automatic)<br>Credit card (automatic) |
| MonthlyCharges    | Monthly charge amount                                |
| TotalCharges      | Total amount paid for the service                     |
| gender            | Gender (Female or Male)                               |
| SeniorCitizen     | Whether the customer is a senior citizen              |
| Partner           | Whether the customer has a partner                    |
| Dependents        | Whether the customer has dependents                   |
| InternetService   | Type of internet service:<br>DSL - Digital Subscriber Line<br>Fiber optic cable |
| OnlineSecurity    | Online security (antivirus software)                  |
| OnlineBackup      | Online file storage and data backup                   |
| DeviceProtection  | Device protection (malicious site blocker)            |
| TechSupport       | Dedicated technical support                          |
| StreamingTV       | TV streaming                                         |
| StreamingMovies   | Access to a directory of movies                       |
| MultipleLines     | Whether the landline plan allows multiple lines at the same time |

## Goal

To predict customer churn in order to implement customer retention strategies.

## Libraries used:
* pandas
* numpy
* scikit-learn
* matplotlib
* seaborn
* regex
* scipy
* sklearn
* xgboost
* catboost
* tqdm
* shap
* imblearn