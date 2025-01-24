### Workforce Analysis and Attrition Prediction

The dataset contains 7,043 entries and 21 columns. Key information includes demographic data, service usage details, payment information, and churn status. Here’s a summary:

### Key Columns:
- **customerID**: Unique identifier for each customer.
- **gender**: Customer's gender.
- **SeniorCitizen**: Whether the customer is a senior citizen (1 for Yes, 0 for No).
- **Partner**/**Dependents**: Indicate marital status and whether the customer has dependents.
- **tenure**: Number of months the customer has stayed with the company.
- **PhoneService**/**InternetService**/**MultipleLines**: Service usage details.
- **Contract**: Contract type (e.g., month-to-month, one year).
- **PaperlessBilling**/**PaymentMethod**: Billing preferences.
- **MonthlyCharges**/**TotalCharges**: Payment amounts.
- **Churn**: Target variable (whether the customer left).

### Observations:
1. **TotalCharges** is stored as a string (`object`) but should be numeric for analysis.
2. All other columns seem appropriately typed.
3. The target column for attrition prediction is **Churn**.

