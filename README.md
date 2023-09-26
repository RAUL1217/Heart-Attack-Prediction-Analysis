# Heart-Attack-Analysis-Prediction
## Problem Statement : Heart Attack Prediction
## Why this problem : 



## Data Content
* Age: Age of the patient.
* Sex: Sex of the patient.
* exang: exercise induced angina (1 = yes; 0 = no).
* ca: number of major vessels (0-3).
* cp: Chest Pain type.
* Value 0: typical angina.
* Value 1: atypical angina.
* Value 2: non-anginal pain.
* Value 3: asymptomatic.
* trtbps: resting blood pressure (in mm Hg).
* chol: cholestoral in mg/dl fetched via BMI sensor.
* fbs: (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false).
* rest_ecg: resting electrocardiographic results.
* Value 0: normal.
* Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV).
* Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria.
* thalach: maximum heart rate achieved.
* target: 0= less chance of heart attack 1= more chance of heart attack.

## Solution :
* Data Collection and Understanding
* EDA
* Data Balancing
* Outliers Removing
* Feature and Target
* Data Splitting
* Applying models

## EDA
* Pairplot
  ![Screenshot 2023-09-26 111827](https://github.com/RAUL1217/Heart-Attack-Prediction-Analysis/assets/142076300/b0e3c818-be46-41df-98c7-5666c89774d2)
  

* Heatmap
  ![Screenshot 2023-09-26 111827](https://github.com/RAUL1217/Heart-Attack-Prediction-Analysis/assets/142076300/e3accbc7-6c3f-4395-a7bb-0e27583a5509)
  

* Countplot
  ![Screenshot 2023-09-26 115205](https://github.com/RAUL1217/Heart-Attack-Prediction-Analysis/assets/142076300/328f0e29-9e6b-4bc2-b90f-71dbc3806182) 
  ![Screenshot 2023-09-26 112002](https://github.com/RAUL1217/Heart-Attack-Prediction-Analysis/assets/142076300/d09230a1-12e3-4651-a2d1-efb27f6bdf00)
  ![Screenshot 2023-09-26 112032](https://github.com/RAUL1217/Heart-Attack-Prediction-Analysis/assets/142076300/9177e1c5-722b-4062-b85a-e0db7a41a477)
  ![Screenshot 2023-09-26 112052](https://github.com/RAUL1217/Heart-Attack-Prediction-Analysis/assets/142076300/1f2c7cb6-12cd-43b5-9448-c33faec31325)
  ![Screenshot 2023-09-26 112251](https://github.com/RAUL1217/Heart-Attack-Prediction-Analysis/assets/142076300/9ad00b2f-e852-41e5-8e33-d083f6aa8d05)
  ![Screenshot 2023-09-26 112310](https://github.com/RAUL1217/Heart-Attack-Prediction-Analysis/assets/142076300/36af1440-86e4-46f9-9d80-e03970ad74b6)
  ![Screenshot 2023-09-26 112331](https://github.com/RAUL1217/Heart-Attack-Prediction-Analysis/assets/142076300/dd8ee790-74ab-4118-9bdf-14033625ebe8)
  ![Screenshot 2023-09-26 112354](https://github.com/RAUL1217/Heart-Attack-Prediction-Analysis/assets/142076300/32965724-ebc6-46a9-944c-c21596cc056d)
  ![Screenshot 2023-09-26 112413](https://github.com/RAUL1217/Heart-Attack-Prediction-Analysis/assets/142076300/3274dd00-b083-49bd-b161-234544f4c9f2)


* Distplot
  ![Screenshot 2023-09-26 112450](https://github.com/RAUL1217/Heart-Attack-Prediction-Analysis/assets/142076300/757dd0bd-85db-4c83-8eb8-42ad05243cba)
  ![Screenshot 2023-09-26 112508](https://github.com/RAUL1217/Heart-Attack-Prediction-Analysis/assets/142076300/9a5e2562-47ad-4022-afbf-e7fccba2c7c4)
  ![Screenshot 2023-09-26 112526](https://github.com/RAUL1217/Heart-Attack-Prediction-Analysis/assets/142076300/3eab81a7-b2a5-41e1-9ecc-7d2037dd98a9)
  ![Screenshot 2023-09-26 112547](https://github.com/RAUL1217/Heart-Attack-Prediction-Analysis/assets/142076300/40352507-c6e6-4f6c-a002-8b138dfd2759)
  ![Screenshot 2023-09-26 112608](https://github.com/RAUL1217/Heart-Attack-Prediction-Analysis/assets/142076300/dc1772c8-cfa8-463d-8545-f29654fa5fac)

  
* Pie Chart
  ![Screenshot 2023-09-26 112648](https://github.com/RAUL1217/Heart-Attack-Prediction-Analysis/assets/142076300/b55c6bfd-b4e9-4145-bd09-d4410cc7a7e5)



## Models
### We will use the following models :
* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier
* AdaBoost Classifier
* Gradient Boosting Classifier
* SVC

## Accuracy
* Logistic Regression
![Screenshot 2023-09-26 113321](https://github.com/RAUL1217/Heart-Attack-Prediction-Analysis/assets/142076300/72ecd2f2-717e-4c40-9ab8-e62e034f098e)

* Decision Tree Classifier
![Screenshot 2023-09-26 113338](https://github.com/RAUL1217/Heart-Attack-Prediction-Analysis/assets/142076300/dc5498b5-39fb-4102-b257-d237d2739a06)

* Random Forest Classifier
![Screenshot 2023-09-26 113400](https://github.com/RAUL1217/Heart-Attack-Prediction-Analysis/assets/142076300/ae760401-2c66-4fee-b71d-e634706c12ce)

* AdaBoost Classifier
![Screenshot 2023-09-26 113418](https://github.com/RAUL1217/Heart-Attack-Prediction-Analysis/assets/142076300/defb6caa-a9c3-410a-8d8b-77b92a2c5fb3)

* Gradient Boosting Classifier
![Screenshot 2023-09-26 113434](https://github.com/RAUL1217/Heart-Attack-Prediction-Analysis/assets/142076300/2363dd47-dc3e-4a03-abea-31814eb5c1f0)

* SVC
![Screenshot 2023-09-26 113452](https://github.com/RAUL1217/Heart-Attack-Prediction-Analysis/assets/142076300/aba18ae5-953e-4be3-aecc-f51d5da9a26b)






