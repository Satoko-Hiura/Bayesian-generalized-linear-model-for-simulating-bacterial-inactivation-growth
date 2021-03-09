# Bayesian-generalized-linear-model-for-simulating-bacterial-inactivation-growth

This repository contains code and data related to the following manuscript:
Bayesian generalized linear model for simulating bacterial inactivation/growth considering variability and uncertainty

Software implementation
The calculations are all run inside Google Colaboratory.
Most code used for generating the results and figures in the paper are in the 'code' folder. There are two folder, 'growth' and 'inactivation' in the 'code' folder.
The data used are provided in 'data' folder in the growth and inactivation folder, respectively.
The calculations are run by using the script in the growth folder and inactivation folder in the following procedure.


Inactivation
1. Parameter estimation by bayesian inference
script: 'bayesian_fitting.ipynb'
data: 'bayesian_fitting.csv'


2. Calculating correlation coefficient and figure generation of the result of 
bayesian inference
script: 'bayesian_fitting_result.ipynb'


3. Comparison of the result of parameter estimation by least square method and bayesian inference and figure generation
script: 'fitting_graph.ipynb'
data: 'bayesian_fitting.csv' and 'frequentism_fitting.csv'


4. Prediction of bacterial behavior with small initial cells
average of initial cell number with 8, 90, 850.

(i)8 cell 
'prediction_8cell.ipynb' and '8cell.csv'

(ii) 90 cell
'prediction_90cell.ipynb' and '90cell.csv'

(iii) 850 cell
'prediction_850cell.ipynb' and '850cell.csv'




Growth
1. Parameter estimation by bayesian inference
script: 'bayesian_fitting.ipynb'
data: 'bayesian_fitting.csv'


2. Calculating correlation coefficient and figure generation of the result of 
bayesian inference
script: 'bayesian_fitting_result.ipynb'


3. Comparison of the result of parameter estimation by least square method and bayesian inference and figure generation
script: 'fitting_graph.ipynb'
data: 'bayesian_fitting.csv' and 'frequentism_fitting.csv'


4. Prediction of bacterial behavior with small initial cells
average of initial cell number with 0.3, 2, 24.

(i)0.3 cell
 'prediction_0.3cell.ipynb' and '0.3cell.csv'

(ii)2 cell
 'prediction_2cell.ipynb' and '2cell.csv'

(iii)24 cell
 'prediction_24cell.ipynb' and '24cell.csv'


