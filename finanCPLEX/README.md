# Machine Learning and CPLEX Demo
This demo involves using machine learning and prescriptive analytics to promote financial products to banking customers.

## Highlights
### Data Exploration and Visualization

- Examine known behavior of customers
- Plot age, income, savings, pension, mortgage plots

### Predict Customer Behavior

- Create a ensemble learning model using sklearn
- Visualize the predicted output

### Compare Optimization Algorithms

- Write a "greedy algorithm" by hand
- Run a CPLEX solver in the cloud to compare revenues


## Project-Specific Information
### Tools Used

- Python, through Jupyter Notebooks
- Scikit Learn for model creation
- matplotlib for plotting
- DOCPLEX for CPLEX in the Cloud

### Model Information

**Gradient Boosting Classifer**

- Response variable is probability of each product
- Features include `age`, `income`, `members_in_household`, `loan_accounts`

### Relevant Files

**Notebooks**

- `MachineLearning_CPLEX.ipynb`

**Data Assets**

- `known_behaviors2.csv`
- `unknown_behaviors.csv`
