# Predict Customer Churn
This demo involves predicting customer churn for a telecommunications company.

## Highlights
### Model Creation

- Using Jupyter Notebooks to create and score a model
- Use DSX specific features like asset sharing, collaboration

### Model Deployment

- Save and retrieve models using Cloud Object Storage
- Deploy the final model in a Watson Machine Learning repository

### Application Deployment

- Access deployed model through an API call to WML
- Deploy a web app on Bluemix that uses the accessed model

## Project-Specific Information
### Tools Used

- Python, through Jupyter Notebooks
- Spark, to allow for scaleable modelling through SparkML
- Data Visualization through IBM Pixiedust

### Model Information

- Random Forests Classifier, trained using SparkML pipelines
- Response variable is Customer Churn
- Features include age, income, gender, mobile data usage, payment method, etc.

### Relevant Files

**Notebooks**

- `Predict Customer Churn.ipynb` - trains the initial model
- `Predict Churn - Score New Data.ipynb` - performs testing on unseen data
- `Predict Churn - Deploy to WML.ipynb` - interfaces with Watson Machine Learning to deploy the trained and scored model

**Data Assets**

- `churn.csv` - churn, by customer ID
- `customer.csv` - customer information, including ID
- `customer_churn.csv` - a combined data table with customer information and churn
- `new_customer_churn_data.csv` - unseen data, with only customer information, but no churn value