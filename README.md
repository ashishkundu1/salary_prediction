# Salary Prediction using Linear Regression

## About

This project is based on predicting salary using years of experience. Linear Regression is used to find the relationship between experience and salary and make predictions.

## Dataset

The dataset contains two main columns:

- Years of Experience
- Salary

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Steps

- Load the dataset
- Check and clean the data
- Visualize the data
- Split the data into training and testing sets
- Train the Linear Regression model
- Make salary predictions
- Evaluate the model

## Linear Regression Model

The model parameters obtained are:

- Intercept: 24848.20
- Slope: 9449.96

### Regression Equation

Salary = 9449.96 × Years of Experience + 24848.20

## Model Evaluation

The model was evaluated using MSE and RMSE.

| Metric | Score |
|---|---:|
| Mean Squared Error (MSE) | 31,270,951.72 |
| Root Mean Squared Error (RMSE) | 5,592.04 |

## Result

The model can predict salary based on the number of years of experience. The regression line shows a positive relationship between experience and salary.

## Project Files

- `salary_prediction.ipynb` - Jupyter Notebook containing the complete code
- `Salary_Data.csv` - Dataset used for the project
- `README.md` - Project information

## How to Run

1. Download or clone the repository.
2. Open `salary_prediction.ipynb` in Jupyter Notebook or JupyterLab.
3. Make sure the required Python libraries are installed.
4. Run the cells in the notebook.

## Author

Ashi
