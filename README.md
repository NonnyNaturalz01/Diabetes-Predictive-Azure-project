**<h1>Diabetes Prediction Model - Azure ML Studio </h1>** <br>

<b><u>Summary</U></b> <br>
This project uses Azure Machine Learning Studio to develop a complete machine learning solution for diabetes prediction.
The approach, which is implemented as a flexible cloud service for real-time inference, uses clinical data to predict diabetes 
risk with high accuracy.
<br>
<br>
<b><u>Business Value</u></b>
- Early Detection: Finds people who are at risk before they exhibit clinical symptoms.
- Resource optimization: makes it possible to implement focused screening and intervention initiatives.
<br>
<h2><b>Data</b></h2>
<h3>Source</h3>

<h3>Description</h3>
- number of rows: 768<br>
- number of cols: 9<br>
- Key Features: Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age <br>
- Target Variable: Outcome 
<br>
<h3>Preprocessing</h3>
Removed Outliers
<br>
<h3>Model Used</h3>
<br>
Support Vector Machine
<br>
<br>

<h2>Results</h2>
<b>Evaluation Metric</b>
<br>
Accuracy Score: 79%<br><br>

<b>Confusion Matrix </b> <br>
- True Negative = 139 <br>
- True Positive = 20 <br>
- False Negative = 57 <br>
- False Positive = 14 <br>
... on a 0.5 threshold.
<br>
<b>ROC Plot Curve </b><br>
<img width="338" height="310" alt="image" src="https://github.com/user-attachments/assets/1e6c3a49-9ddd-4506-a8a7-2917c29b9c90" />

<b> Precision-Recall Curve</b>
<br>
<img width="322" height="311" alt="image" src="https://github.com/user-attachments/assets/f58472d5-94d8-4a69-8235-e09ee2d04bee" />



