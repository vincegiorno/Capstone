This project attempts to identify predictors of high rates of low birth weight in US counties based on available national data contained in various governmental datasets. These are detailed in the report, with links. All the datasets used are in the `/datasets` directory. Related descriptive files and the original dataset files, if these were not in CSV format, are in the `/extra` subdirectory, which contains an `unused` subdirectory that holds files downloded as part of the datasets but not used.

All the project code in the Jupyter notebook is written in Python 2.7. The following packages are used, and so need to be available in the environment in order to run the code:
+ pandas (general data manipulation)
+ numpy (general math and array handling)
+ seaborn (`heatmap`) 
+ matplotlib (data distribution and residuals plots)
+ statsmodels (`variance_inflation_factor` in `stats.outliers_influence` module)
+ sklearn (various algorithms and auxiliary functions)
