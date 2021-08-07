# Heart Disease Prediction

## Project Overview

The goal of this project is to go through the data science lifecycle steps in order to build a heart disease classification web application by using [UCI heart disease](https://archive.ics.uci.edu/ml/datasets/statlog+(heart)) dataset. This project uses Flask API to deploy the model and build the web application.

## Installation 

All libraries are available in Anaconda distribution of Python.

## Dataset
The dataset has 14 attributes:

 - age: age in years.
 - sex: sex (1 = male; 0 = female).
 - cp: chest pain type (Value 0: typical angina; Value 1: atypical angina; Value 2: non-anginal pain; Value 3: asymptomatic).
 - trestbps: resting blood pressure in mm Hg on admission to the hospital.
 - chol: serum cholestoral in mg/dl.
 - fbs: fasting blood sugar > 120 mg/dl (1 = true; 0 = false).
 - restecg: resting electrocardiographic results (Value 0: normal; Value 1: having ST-T wave abnormality; Value 2: probable or definite left ventricular hypertrophy).
 - thalach: maximum heart rate achieved.
 - exang: exercise induced angina (1 = yes; 0 = no).
 - oldpeak: ST depression induced by exercise relative to rest.
 - slope: the slope of the peak exercise ST segment (Value 0: upsloping; Value 1: flat; Value 2: downsloping).
 - ca: number of major vessels (0-3) colored by flourosopy.
 - thal: thalassemia (3 = normal; 6 = fixed defect; 7 = reversable defect).
 - target: heart disease (1 = no, 2 = yes).


## File Descriptions 

- `data.csv`: the dataset file.
- `Heart_Disease_Classification.ipynb`: contains the code of data exploration, preparation and modeling. 
- `model.pkl`: the classification model. 
- `heart_disease_app.py`: Flask API that bind between the classification model and the web page. 
- templates:
	- `Heart Disease Classifier.html`: a web page that contains a form for heart disease testing. 
	






