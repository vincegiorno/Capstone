This project attempts to identify significant factors related to low birth weight (LBW) in the United States based on county data contained in countrywide governmental datasets. This information could be useful in targeted interventions aimed at lowering LBW, which leads to developmental problems and additional healtcare costs but is mostly preventable. All the datasets used are in the `/datasets` directory. Related descriptive files and the original dataset files, if these were not in CSV format, are in the `/extra` subdirectory, which contains an `unused` subdirectory that holds files downloded as part of the datasets but not used.

The `capstone.ipynb` file, a Jupyter notebook containing all the project code, will run in a Python 2.7 environment where the following packages are available for import:
+ pandas - *used for general data manipulation*
+ numpy - *used for general math and array handling*
+ seaborn - *used to produce heat map plots (`heatmap`)* 
+ matplotlib - *used for data-distribution and residuals plots*
+ statsmodels - *used to compute VIF scores (`variance_inflation_factor` in the `stats.outliers_influence` module)*
+ sklearn - *used to implement various algorithms and auxiliary functions*

The `report.pdf` file details the project, its implementation and the results.
