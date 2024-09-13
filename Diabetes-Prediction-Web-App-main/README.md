# Welcome to [NareshKumars's](https://github.com/Nare5hkumars/) profile! <a href="https://github.com/Nare5hkumars/"> 

 
<img src="https://camo.githubusercontent.com/2366b34bb903c09617990fb5fff4622f3e941349e846ddb7e73df872a9d21233/68747470733a2f2f63646e2e6472696262626c652e636f6d2f75736572732f3733303730332f73637265656e73686f74732f363538313234332f6176656e746f2e676966" width="25px"></a>

 

### I'm a...   <img src="https://camo.githubusercontent.com/2366b34bb903c09617990fb5fff4622f3e941349e846ddb7e73df872a9d21233/68747470733a2f2f63646e2e6472696262626c652e636f6d2f75736572732f3733303730332f73637265656e73686f74732f363538313234332f6176656e746f2e676966" height=15% width=40% align="right">

 

* Future Web devolper And Datascience Engineer

* Self-directed programmer

* Independent learner

* Demanding Perfectionist

 
🌱 I'm currently learning: Dataset And Algorithms in [Leet Code]<br>

📬 How to reach me: [nareshkumarnkrs@gmail.com](mailto:nareshkumarnkrs@gmail.com)<br>



💪 "Here, I code, write, and tackle challenges.".<br><br>

 As a Information Technology, I enjoy using my obsessive attention to detail, my unequivocal love for making

 things that change the world.

 

 

-------------------------------------------------------------------------------------------------------

### My Skills

<img src="https://img.shields.io/badge/-C-blue?style=for-the-badge&logo=c&logoColor=FFFFFF" height="30"> <img src="https://img.shields.io/badge/-C++-blue?style=for-the-badge&logo=c%2B%2B&logoColor=FFFFFF" height="30"> <img src="http://img.shields.io/badge/-Python-blue?style=for-the-badge&logo=python&logoColor=FFFFFF" height="30"> <img src="https://img.shields.io/badge/-Java-blue?style=for-the-badge&logo=openjdk&logoColor=white" height="30"> <img src="http://img.shields.io/badge/-PHP-blue?style=for-the-badge&logo=php&logoColor=FFFFFF" height="30"> <img src="http://img.shields.io/badge/-Machine%20Learning-blue?style=for-the-badge&logo=machine-learning&logoColor=FFFFFF" height="30"> <img src="http://img.shields.io/badge/-Deep%20Learning-blue?style=for-the-badge&logo=deep-learning&logoColor=FFFFFF" height="30"> <img src="http://img.shields.io/badge/-Computer%20Vision-blue?style=for-the-badge&logo=computer-vision&logoColor=FFFFFF" height="30"> <img src="http://img.shields.io/badge/-MySQL-blue?style=for-the-badge&logo=mysql&logoColor=FFFFFF" height="30">![Canva](https://img.shields.io/badge/Canva-%2300C4CC.svg?style=for-the-badge&logo=Canva&logoColor=white)  ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-%2300000f.svg?style=for-the-badge&logo=mysql&logoColor=white)![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)

 
# Diabetes Predicition Flask WebApp
This repository contains the code for a web-based diabetes prediction application using a machine learning model. The application is built using Flask and allows users to input various health parameters to predict the likelihood of diabetes.<br>



## Overview

The web app utilizes a machine learning model, specifically an ensemble model combining RandomForestClassifier, LogisticRegression, and Support Vector Machine (SVM), to provide predictions. The model was trained on the diabetes dataset from kaggle.

## Requirements

Python: Ensure you have Python 3.6 or later installed. Python is the programming language used to write the application.

Flask: A lightweight web framework for building the web application.

Machine Learning Libraries: Tools for training and using machine learning models.

Web Browser: For accessing and testing the web application.

2. Python Libraries
Create a requirements.txt file to list the necessary Python libraries and their versions. This file helps in managing dependencies and setting up the environment easily. Below is a sample requirements.txt for a Diabetes Prediction Flask WebApp:

plaintext
Copy code
Flask==2.5.2
scikit-learn==1.2.2
pandas==2.0.3
numpy==1.25.0
joblib==1.2.0
Explanation of Each Library:
Flask: A micro web framework for Python. It helps in creating web applications and handling HTTP requests.
scikit-learn: A library for machine learning that includes tools for classification, regression, clustering, and more.
pandas: A data manipulation library that provides data structures and operations for manipulating numerical tables and time series.
numpy: A fundamental package for numerical computations in Python, essential for handling arrays and mathematical operations.
joblib: A library used to serialize and deserialize Python objects, including machine learning models.


## Dataset

<h3>Dataset Preview</h3><a id="3"></a>
A preview of Indians Dataset is as below:

| | Pregnancies | Glucose | BloodPressure | SkinThickness | Insulin |  BMI | DiabetesPedigreeFunction | Age | Outcome |
|-| ----------- | ------- | ------------- | ------------- | ------- | ---- | ------------------------ | --- | ------- |
|0|	          6	|     148 |            72 |            35 |       0 | 33.6 |                    0.627 |  50 |       1 |
|1|	          1	|      85 |            66 |            29 |       0 | 26.6 |                    0.351 |  31 |       0 |
|2|	          8	|     183 |            64 |             0 |       0 | 23.3 |                    0.672 |  32 |       1 |
|3|           1 |      89 |            66 |            23 |      94 | 28.1 |                    0.167 |  21 |       0 |
|4|	          0 |	  137 |            40 |            35 |     168 | 43.1 |                    2.288 |  33 |       1 |
|5|	          5 |	  116 |            74 |             0 |       0 | 25.6 |                    0.201 |  30 |       0 |
|6|	          3 |	   78 |            50 |            32 |      88 | 31.0 |                    0.248 |  26 |       1 |
|7|          10 |     115 |             0 |             0 |       0 | 35.3 |                    0.134 |  29 |       0 |
|8|           2 |     197 |            70 |            45 |     543 | 30.5 |                    0.158 |  53 |       1 |
|9|	          8 |     125 |            96 |             0 |       0 |  0.0 |                    0.232 |  54 |       1 |



<h3>Description of variables in the dataset</h3><a id="4"></a>

```Pregnancies:``` Number of times pregnant

```Glucose:``` Plasma glucose concentration a 2 hours in an oral glucose tolerance test

```BloodPressure:``` Diastolic blood pressure (mm Hg)

```SkinThickness:``` Triceps skin fold thickness (mm)

```Insulin:``` 2-Hour serum insulin (mu U/ml)

## Features

- Users can input their health parameters such as Glucose level, Blood Pressure, Skin Thickness, Insulin level, BMI, Diabetes Pedigree Function (DPF), and Age.
- The ensemble machine learning model predicts the likelihood of diabetes based on the input.
- The app displays the prediction result, indicating whether the user is likely to have diabetes or not.
- Users can receive accurate and quick predictions for early diabetes detection.

## Model

The machine learning model used in this app is an ensemble of RandomForestClassifier, LogisticRegression, and Support Vector Machine (SVM). The ensemble approach combines the strengths of these classifiers to improve prediction accuracy.


<img src="demo.gif" height=50% width=70% align="left"><br>




