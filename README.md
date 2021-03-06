# SG Markets Notebooks

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/sgmarkets/sgmarkets-notebooks/master)

This repo contains a collection of notebooks to help tap SG Market APIs.  
These [Jupyter](http://jupyter.org/) notebooks are meant to be used as inspiration.  

To run them
+ Locally: `git clone` the repo, install the packages in [requirements.txt](requirements.txt) and run `jupyter notebook`.
+ In the cloud: Click on the **Binder** badge above, and go inside the `notebooks/` folder, click on a notebook.  

To browse them
+ [demo_ROTB_vol.ipynb](http://nbviewer.jupyter.org/github/sgmarkets/sgmarkets-notebooks/blob/master/notebooks/demo_ROTB_vol.ipynb)
+ [ROTB_endpoint_strategy_components.ipynb](http://nbviewer.jupyter.org/github/sgmarkets/sgmarkets-notebooks/blob/master/notebooks/ROTB_endpoint_strategy_components.ipynb)
+ [ROTB_endpoint_strategy_prices.ipynb](http://nbviewer.jupyter.org/github/sgmarkets/sgmarkets-notebooks/blob/master/notebooks/ROTB_endpoint_strategy_prices.ipynb)
+ [ROTB_endpoint_strategy.ipynb](http://nbviewer.jupyter.org/github/sgmarkets/sgmarkets-notebooks/blob/master/notebooks/ROTB_endpoint_strategy.ipynb)
+ [equity-availability.ipynb](http://nbviewer.jupyter.org/github/sgmarkets/sgmarkets-notebooks/blob/master/notebooks/equity-availability.ipynb)

It is a work in progress. Notebooks are regularly updated and/or added.  

Here is the list of APIs covered:
+ [ROTB](https://analytics-api.sgmarkets.com/rotb/v1/swagger/ui/index) (Rates Option Trade Builder V1) through module [sgmarkets-api-analytics-rotb](https://gitlab.com/sgmarkets/sgmarkets-api-analytics-rotb)
+ [SFT](https://analytics-api.sgmarkets.com/syntheticfinancingtrading/swagger/ui/index) (Synthetic Financing Trading V1)


It also uses the following common modules
+ Authentication: [sgmarkets-api-auth](https://gitlab.com/sgmarkets/sgmarkets-api-auth)
+ Plot: [sgmarkets-plot](https://gitlab.com/sgmarkets/sgmarkets-plot)
