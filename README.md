# Module 11 Challenge - Forecasting Net Prophet

---

## Description

In this Jupyter Lab Notebook, we analyze a company's financial and user data to find ways to make the company grow and try and predict successful trading of the stock.   

The sections of this notebook are as follows: 

* Find unusual patterns in hourly Google search traffic

* Mine the search traffic data for seasonality

* Relate the search traffic to stock price patterns

* Create a time series model with Prophet

* Forecast revenue by using time series models

---

## Technologies

This project leverages Google Colab to run a .ipynb notebook.  The following packages are also used: 

* [pandas](https://github.com/pandas-dev/pandas) - Data analysis toolkit for Python.

* [hvPlot](https://github.com/holoviz/hvplot) - A high-level plotting API for the PyData ecosystem built on HoloViews.

* [holoviews](https://github.com/holoviz/holoviews) - Data analysis and visualization tool. 

* [pystan](https://github.com/stan-dev/pystan) - Python interface to Stan, a package for Bayesian inference.

* [fbprophet](https://github.com/facebook/prophet) - Prophet is a procedure for forecasting time series data.

---

## Installation Guide

Before running the application on Google Colab, run the following code to install and import the required librarys:

```python

  # Install the required libraries
from IPython.display import clear_output
try:
  !pip install pystan
  !pip install fbprophet
  !pip install hvplot
  !pip install holoviews
except:
  print("Error installing libraries")
finally:
  clear_output()
  print('Libraries successfully installed')
```
```python

# Import the required libraries and dependencies
import pandas as pd
import holoviews as hv
from fbprophet import Prophet
import hvplot.pandas
import datetime as dt
import numpy as np
%matplotlib inline
```

---

## Contributors

Joshua Creveling

Email: josh.creveling22@gmail.com

GitHub: https://github.com/joshuacreveling

LinkedIn: https://www.linkedin.com/in/joshua-creveling/

*Starter template provided by Trilogy Education Services*

---

## License

MIT