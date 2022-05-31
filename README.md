# btc-time-series

This is a Jupyter Notebook .ipynb file for practing multiple ways to do time-series forecasting on Bitcoin.  Jupyter is a great tool for data analysis using the Python language.  

If you are new to programming you will first need to setup your computer's enviornment by downloading Python 3.9.7.

Check that it was properly installed by typing in the terminal:
$ python -v
This should output "3.9.7"

Next, install Jupyter with the "pip" command:
$ pip install notebook

Then once you have Jupyter installed start it with:
$ jupyter notebook

Once open you can use your browser to navigate your file system and use notebooks that end in .ipynb

You will also need to obtain Bitcoin price data from Coinbase to follow the examples.  In this notebook we are using a .csv file named "coinbaseUSD_1-min_data_2014-12-01_to_2018-11-11.csv", so you can either edit the code to match your preferred dates, or you can chose to download the 1minute data from 12/01/14-11/11/2018 in order to follow along and get the models up and running.

This notebook uses many python libraries, that you may need to install first with either pip or conda including:
datetime
matplotlib
numpy
seaborn
pytz
pandas
plotly
keras
sklearn
fbprophet
xgboost
scipy
itertools
