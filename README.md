# Heart Disease Prediction and Analysis
![Heart Disease Prediction](image.jpg)

## Overview
This repository contains a project focused on heart disease prediction. The data, derived from heart patients, includes various health metrics such as age, blood pressure, heart rate, and more. The primary objective is to create a predictive model that accurately identifies individuals at risk of heart disease. The emphasis is on achieving a high recall to ensure no potential heart disease case is missed.

## Problem
In this project, we delve into a dataset encapsulating various health metrics from heart patients, including age, blood pressure, heart rate, and more. Our goal is to develop a predictive model capable of accurately identifying individuals with heart disease. Given the grave implications of missing a positive diagnosis, our primary emphasis is on ensuring that the model identifies all potential patients, making recall for the positive class a crucial metric.

## Objectives
The objectives of the project are as follows:

1. **Data Understanding**: Familiarize ourselves with the dataset and its features.
2. **Exploratory Data Analysis (EDA)**: Unveil patterns, trends, and relationships between different variables.
   - Univariate Analysis
   - Bivariate Analysis
3. **Data Preprocessing**: Prepare the data for future machine learning tasks.
   - Remove irrelevant features
   - Address missing values
   - Treat outliers
   - Encode categorical variables
   - Transform skewed features to achieve normal-like distributions
4. **Model Building**: Develop and refine the prediction models.
   - Establish pipelines for models that require scaling
   - Implement and tune classification models including KNN, SVM, Decision Tree, and Random Forest
   - Emphasize achieving high recall for class 1, ensuring comprehensive identification of heart patients
5. **Evaluate and Compare Model Performance**: Utilize precision, recall, and F1-score to gauge models' effectiveness.

## Dataset
The dataset comprises various metrics related to heart health. The features of the dataset are described in the table below:

<div align="center">
<table style="width:100%">
<thead>
<tr>
<th style="text-align:center; font-weight: bold; font-size:20px">Variable Name</th>
<th style="text-align:center; font-weight: bold; font-size:20px">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td><b><center>age</center></b></td>
<td>Age of the patient in years</td>
</tr>
<tr>
<td><b><center>sex</center></b></td>
<td>Gender of the patient (0 = male, 1 = female)</td>
</tr>
<tr>
<td><b><center>cp</center></b></td>
<td>Chest pain type: <br> 0: Typical angina <br> 1: Atypical angina <br> 2: Non-anginal pain <br> 3: Asymptomatic</td>
</tr>
<tr>
<td><b><center>trestbps</center></b></td>
<td>Resting blood pressure in mm Hg</td>
</tr>
<tr>
<td><b><center>chol</center></b></td>
<td>Serum cholesterol in mg/dl</td>
</tr>
<tr>
<td><b><center>fbs</center></b></td>
<td>Fasting blood sugar level, categorized as above 120 mg/dl (1 = true, 0 = false)</td>
</tr>
<tr>
<td><b><center>restecg</center></b></td>
<td>Resting electrocardiographic results: <br> 0: Normal <br> 1: Having ST-T wave abnormality <br> 2: Showing probable or definite left ventricular hypertrophy</td>
</tr>
<tr>
<td><b><center>thalach</center></b></td>
<td>Maximum heart rate achieved during a stress test</td>
</tr>
<tr>
<td><b><center>exang</center></b></td>
<td>Exercise-induced angina (1 = yes, 0 = no)</td>
</tr>
<tr>
<td><b><center>oldpeak</center></b></td>
<td>ST depression induced by exercise relative to rest</td>
</tr>
<tr>
<td><b><center>slope</center></b></td>
<td>Slope of the peak exercise ST segment: <br> 0: Upsloping <br> 1: Flat <br> 2: Downsloping</td>
</tr>
<tr>
<td><b><center>ca</center></b></td>
<td>Number of major vessels (0-4) colored by fluoroscopy</td>
</tr>
<tr>
<td><b><center>thal</center></b></td>
<td>Thalium stress test result: <br> 0: Normal <br> 1: Fixed defect <br> 2: Reversible defect <br> 3: Not described</td>
</tr>
<tr>
<td><b><center>target</center></b></td>
<td>Heart disease status (0 = no disease, 1 = presence of disease)</td>
</tr>
</tbody>
</table>
</div>
<br>

You can find the dataset [here](heart.csv).

## File Descriptions
- `Heart Disease Prediction.ipynb`: Jupyter notebook containing all the data exploration, visualization, modeling, and evaluation code.
- `heart.csv`: CSV file containing the heart disease data.
- `README.md`: This file, providing an overview of the project.

## How to Run
- Clone this repository.
- Open the `Heart Disease Prediction.ipynb` notebook in Jupyter.
- Run all cells in the notebook.

## Additional Resources
For those interested in exploring this notebook in a Kaggle environment, you can access it [here](https://www.kaggle.com/code/farzadnekouei/heart-disease-prediction).
