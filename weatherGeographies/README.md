# Weather Geographies Demo
We build a model to predict `TMAX` (temperature maximum) based on geographic coordinates

## Highlights
### Data Exploration

- Examine the data, and the schema

### Model Creation

- Split the data into training, validation, and test
- Validate model hyperparameter (`n_estimators`)
- Test model and produce mean absolute deviation

### Model Visualization

- Use the model to predict a set of lat/lon/elevations
- Produce a map output

### Model Conversion

- Convert the model to core ml
- Save the model

## Project-Specific Information
### Tools Used

- Python, through Jupyter Notebooks
- Matplotlib visualization

### Model Information

- Gradient Boosting Regressor
- Response variable is `TMAX`
- Features are `latitude`, `longitude`, and `elevation`

### Relevant Files

**Notebooks**

- `WeatherGeographies_CoreML.ipynb` - trains the initial model

**Data Assets**

- `seasonal_data.csv` - Weather data for 4 seasonal days
- `elevation.csv` - 181x180 matrix for elevations by lat/lon