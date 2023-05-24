## Exploring Diabetes

### Dataset Overview

The data is a part of `Pima Indians Diabetes Database` dataset, a popular dataset, related to diabetes. It is used in machine learning and data mining demonstrations.<br/>

`Each row represents a medical case, and each column represents a different feature or characteristic of the case:`

#### Feature Descriptions

```md
Pregnancies: Number of times the individual has been pregnant.
Glucose: Plasma glucose concentration over 2 hours in an oral glucose tolerance test.
BloodPressure: Diastolic blood pressure (mm Hg).
SkinThickness: Triceps skin fold thickness (mm).
Insulin: 2-Hour serum insulin (mu U/ml).
BMI: Body mass index (weight in kg/(height in m)^2).
DiabetesPedigreeFunction: Diabetes pedigree function, a function which scores likelihood of diabetes based on family history.
Age: Age (years).
```

```python
# BMI Formula: BMI = weight (kg) / (height (m) ^ 2)

weight_kg = 70  # Weight in kilograms
height_m = 1.75  # Height in meters

bmi = weight_kg / (height_m ** 2)
bmi
```

<br/>

**Outcome:** Class variable (0 or 1), where '1' denotes the patient has diabetes and '0' denotes they do not.<br/>

<br/>

`The data includes five cases, or rows. For each case, It has aforementioned characteristics. For instance, the first patient has had 6 pregnancies, a glucose level of 148, blood pressure of 72, skin thickness of 35, an insulin level of 0, BMI of 33.6, Diabetes Pedigree Function of 0.627, age of 50, and has diabetes (since the outcome is 1).`

[Diabetes Prediction using Machine Learning with Python](https://youtu.be/xUE7SjVx9bQ?list=PLfFghEzKVmjvuSA67LszN1dZ-Dd_pkus6)
