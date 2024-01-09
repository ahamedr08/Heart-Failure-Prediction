![image](https://github.com/ahamedr08/Heart-Failure-Prediction/assets/134275920/be8063b3-cd0d-4b4d-a4f8-7a9ed7a10015)

Aim
The aim of this project is to develop an accurate and reliable predictive model for heart disease detection using various machine learning algorithms. By analyzing a diverse dataset containing medical features, the project aims to identify patterns contributing to the presence or absence of heart disease. The primary goal is to create a model that assists healthcare professionals in making informed decisions based on patient data, leading to early detection and intervention for individuals at risk of heart disease. Ultimately, the project strives to contribute to improved patient outcomes and the prevention of cardiovascular issues through effective machine learning-based prediction.

Background
Cardiovascular diseases (CVDs) are a global health concern, responsible for a significant number of deaths each year. They encompass various conditions that affect the heart and blood vessels, including heart attacks, strokes, and heart failure. CVDs are a leading cause of premature mortality, and their impact is felt worldwide. Many of these deaths are preventable or manageable with early detection and appropriate interventions.

Tool Used
Python

Data Description
The raw dataset used in this project comprises 12 columns, including the target variable, and a total of 918 records.

Attribute Information:
Attribute	Description	Format / Values
Age	Age of the patient	Numeric value in years
Sex	Sex of the patient	M: Male, F: Female
ChestPainType	Chest pain type	TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic
RestingBP	Resting blood pressure	Numeric value in mm Hg
Cholesterol	Serum cholesterol	Numeric value in mg/dl
FastingBS	Fasting blood sugar	1: if FastingBS > 120 mg/dl, 0: otherwise
RestingECG	Resting electrocardiogram results	Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria
MaxHR	Maximum heart rate achieved	Numeric value between 60 and 202
ExerciseAngina	Exercise-induced angina	Y: Yes, N: No
Oldpeak	Oldpeak = ST (Numeric value measured in depression)	Numeric value
ST_Slope	The slope of the peak exercise ST segment	Up: upsloping, Flat: flat, Down: downsloping
HeartDisease	Output class	1: heart disease, 0: Normal
