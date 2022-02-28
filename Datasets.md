# Datasets

The first step in applying machine learning methodologies is finding a rich representative dataset. I have identified a dataset that is optimal for modern ML techniques like ANNs for detecting and diagnosing heart disease. It is based on the [UCI Machine Learning Heart Disease dataset](https://archive.ics.uci.edu/ml/datasets/heart+disease) and is enhanced with patient data from 4 other datasets:

```markdown

1. Cleveland: 303 observations
2. Hungarian: 294 observations
3. Switzerland: 123 observations
4. Long Beach VA: 200 observations
5. Stalog (Heart) Data Set: 270 observations

Hence there are a total of **918** unique observations and **12** common attributes available in this enhanced dataset.

```

## Data Attributes

The **UCI heart disease dataset** contains 75 attributes and during pre-processing, I have selected 12 attributes that will best represent the patients’ health and condition. The attribute values will then be normalized and converted to numerical form. Data quality is an important factor in getting accurate results. Hence data cleaning will involve removing unnecessary or irrelevant attributes from the dataset. This step of the procedure will make the dataset more precise and exact. As part of this step, Null (NaN) values will be removed from the dataset as these values decrease the productivity of the algorithm 


| Attribute     | Description | Value Set |
| ---      | ---       | ---         |
| **Age** |    age of the patient      | [years] |
| **Sex**     | sex of the patient |    [M: Male, F: Female]   |
| **ChestPainType** | chest pain type | [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic] |
| **RestingBP** | resting blood pressure | [mm Hg] |
| **Cholesterol** | serum cholesterol | [mm/dl] |
| **FastingBS** | fasting blood sugar | [1: if FastingBS > 120 mg/dl, 0: otherwise] |
| **RestingECG** | resting electrocardiogram results | [Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria] |
| **MaxHR** | maximum heart rate achieved | [Numeric value between 60 and 202] |
| **ExerciseAngina** | exercise-induced angina | [Y: Yes, N: No] |
| **Oldpeak** | oldpeak = ST | [Numeric value measured in depression] |
| **ST_Slope**| the slope of the peak exercise ST segment | [Up: upsloping, Flat: flat, Down: downsloping] |
| **HeartDisease** | output class | [1: heart disease, 0: Normal] |


## Polynomial Feature Space
This is a technique to alter and enhance the dataset by engineering new features. We create new features transforms by raising input variables to a power. Some machine learning algorithms prefer or perform better with polynomial input features.




