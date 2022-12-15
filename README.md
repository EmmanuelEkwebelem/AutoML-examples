# HHA 507 - Assignment # 9

This repository represents the completion of HHA 504 Assignment # 9

Instructions:

Create a new github repo called 'AutoML examples' 

Select a dataset of your own choosing (or select my modified version of SPARCS - https://raw.githubusercontent.com/hantswilliams/HHA-507-2022/main/autoML/datasets/data_sparcs.csv) 

Create two 'experiments' using the autoML package mljar-supervised 
- One that is focused around classification (binary or multi-class outcome variable)
- One that is focused around regression (continuous outcome variable) 

Include the output of the mljar-supervised output folder inside of the github repo (e.g., so there should be 2 folders - one for classification and one for regression) 

## Outcomes:

### Experiment 1: Multiclass Variable 

Dependent Variable: Risk of Mortality 

Best Model: Ensemble 
- Metric_Type: logloss
- Metric_Value: 0.50403
- Train_Time: 0.33

Comparison: 
- Performed significantly worse to Baseline

### Experiment 2: Continuous Variable 

Dependent Variable: Risk of Mortality 

Best Model: Ensemble 
- Metric_Type: rmse
- Metric_Value: 32770.9
- Train_Time: 0.19

Comparison: 
- Performed considerable worse to Baseline 
