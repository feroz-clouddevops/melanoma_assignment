# Advanced Regression Assignment
> This repository holds code to create a Convolutional Neural Network for  Deep Learning Assignment - Melanoma Detection.


## Table of Contents
* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information
- To build a CNN based model which can accurately detect melanoma. 
- Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. 
- A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Technologies Used
- numpy
- pandas
- matplotlib
- seaborn
- sklearn
- tensorflow
- keras

## Conclusions
1. The jupyter notebook contains the following 3 models:
- A base CNN model used to detect melanoma based on an input image.
- An updated model with manual data augmentation to attempt to address the class imbalance issue.
- A final model with `Augmentor` library to perform augmentation and to resolve the class imbalance problem.

## Notes
- The dataset was uploaded to Google Drive and mounted to the Google Colab Jupyter notebook.