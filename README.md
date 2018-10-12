# Floc-Analysis

## Introduction
This repository contains a collection of Jupyter notebooks and pieces of code for processing floc size data. Much of it is aimed at processing the data in light of the time-dependent single-size floc model of Winterwerp (1998) and Kuprenas et al. (2018). You can click on the individual notebooks to see them displayed in the browser, or you can download the repository and run the files on a local computer.

## Description of key repository files
- [01_Winterwerp1998-Model.ipynb][1]: this worksheet gives an overview of the W98 model and can be used to plot the W98 model given user input.
- [02_Winterwerp1998-Model-Fitting.ipynb][2]: this worksheet can be used to determine the aggregation and breakup coefficients, $K_{a}^{'}$ and $K_{b}^{‘}$, that produce the closest fit between the W98 model and observed time series of floc size. These coefficients are specific to a given mud mixture and water column chemistry and organic content. They are the two primary parameters that must be determined to use the W98 model in a prediction of floc size as a function of turbulence and suspended sediment concentration.
- [03_03_KuprenasEtal2018_model_SolvePlot.ipynb][3]: this worksheet gives an overview of the W98 model and can be used to plot the W98 model given user input.
- [04_KuprenasEtal2018_Model_Fitting.ipynb][4]: this worksheet can be used to determine the aggregation and breakup coefficients, $K_{a}^{'}$ and $K_{b}^{‘}$, that produce the closest fit between the Kuprenas et al. 2018 modification to the W98 model and observed time series of floc size. .

## References
Kuprenas, R., D. Tran, and K. Strom. (2018), A shear‐limited flocculation model for dynamically predicting average floc size, Journal of Geophysical Research Oceans, doi: [10.1029/2018JC014154](https://doi.org/10.1029/2018JC014154)
Winterwerp, J. C. (1998). A simple model for turbulence induced flocculation of cohesive sediment. Journal of Hydraulic Research, 36(3):309–326. http://dx.doi.org/10.1080/00221689809498621

[1]:	https://github.com/FlocData/Floc-Analysis/blob/master/Winterwerp1998-Model.ipynb
[2]:	https://github.com/FlocData/Floc-Analysis/blob/master/Winterwerp1998-Model-Fitting.ipynb
[3]:    https://github.com/FlocData/Floc-Analysis/blob/master/03_KuprenasEtal2018_model_SolvePlot.ipynb
[4]:    https://github.com/FlocData/Floc-Analysis/blob/master/04_KuprenasEtal2018_Model_Fitting.ipynb
