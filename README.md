# Multi-output-Regression

## Abstract:
To conduct Regression on data from an Electric vehicle with 40 passengers in 10 cities across the United States using the data enclosed in CSV files.

## Understanding the data:
##### 1)  Each drive cycle (6 of them) is a unique independent variable - CBD, Manhattan, New york comp, New york bus, Orange country and UDDS.
##### 2)  Each drive cycle consists of 10 cities with varying temperatures ( each city is an independent variable)
##### 3)  Each city folder consists of two seasons - Summer & Winter - which are unique.
##### 4)  Each seasonal file contains :
##### Degrees
##### Time
##### Speed
##### Energycons  (dependent variable)
##### EProp    (dependent variable)
##### E_Aux    (dependent variable)
##### HVAC    (dependent variable)
##### Power    (dependent variable & is the sum of E-prop,E-Aux & HVAC)
##### Regen    (dependent variable)
##### SoC    (dependent variable)

## Modeling :
##### 1) Applied preprocessing and visualization techniques in order to convert - 10 folders - with 2 subfiles - into one unique readable file.
##### 2) By practising various models which includes - Linear, KNN, Random forest and XGBoost for multi-target regression analysis, recognized that Random forest was the best fit amongst the four with an accuracy rate of 93 - 96%, differing rate amongst 6 drive cycles.
##### 3) Compare and contrast models using the following statistical metrics :
#####  mean_absolute_error
#####  mean_absolute_percentage_error
#####  mean_squared_error &
#####  r2_score
