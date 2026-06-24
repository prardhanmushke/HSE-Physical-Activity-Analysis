#HSE Physical Activity Analysis

​This repository contains the code and methodology for the MSc Data Science project: Predicting Physical Activity Levels Using Machine Learning.

​#Project Summary

This research investigates whether physiological and lifestyle factors (such as BMI and sedentary time) are stronger predictors of exercise habits than traditional socio-demographic indicators, utilizing the Health Survey for England (HSE) 2022 dataset.

​The project evaluates and compares three distinct machine learning architectures:
​1.LightGBM: The champion model, optimized for categorical survey data.
2.​Random Forest: An ensemble baseline for comparative performance.
3.​Multi-Layer Perceptron (MLP): A deep learning architecture used to explore complex, non-linear relationships.

​#Key Technical Features
​Dual-Stream Preprocessing: A custom pipeline routing raw categorical features to tree-based models and scaled continuous features to neural networks.
​Target Engineering: A composite target variable created by aggregating moderate, vigorous, and walking activity metrics.
​Interactive Deployment: An ipywidgets interface allowing for real-time model inference based on hypothetical patient physiological metrics.

​#Dataset Attribution
This project utilizes the Health Survey for England (HSE) 2022 (Study Number: 9469).
​Official Data Access: UK Data Service - Study 9469 (https://datacatalogue.ukdataservice.ac.uk/studies/study/9469).
