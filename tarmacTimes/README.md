# Modeling Tarmac Times
This is a demo of the `R Notebook` functionality within DSX.

## Highlights
### Data Exploration and Visualization

- Create histograms and scatterplots on total aircraft taxi time
- Color code histogram by `UniqueCarrier`

### Create Frequency Tables

- Frequency of departing and arriving flights by airport
- Mean taxi times by airport

### Create Linear Regression model

- Model mean taxi depending on frequency of departing and arriving flights.


## Project-Specific Information
### Tools Used

- R Notebook
- `data.table` library
- `ggplot2` plotting library

### Model Information

**Linear Regression**

- Response variable is `meanTaxi`
- Only feature is `freq`

### Relevant Files

**Notebooks**

- `MachineLearning_CPLEX.ipynb`

**Data Assets**

- `2016.csv`
- `2016_airport_freq.csv`
