# Mercado_libre_trend_analysis-forecast

The application utilizes fb prophet to analyze large sets of data, identify unusual patterns and generate model forecast. The program starts by importing data (csv file) for which it provides time series analysis and pattern visualizations. Subsequently, it incorporates a second set of data to locate correlations using lagged time techniques. Finally, a times series model generates seasonality and predictions useful for business practices such as marketing, production, and sale forecast. 

#Installations and imports

pip install pystan
pip install fbprophet
pip install hvplot
pip install holoviews


import pandas as pd
import holoviews as hv
from fbprophet import Prophet
import hvplot.pandas
import datetime as dt
%matplotlib inline
import numpy as np

#Contributors

Javier Leon
