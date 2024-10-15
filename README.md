# Telco-Data-Analysis
Telco Customer Service Data Analysis
### Dataset Description

The Telco Customer Churn dataset captures key attributes related to customers of a telecommunications company. It provides insights into customer demographics, service usage, and billing information. This dataset can be used to analyze customer behavior, predict churn rates, and develop targeted marketing strategies aimed at improving customer retention.

### Dataset Features

<details>
  <summary>See Features</summary>
  
  - **CustomerID**:
    - A unique identifier for each customer in the dataset. This helps in tracking individual customer data.

- **Gender**:
  - The gender of the customer. Typically represented as categories (e.g., "Male", "Female"). This information can be used to analyze trends and behaviors based on gender.

- **SeniorCitizen**:
  - A binary indicator (0 or 1) indicating whether the customer is a senior citizen.
    - **1**: Senior citizen (usually 65 years or older)
    - **0**: Not a senior citizen.

- **Partner**:
  - A binary indicator that shows whether the customer has a partner.
    - **Yes**: Customer has a partner.
    - **No**: Customer does not have a partner.

- **Dependents**:
  - A binary indicator that shows whether the customer has dependents (e.g., children or others relying on them).
    - **Yes**: Customer has dependents.
    - **No**: Customer does not have dependents.

- **Tenure**:
  - The number of months the customer has been with the company. This indicates customer loyalty and the length of the relationship.

- **PhoneService**:
  - A binary indicator of whether the customer subscribes to phone service.
    - **Yes**: Customer has a phone service.
    - **No**: Customer does not have a phone service.

- **MultipleLines**:
  - Indicates whether the customer has multiple lines for their phone service.
    - **Yes**: Customer has multiple phone lines.
    - **No**: Customer does not have multiple lines.

- **InternetService**:
  - The type of internet service the customer subscribes to. Categories may include:
    - **DSL**: Digital Subscriber Line.
    - **Fiber optic**: High-speed internet.
    - **No**: Customer does not have internet service.

- **OnlineSecurity**:
  - Indicates whether the customer has an online security feature included in their plan.
    - **Yes**: Customer has online security.
    - **No**: Customer does not have online security.

- **OnlineBackup**:
  - Indicates whether the customer has an online backup feature included in their plan.
    - **Yes**: Customer has online backup.
    - **No**: Customer does not have online backup.

- **DeviceProtection**:
  - Indicates whether the customer has device protection (e.g., insurance for devices).
    - **Yes**: Customer has device protection.
    - **No**: Customer does not have device protection.

- **TechSupport**:
  - Indicates whether the customer has tech support included in their service plan.
    - **Yes**: Customer has tech support.
    - **No**: Customer does not have tech support.

- **StreamingTV**:
  - Indicates whether the customer subscribes to a streaming TV service.
    - **Yes**: Customer has streaming TV.
    - **No**: Customer does not have streaming TV.

- **StreamingMovies**:
  - Indicates whether the customer subscribes to a streaming movies service.
    - **Yes**: Customer has streaming movies.
    - **No**: Customer does not have streaming movies.

- **Contract**:
  - The type of contract the customer has with the company. Categories may include:
    - **Month-to-month**: No long-term commitment.
    - **One year**: A one-year contract.
    - **Two year**: A two-year contract.

- **PaperlessBilling**:
  - A binary indicator of whether the customer opts for paperless billing.
    - **Yes**: Customer uses paperless billing.
    - **No**: Customer receives paper bills.

- **PaymentMethod**:
  - The method by which the customer pays for their service. Common methods may include:
    - **Credit card (automatic)**: Automatic payments via credit card.
    - **Bank transfer (automatic)**: Automatic payments via bank transfer.
    - **Mailed check**: Payments made by mailing a check.
    - **Electronic check**: Payments made via electronic check.

- **MonthlyCharges**:
  - The amount the customer is charged monthly for their service. This can vary based on the plan and additional features selected.

- **TotalCharges**:
  - The total amount billed to the customer. It reflects the cumulative charges over the customer's tenure with the company.

- **Churn**:
  - A binary indicator that shows whether the customer has churned (i.e., discontinued service).
    - **Yes**: Customer has churned. (1)
    - **No**: Customer is still active. (0)

</details>


### EDA


***Descriptive Statistics***
- Dataset:
  - 7043 Entries

- Gender Split:
  - Male: 50.47% (3555)
  - Female: 49.53% (3488)

- Senior Citizen Split:
  - Senior Citizen: 16.21% (1142)
  - Non-Senior Citizen: 83.78% (5901)

- Partner Split:
  - Yes (they have a partner): 48.30% (3402)
  - No (they do not have a partner): 51.69% (3641)

- Monthly Cost
  - Average monthly cost: $64.76
  - Standard deviation from mean: $30.09
  - Maximum monthly cost: $118.75
  - Minimum monthly cost: $18.25