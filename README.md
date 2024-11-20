# CNN-Melanoma-Detection-Assignment

> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
- [Problem Statement](#problem-statement)
- [Project Pipeline](#project-pipeline)
- [Conclusions](#Conclusion)
- [Technologies Used](#technologies-used)
- [Acknowledgements](#acknowledgements)



## Problem Statement

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases:

Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion


## Project Pipeline

- Data Reading/Data Understanding
Dataset Creation
Dataset visualisation
Model Building & training
Chose an appropriate data augmentation strategy to resolve underfitting/overfitting
Model Building & training on the augmented data
Class distribution
Handling class imbalances
Model Building & training on the rectified class imbalance data


## Conclusion:

-	We are required to build a multiclass classification model using a custom convolutional neural network in TensorFlow.
- The problem of overfitting and underfitting was solved and the model was well trained for predictions. Data augmentation, outliers, and class equalization were found to be useful in improving model performance in this case.
-	Predicting a incorrect class of skin cancer


# Technologies Used

- Keras
- TensorFlow
- Python 3
- Pandas, Numpy, Matplotlib,
- Augmentor


# Acknowledgements

- This project was based on tutorial https://learn.upgrad.com/course/5800/segment/55852/333577/1009201/5042348
- Efficient way to build CNN architecture from https://github.com/ContentUpgrad/Convolutional-Neural-Networks/blob/main/Melanoma%20Detection%20Assignment/Starter_code_Assignment_CNN_Skin_Cancer%20(1).ipynb


# Contact

Created by [https://github.com/Yesha711/CNN-Melanoma-Detection-Assignment.git] - feel free to contact me!
