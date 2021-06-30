# Abalone Age Prediction
### Predicting the age of Abalones, which is a type of  a snail, from its physical features
<br>
<h2>Problem Statement</h2><br>
The aim of this project is to predicting the age of abalone by analyzing its physical measurements. The age of abalone is equal to 1.5 multiplied by the number of its rings.
<h2>Background</h2><br>
An abalone is type of cold-water marine snail. The age of abalone is determined by cutting the shell through the cone, staining it, and counting the number of rings. Other measurements, which are easier to obtain, are used to predict the age.<br>
<h2>Overview</h2><br>
<br>1. Data Source: UCI Machine Learning Repository
<br>2. Dataset Info: The dataset has 4177 observations and 9 features.It does not have any missing values.
<br>3. Target Variable: Rings or, newly created column derived from Rings called Age.
<br>
<h2>Data Description:</h2><br>

| Name  | Data Type | Description | Measurement | Variable Type |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| Sex  | Categorical | Male, Female and Infant |	M, F, I	| Independent Variable |
| Length  | Numerical  | Longest shell measurement  | mm  | Independent Variable  |
| Diameter |	Numerical |	perpendicular to length |	mm	| Independent Variable |
| Height	| Numerical |	with meat in shell |	mm	| Independent Variable |
| Whole weight |	Numerical |	whole abalone |	grams |	Independent Variable |
| Shucked weight |	Numerical |	weight of meat |	grams |	Independent Variable |
| Viscera weight |	Numerical |	gut weight (after bleeding)	|  grams |	Independent Variable |
| Shell weight |	Numerical |	after being dried |	grams |	Independent Variable |
| Rings |	Numerical |	+1.5 gives the age in years	| years	 | Dependent/Target Variable |

<h2>Problem Approach</h2><br>
The age of abalones can be predicted using Supervised Machine Learning Algorithms. Following the various steps of the data and machine learning pipeline, a candidate algorithm will be selected. The following steps will be conducted:
<br>1. Data Preprocessing and cleaning
<br>2. Exploratory Data Analysis
<br>3. Data Visualization
<br>4. Feature Engineering
<br>5. Candidate Model Research
<br>6. Candidate Model Evaluation
<br>7. Visualization and Inspection of Results.
<br>
<h2>Classification + Regression Approach</h2><br>
This solution can be treated with both regression and classification. We analyze both approaches, and it is to be noted that I strongly prefer a classification approach over a regression approach.
