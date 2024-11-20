# **Heart Disease Prediction**  
This repository contains a machine learning model for predicting the likelihood of heart disease based on various health parameters. The model uses patient data, processes it for feature extraction, and applies  machine learning algorithm to predict outcomes.

## **Overview**  
Heart disease is one of the leading causes of mortality worldwide. Early detection can significantly reduce risks and improve patient outcomes. This project aims to predict heart disease using patient data, helping healthcare professionals make better-informed decisions.

### **Features**  
The dataset includes property attributes such as:  

- Age  
- Sex  
- cptype (Chest Pain Type)  
- rsb (Resting Blood Pressure)  
- serumcholestrol (Serum Cholestoral)  
- fbs (Fast Blood Sugar)  
- restingelectrocardiographicresults (Resting Electrocardiographic results)   
- max_heart_rate (Max Heart Rate Achieved)  
- exerciseinducedangina (Exercise induced angina)  
- oldpeak (ST depression induced by exercise relative to rest)  
- slope (The slope of the peak exercise ST segment)  
- majorvessels (Number of major vessels colored by flourosopy)  
- thal  
  
#### **Approach**
**Data analysis** : Using heatmap to check correaltion between multiple features, Using pie charts to check people diagnosed with heart disease distribution  

**Data Preprocessing** : data had no missing values to be handled  

**Model Selection**: Tested Logistic Regression  

**Model Evaluation:**  
- Accuracy on Training Data: 85.12%  
- Accuracy on Testing Data: 81.96%  

##### **Getting Started** 
Clone the repo and install dependencies.  
