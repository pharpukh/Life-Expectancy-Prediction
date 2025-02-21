# Regression Task - Life Expectancy Prediction

## Overview
This project is a university assignment focused on solving a **regression problem** using various models, including a custom implementation of **Random Forest Regression**, **Linear Regression**, and another model of choice. The task involves **data preprocessing, feature transformation, handling missing values, model training, evaluation, and prediction**. The dataset contains life expectancy and related features for different countries over various years.

## Dataset
The project uses two datasets:
- **Training Data (`data.csv`)** – Used for model training and validation.
- **Evaluation Data (`evaluation.csv`)** – Used for generating predictions.

### Features
- `Year` - The year of the data record.
- `Status` - Classification as **Developed** or **Developing** country.
- `Life expectancy` - The target variable to predict.
- `Adult Mortality`, `Infant Deaths`, `Alcohol Consumption`, `GDP`, `Schooling`, and many other health and economic indicators.

The complete list of features is available in the `homework description`.

## Project Structure
```
├── homework_02.ipynb    # Jupyter Notebook containing the full solution
├── data.csv             # Training dataset (if available)
├── evaluation.csv       # Evaluation dataset (if available)
├── results.csv          # Model predictions on evaluation data
├── README.md            # Project documentation
```

## Requirements
To run this project, you need:
- Python 3.x
- Jupyter Notebook
- Required libraries:
  ```sh
  pip install numpy pandas matplotlib seaborn scikit-learn
  ```

## How to Run
1. **Download the datasets**: Ensure `data.csv` and `evaluation.csv` are in the project directory.
2. **Open Jupyter Notebook**:
   ```sh
   jupyter notebook
   ```
3. **Run `homework_02.ipynb`** step by step, following the provided explanations.
4. **Check `results.csv`**: This file will contain the final predictions after running the notebook.

## Evaluation Metrics
The models are evaluated using:
- **Root Mean Squared Error (RMSE)**
- **Mean Absolute Error (MAE)**

## Notes
- The `Random Forest` model is implemented from scratch.
- Feature engineering and hyperparameter tuning are included.
- Missing values are handled carefully to avoid data leakage.

## Author
Farukh Rustamov

