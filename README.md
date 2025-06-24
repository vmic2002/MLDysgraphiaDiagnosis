# MLDysgraphiaDiagnosis
## Overview
This repository contains the code and documentation for the "Dysgraphia Detection Through Machine Learning" project, which develops AI-based methods to diagnose dysgraphia using children’s handwriting stroke data collected via tablets. 
The project compares shallow machine learning, deep learning with synthetic data, and K-medoids clustering with dynamic time warping (DTW), extending prior work by Drotár and Dobeš (2020) https://www.nature.com/articles/s41598-020-78611-9.


`dysgraphiaResearchProject.ipynb`: Implements data preprocessing, feature extraction, model training, and evaluation for all approaches (shallow ML, deep ML, clustering).

`dataSciRep_public`: Handwriting stroke data (CSV files with x, y, pen-down status, timestamps, pressure, azimuth, altitude).

`data2_SciRep_pub.xlsx`: Metadata Excel file. Dysgraphia label + sex + hand + age
