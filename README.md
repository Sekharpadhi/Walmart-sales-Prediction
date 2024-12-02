# Walmart Sales Forecasting

This project analyzes Walmart sales data to identify trends, seasonality, and factors influencing sales performance. It then uses predictive modeling techniques, specifically ARIMA and SARIMAX, to forecast sales for individual stores over the next 12 weeks.

## Project Goals

* **Exploratory Data Analysis (EDA):** Understand the dataset, identify trends, and uncover relationships between variables like unemployment rate, CPI, temperature, and weekly sales.
* **Sales Forecasting:** Build predictive models to forecast weekly sales for individual stores over the next 12 weeks.
* **Store Performance Analysis:** Identify top and bottom performing stores and quantify the significance of the difference in their performance.

## Key Findings

* **Seasonal Trends:** Weekly sales show a seasonal trend, with higher sales during colder months and lower sales during warmer months, inversely correlating with temperature.
* **Unemployment Impact:** Sales are generally higher when unemployment rates are between 6 and 10, and lower when unemployment rates are outside this range.
* **CPI Influence:** Weekly sales tend to decrease as the Consumer Price Index (CPI) increases.
* **Top and Bottom Performers:** Store performance varies significantly, with Stores 1, 2, 4, 10, 13, 14, 20, and 27 being among the top performers, while Stores 3, 5, 12, 28, 33, 36, 38, and 44 are among the bottom performers.

## Predictive Modeling

* **ARIMA and SARIMAX:** Time series models (ARIMA and SARIMAX) are used to forecast sales for individual stores, leveraging historical data and identified patterns.
* **Hidden Seasonality:** SARIMAX models are employed to address potential hidden seasonality and improve forecast accuracy.

## Data

* The project uses the 'Walmart.csv' dataset containing historical sales data for multiple Walmart stores.

## Libraries

* pandas
* numpy
* matplotlib
* seaborn
* statsmodels
* pmdarima
* scikit-learn

## Usage

1. Clone the repository.
2. Install the required libraries.
3. Run the Jupyter Notebook to perform the analysis and generate forecasts.

## Contributing

Contributions are welcome! Please open an issue or pull request to suggest improvements or add features.

## License

This project is licensed under the MIT License.
