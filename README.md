# arima-sarima-flight-prediction
# ARIMA and SARIMA Model for Flight Passenger Prediction

This repository contains a mini project on the application of ARIMA (AutoRegressive Integrated Moving Average) and SARIMA (Seasonal AutoRegressive Integrated Moving Average) models to predict the number of passengers on a flight from 1949 to 1960. The project aims to forecast the future passenger count based on historical data and seasonal patterns.

## Dataset

The dataset used in this project contains monthly passenger counts on a flight from January 1949 to December 1960. The data is stored in a CSV file and includes a time series with the number of passengers as the target variable and the corresponding dates as the index.

## Requirements

Before running the code, ensure you have the following libraries installed:

- Python (>=3.6)
- Pandas
- NumPy
- Matplotlib
- Statsmodels

You can install these dependencies using pip:

```
pip install pandas numpy matplotlib statsmodels
```

## Project Structure

The repository is organized as follows:

- `data/`: Contains the dataset file (`flight_passengers.csv`).
- `notebooks/`: Jupyter notebooks used for data analysis, model development, and visualization.
- `src/`: Python scripts for implementing the ARIMA and SARIMA models.
- `results/`: Plots and visualizations generated during the project.

## Getting Started

To run the project and see the results, follow these steps:

1. Clone the repository to your local machine using the command:
   ```
   git clone https://github.com/Abhay14tyagi/arima-sarima-flight-prediction.git
   ```

2. Navigate to the project directory:
   ```
   cd arima-sarima-flight-prediction
   ```

3. Run the Jupyter notebooks in the `notebooks/` directory to explore the dataset, analyze the time series, and develop the ARIMA and SARIMA models.

4. Execute the Python scripts in the `src/` directory to apply the trained models on new data or perform forecast.

5. The generated visualizations and plots will be saved in the `results/` directory.

## Model Evaluation

The ARIMA and SARIMA models are evaluated based on various metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE). The evaluation results can be found in the Jupyter notebooks and may be further analyzed and interpreted.

## Contributing

If you would like to contribute to this project or make improvements, please feel free to create a pull request. We welcome your ideas, bug fixes, and feature enhancements.

## Acknowledgments

Special thanks to the authors and maintainers of the libraries used in this project. Their contributions have been instrumental in making this project possible.

Please feel free to contact us if you have any questions or suggestions related to this project. Happy forecasting!

[Abhay Tyagi](https://github.com/Abhay14tyagi)

**Note**: Replace "your-username" with your GitHub username and update the `Your Name` section with your actual name or preferred display name. Also, feel free to add any additional sections or information that you think would be useful for users exploring your project on GitHub.
