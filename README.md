# Towards-Global-Aerobic-Activity-Monitoring with Spark

## Dataset
https://archive.ics.uci.edu/ml/datasets/PAMAP2+Physical+Activity+Monitoring

## Objective
Analysis of the difference in performance between the application of classification algorithms directly to the raw data of the time series and to some high level features extracted from the raw data, as suggested by the papers:

* https://ieeexplore.ieee.org/document/6246152 (in **relevant papers** of the UCI dataset link)
* https://www.researchgate.net/publication/221410580_Towards_global_aerobic_activity_monitoring (cited by the first one)

At the beginning the analysis will be performed just relying on the raw data, then some more high level features are extracted both in the time and frequency domains.
In addition, there will be a careful NaNs handling, with the evaluation of some possible alternatives:
* getting rid of every row that has at least one NaN value
* getting rid of the columns with the greatest number of NaN values and then apply the first option
* avoid getting rid of NaN values applying in the pre-processing some forms of predictions for the NaN values filling
