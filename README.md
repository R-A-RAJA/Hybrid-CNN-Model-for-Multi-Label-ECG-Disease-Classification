Hybrid CNN Model for Multi-Label ECG Disease Classification

  This project presents a hybrid deep learning and machine learning approach to classify cardiovascular diseases from 12-lead ECG images. It leverages an optimized CNN model for feature extraction and multiple ML classifiers to improve classification accuracy across four ECG categories.

Project Overview

Goal: Accurately classify 12-lead ECG images into:
    
    Normal
    
    Abnormal
    
    Myocardial Infarction (MI)
    
    History of MI (HMI)

Approach:

  A Convolutional Neural Network (CNN) is used to extract deep features from ECG images.

  Extracted features are then passed to various machine learning classifiers for final prediction.

Technologies Used

  Frontend: ReactJS

  Backend: Django (REST Framework)

  ML/DL Libraries:

  TensorFlow / Keras

  Scikit-learn

  LightGBM

  SVM, Random Forest, KNN, XGBoost

  Image Processing: OpenCV, PIL

  Utilities: NumPy, Pandas, Matplotlib, Joblib

Features

  Drag and drop ECG image upload

  Live preview of uploaded ECG

  Instant prediction results via REST API

  Interactive and responsive UI
