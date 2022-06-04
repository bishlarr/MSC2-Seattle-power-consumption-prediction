# MSC2-Seattle-power-consumption-prediction

The project MSC2-Seattle-power-consumption-prediction is a data scientist MSc student project.

The goal is to predict the CO2 emissions and total energy consumption of non-housing buildings for which they have not yet been measured for the city of Seattle.
To do so, we first conduct an analysis in the Study.ipynb, and then process to the modeling part in the Modeling.ipynb.

The input files are not present into the Git. It consists into 2 different files:
  - 2015 building energy benchmarking, 3340 buildings described according to 42 parameters
  - 2016 building energy benchmarking, 3376 buildings described according to 46 parameters

Main librairies:
  - Python scientific libraries
  - Seaborn
  - Missingno
  - Sklearn

Main models:
  - Chi2, f_classif
  - Linear Regression
  - Ridge Regression
  - Lasso Regression
  - SVR
  - Random Forest Regressor
