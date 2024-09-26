# Lung cancer prediction and Analysis
## Project  Overview:
This dataset contains 309 records with 16 columns initially.
After removing duplicates, the cleaned dataset consists of 276 rows and 14 columns.
Key features include variables like gender, age, smoking status, anxiety, fatigue, coughing, chest pain, and whether the patient has lung cancer or not.

## Data Source:
- this data is from kaggle.com

## Data Processing:
- The dataset was normalized using MinMaxScaler, and it was split into training and testing sets with an 80-20 split.

## Model Building:[]()
- Three models were built:
- Random Forest (Accuracy: 99.5% on training set, 85.7% on test set)
-	Naive Bayes (Accuracy: 86.8% on training set, 83.9% on test set)
- Logistic Regression (Accuracy: 91.8% on training set, 83.9% on test set)
- Logistic Regression was chosen due to its performance and fit.
  
## Model Evaluation:
- Accuracy scores and confusion matrices were used to evaluate models.
- Cross-validation was also performed using K-Fold (3 and 5 splits), yielding varying but consistent performance.

## Visualization:
-	Several visualizations, including count plots and pie charts, illustrated distributions of lung cancer cases across age, gender, and other factors.
-	Example: 86.2% of patients in this dataset had lung cancer, while 13.8% were lung cancer free.
  ![]()
 	![]()
  
## Conclusion and Benefits:
- Logistic Regression was chosen as the final model, considered to fit well for lung cancer detection.
-	The model aims to assist hospitals or individuals in detecting early-stage lung cancer, potentially preventing worse outcomes.
-	the model will be make work easier for the employees and patient will be attended to quickly
-	if the model were to be deployed to individuals, it will enable individual to quiclky check and monitor their health
  

