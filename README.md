# Towards-Global-Aerobic-Activity-Monitoring with PySpark

## Dataset
https://archive.ics.uci.edu/ml/datasets/PAMAP2+Physical+Activity+Monitoring

## Objective
Application of classification algorithms to raw data of the time series and to some high level features (frequency features) extracted from the raw data for human activity recognition, as suggested by the papers:

* https://ieeexplore.ieee.org/document/6246152 (in **relevant papers** of the UCI dataset link)
* https://www.researchgate.net/publication/221410580_Towards_global_aerobic_activity_monitoring (cited by the first one)

relying on PySpark and HDFS.

## Setup
The experiment is setup on a hdfs cluster with 3 nodes:
* node-master
* node1
* node2

and Spark relying on the data stored in the HDFS.
The experiment is also performed on a single node.
