# BlocPower Demo
This demo involves modeling energy usage for buildings in NYC.

## Highlights
### Data Import and Exploration

- Create Spark DataFrames from imported CSV files
- Run some data exploration commands to inspect the data
- Define functions to clean and prepare the data for modeling

### Model Creation

- Create a model using sklearn
- Visualize the model accuracy
- Detect buildings that consume energy inefficiently

## Project-Specific Information
### Tools Used

- Python, through Jupyter Notebooks
- Spark DataFrames
- Scikit Learn for model creation

### Model Information

**Linear Regression**

- Response variable is energy usage in kWh
- Features include age of the building, square feet, number of stories, total plugged equipment, etc.

**Unsupervised Learning**

- Perform PCA and Clustering
- Metrics used: plugged-in equipment, air conditioning, domestic gas, heating gas
- Visualize clusters using two out of four dimensions and K-means to determine center locations

**Classification using Logistic Regression**

- Model used to identify inefficient buildings
- Visualize accuracy using a confusion matrix

### Relevant Files

**Notebooks**

- `BlocPower.ipynb`

**Data Assets**

- `BlocPower_T.csv`
- `CDD-HDD-Features.csv`
- `HDD-Features.csv` 
