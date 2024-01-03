# Modelo de Previsão de Retenção de Clientes

O desafio do churn é uma questão recorrente para as empresas de telecomunicações, especialmente em um mercado tão competitivo, onde a alta taxa de troca de serviços entre os clientes é comum. A indústria de telecomunicações investe consideráveis recursos para reduzir o churn. Estudos revelam que os custos associados à aquisição de novos clientes superam os de manter os já existentes. Portanto, é imperativo estar atento e identificar os sinais de alerta de churn para prevenir a saída dos clientes ativos.

Com isso em mente, a operadora de telecomunicações Interconnect gostaria de aprimorar a retenção de clientes e ser capaz de predizer a rotatividade deles, para aplicar estratégias de retenção eficientes.  No âmbito deste projeto, realizei uma análise abrangente dos dados de churn, fornecendo insights acionáveis ao Chief Marketing Officer (CMO). Ao longo dessa análise, concentrei-me em diversos aspectos, abrangendo desde a demografia dos clientes até os padrões de utilização de serviços, com o objetivo de identificar oportunidades significativas para aprimoramentos.

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