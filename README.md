
# Forecasting Net Prophet


This application analyzes user data for the MercadoLibre, an e-commerce site in Latin America, and makes predictions for future search engine traffic. 

---

## Technologies

This prodject uses Python 3.7 with the following packages:
* ### **Faceboook Prophet** - A forecasting procedure for time series data
* ### **pandas** - A package of intuitive data analysis tools
* ### **hvplot** - Creates static plots with feetures like hovering, zooming, and scanning
* ### **holoviews** - Extensive visualization gallery
* ### **pystan** - A platform for statistical modeling and computations

---

## Installation Guide

First, install the following:
    
    pip install pystan
    conda install -c conda-forge fbprophet -y
    
To run the application start by importing and installing the following:  
    
    conda list hvplot
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
    
Then import the following libraries and extensions:  

    import pandas as pd
    import holoviews as hv
    from fbprophet import Prophet
    import hvplot.pandas
    import datetime as dt
    %matplotlib inline
    import hvplot.pandas
    import holoviews as hv
    def _render(self, **kw):
     hv.extension('bokeh')
     return hv.Store.render(self)
    hv.core.Dimensioned._repr_mimebundle_ = _render
---

## Usage


* ### In Google Colab imported CSV file
* ### Compare monthly median trends to monthly trends and use hyplot to visualize trends
* ### Analyze the date for seasonal affects using a heatmap and grouping the data by weeks and hours
* ### Investigate and calculate the the correlation bewteen the search trends data and stock prices of the company 
* ### Using Prophet create a time series model to predict the future search traffic trends  


---

## Contributors

A.Nansamba Ssensalo
[LinkedIn](www.linkedin.com/in/a-nansamba-ssensalo)

---

## License

[![License](https://img.shields.io/badge/License-Boost%201.0-lightblue.svg)](https://www.boost.org/LICENSE_1_0.txt)
