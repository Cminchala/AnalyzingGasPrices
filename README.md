# Gasoline Prices Analysis

This project analyzes and visualizes gasoline prices using various datasets based on different gasoline types and used Different Machine learning models to Predict gas prices . The main analysis is performed in the `notebook.ipynb` file.

## Project Structure

- `notebook.ipynb`: Main Jupyter Notebook containing the analysis and visualizations.
- `average_prices.csv`: CSV file containing average gasoline prices.
- `gas.csv`: CSV file containing gasoline data.
- `Weekly_U.S._All_Grades_All_Formulations_Retail_Gasoline_Prices.csv`: CSV file containing weekly U.S. retail gasoline prices for all grades and formulations.
- `Weekly_U.S._Midgrade_All_Formulations_Retail_Gasoline_Prices.csv`: CSV file containing weekly U.S. retail gasoline prices for midgrade formulations.
- `Weekly_U.S._No_2_Diesel_Retail_Prices.csv`: CSV file containing weekly U.S. retail diesel prices.
- `Weekly_U.S._Premium_All_Formulations_Retail_Gasoline_Prices.csv`: CSV file containing weekly U.S. retail gasoline prices for premium formulations.
- `Weekly_U.S._Regular_All_Formulations_Retail_Gasoline_Prices.csv`: CSV file containing weekly U.S. retail gasoline prices for regular formulations.
- `requirements.txt`: List of Python dependencies required to run the notebook.
- `test.ipynb`: Jupyter Notebook for testing purposes.

## Analysis Overview

The `notebook.ipynb` file performs the following tasks:

1. **Data Loading**: Loads gasoline price data from various CSV files.
2. **Data Visualization**: Plots predictions for different gasoline price categories:
    - `A1` All Grade Gas
    - `M1` MidGrade Gas
    - `R1` Regular Gas
    - `P1` Premium Gas
    - `D1` Diesel Gas
3. **Machine Learning**: Used to Predict Gas Prices for the future 
    - Linear Regression
    - Polynomial Ridge Regression
    - Random Forest Regression
    - Gradiant boosting 
## How to Run

1. Clone the repository.
2. Install the required dependencies using:
    ```sh
    pip install -r requirements.txt
    ```
3. Open `notebook.ipynb` in Jupyter Notebook or JupyterLab.
4. Run the cells to execute the analysis and generate the plots.

## Made By Christian Minchala, Hao Ye , Kevin Heneson
