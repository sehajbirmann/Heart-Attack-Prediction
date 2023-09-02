# Heart Attack Prediction

## Introduction
This README provides an overview of an ML project for heart disease prediction, along with key information on its attributes and the machine learning model used for prediction. The dataset contains information from includes four databases: Cleveland, Hungary, Switzerland, and Long Beach V. It consists of 76 attributes, but all published experiments refer to using a subset of 14 of them. The primary target attribute is "target," which indicates the presence of heart disease in the patient. It is an integer value where 0 represents no disease and 1 represents the presence of disease.

## Methodology

![image](https://github.com/sehajbirmann/Heart-Attack-Prediction/assets/72991473/7164fb1c-6310-4d25-91c3-514d9d300451)

### 1. Data Collection

The data used in this project was obtained from four different databases: Cleveland, Hungary, Switzerland, and Long Beach V. These databases contain a total of 76 attributes, including the predicted attribute, which is the presence of heart disease in patients. The target variable is binary, with 0 indicating no disease and 1 indicating the presence of heart disease.

### 2. Data Pre-processing

The dataset underwent data pre-processing before model training. This pre-processing step involved cleaning the data, handling missing values, and ensuring data consistency. Additionally, feature selection was performed to use a subset of 14 relevant attributes for training and testing. This subset was chosen based on previous experiments.

### 3. Model Training

The machine learning model selected for this project is logistic regression, a binary classification algorithm. The training data, consisting of the selected features and target variable, were used to train the logistic regression model. During training, the model learned the relationships between the input features and the presence or absence of heart disease.

### 4. Model Testing

After training, the logistic regression model was tested using a separate dataset to evaluate its performance. The testing dataset was split from the original dataset, ensuring that it was not used during the training phase. The model's predictions were compared to the actual target values in the testing dataset to assess its accuracy which came to about 85%.

### 5. Result Analysis

The results of the model testing phase were analyzed to determine the accuracy of the logistic regression model in predicting heart disease. The accuracy metric provided insights into the model's performance, and it was found to be 82%. This analysis helped validate the effectiveness of the machine learning model in predicting heart disease based on the selected features.

## Description

### Dataset Source
The dataset used in this project dates back to 1988 and comprises data from four databases: Cleveland, Hungary, Switzerland, and Long Beach V. It contains 76 attributes, but our analysis focused on a subset of 14 attributes. The primary target attribute is "target," which indicates the presence of heart disease in patients. A value of 0 represents no disease, while 1 indicates the presence of disease.

### Significance
Predicting heart disease is of paramount importance in healthcare. Early detection can lead to timely interventions and improved patient outcomes. This projectserves as a valuable resource for building predictive models to assist medical professionals in identifying individuals at risk of heart disease.

### Background
Understanding the context of this dataset is crucial. Cardiovascular diseases are a leading cause of death worldwide. By leveraging machine learning to predict heart disease, we aim to contribute to early diagnosis and prevention.

## Input / Output

### Input Data
For model training, users need to provide data in a structured format. The input data should include the following attributes:

- `age`: Age of the patient.
- `sex`: Gender of the patient (0 = female, 1 = male).
- `chest pain type`: Type of chest pain (encoded as categorical values).
- `resting blood pressure`: Resting blood pressure of the patient.
- `serum cholestoral`: Serum cholesterol level in mg/dl.
- `fasting blood sugar`: Fasting blood sugar level > 120 mg/dl.
- `resting electrocardiographic results`: Results of resting electrocardiogram (values 0, 1, 2).
- `maximum heart rate achieved`: Maximum heart rate achieved during exercise.
- `exercise induced angina`: Presence of exercise-induced angina.
- `oldpeak`: ST depression induced by exercise relative to rest.
- `slope of the peak exercise ST segment`: The slope of the peak exercise ST segment.
- `number of major vessels`: Number of major vessels colored by fluoroscopy (0-3).
- `thal`: Thalassemia type (0 = normal; 1 = fixed defect; 2 = reversible defect).

### Output
The model generates predictions in the form of binary values:
- 0: No heart disease detected.
- 1: Heart disease detected.

## Live Link

A live version of this heart disease prediction system is available for interactive use. You can access it here -> [Google_Colaboratory_Link](https://colab.research.google.com/drive/1Q2ioXVZ3SUF2fxXMwqzv1ePMEU-8OUOP?usp=drive_link).



