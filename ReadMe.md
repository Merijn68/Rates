# RatesDashboard

RatesDashboard is a Python Demo App showing a use case of Jupyter Dash for visualizing daily market data and managing exceptions.

## Installation

RatesDashboard is written in Jupyter Dash.Files should be installed in the main project directory.
Assets need to be installed. The data directory should at least should contain the rates_data.csv dataset and exceptions.xlsx. You need read/write access to the exceptions.xlsx file where the application stores the suppressed exceptions.

This project uses [JupyterDash](https://medium.com/plotly/introducing-jupyterdash-811f1f57c02e). 

To install JupyterDash:
- conda install -c conda-forge -c plotly jupyter-dash

## Technologies

- Python 3.8.3
- Jupyter Notebooks 6.0.3
- JupiterDash 0.3.1

## Usage

Data used for this project is real life data coming from the banks back office system. As unfortunatly the Market Data is not freely available - market data has been altered on purpose to be distributed with this application.

    RatesDashboard is the main notebook. This contains the code to clean, calcuate and present the results
    CurrencyGroup - is a small python routine to maintain the currency grouping stored in the data folder
    YieldGroup - is a small python routine to maintain the yield grouping stored in the data folder
    LoadDataFromTreasurySystem - This code was used to load the data from the backofficeSystem
    DataManipulation - this file shows the code that was used to change the market data for distribution


## License
[MIT](https://choosealicense.com/licenses/mit/)