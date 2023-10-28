# TOC Prediction in Well Logging using ML and DL Models

## Author

Cuong Hai Bach
AGH University of Science and Technology
Email: bachhaicuong110@gmail.com

## Overview

This repository explores the application of machine learning (ML) and deep learning (DL) models for predicting Total Organic Carbon (TOC) in well logging. The project utilizes Multiple Linear Regression (MLR), Support Vector Machine for regression (SVR), and Convolutional Neural Network (CNN) models, comparing their performances on a small well log dataset.

## Dataset

The dataset consists of 35 laboratory measurements of TOC and related values from well logging curves in Silurian and Ordovician shales. Models are trained and evaluated on this dataset to predict TOC.

## Results

MLR and CNN models show signs of overfitting, performing well on training sets but poorly on test sets.
The SVR model with an RBF kernel demonstrates robustness and does not overfit.
Data distribution reveals two classes of datapoints with low and high TOC values.

## Conclusions

Deep Learning CNN models may not be optimal for small datasets due to inherent characteristics.
Both CNN and traditional models provide general outcomes aligned with geological data references.
Further research is recommended for improving pre-processing methods to enhance model accuracy and stability.

## References

Elkatatny, S. A Self-Adaptive Artificial Neural Network Technique to Predict Total Organic Carbon (TOC) Based on Well Logs. Arab J Sci Eng 44, 6127–6137 (2019).
Mahmoud A.; Elkatatny S.; Ali A.; Abdulraheem A.; Abouelresh M., 2020, Estimation of the Total Organic Carbon Using Functional Neural Networks and Support Vector Machine, International Petroleum Technology Conference.
Ross, D.J., Bustin, R.M., 2007. Impact of mass balance calculations on adsorption capacities in microporous shale gas reservoirs. Fuel 86 (17), 2696–2706.
