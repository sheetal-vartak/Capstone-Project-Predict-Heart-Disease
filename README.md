# Capstone Project Predict Heart Disease

## Project Description
Cardiovascular diseases (CVDs) are the number 1 cause of death globally, taking an estimated 17.9 million lives each year, which accounts for 31% of all deaths worldwide. Four out of 5 CVD deaths are due to heart attacks and strokes, and one-third of these deaths occur prematurely in people under 70 years of age. Heart failure is a common event caused by CVDs and this dataset contains 11 features that can be used to predict a possible heart disease.

People with cardiovascular disease or who are at high cardiovascular risk (due to the presence of one or more risk factors such as hypertension, diabetes, hyperlipidaemia or already established disease) need early detection and management wherein a machine learning model can be of great help.

(source - https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction/data)

 

## Data Source
https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction/data

 

## Techniques to be used
* LogisticRegression
* LR L1 (Lasso)
* LR L2 (Ridge)
* Random Forest
* SVM
 

## Expected Results
The expectation is to find the features that negatively and positively affect the probability of Heart Disease as well as detect heart disease as accurately as possible.

 

## Why is this important
Currently, the treatments and detection are all reactive. 

* Patients are treated AFTER the heart attacks occur
* Emergency room visits cost 50x more than prevention
* Higher mortality rates 
* Family trauma and reduced quality of life for the patient
* Healthcare system cannot scale

Issues related to undetected heart disease :

* Silent progression of disease goes undetected
* Risk factors compound over time without intervention
* Patients develop complications that could be prevented
* Healthcare providers lack tools for early identification

  
All of the above can be avoided if we can detect heart disease sooner.

## Cardiovascular Disease prediction project summary

### ✅ Deliverables completed:

1. Data Analysis and exploration
   * Comprehensive EDA with 918 patient records
   * Data quality assessment and visualization
   * Correlation analysis and feature relationships

3. Data processing
   * Handled missing values (173 missing entries)
   * Encoded categorical variables (5 features)
   * Feature standardization for optimal model performance

4. Logistic Regression Model   
   * Achieved 84.8% accuracy on test set
   * ROC-AUC: 0.899 indicating good discrimination
   * Cross-validation confirmed model stability

5. Comprehensive evaluation
   
   * Multiple performance metrics calculated
   * Confusion matrix analysis
   * ROC curve visualization
   * 5-fold cross-validation

6. Model interpretation
    
   * Identified key cardiovascular risk factors
   * Clinical significance of coefficients
   * Odds ratio calculations for clinical understanding

7. Multiple Model Comparison
    
   * Compared 5 different algorithms
   * L1/L2 regularization evaluation
   * Random Forest and SVM comparison
   * Best model: Random Forest (AUC: 0.923)

### 🏥 Clinical applications:

* Early detection screening tool
* Risk stratification for preventive care
* Decision support for healthcare providers
* Population health management

### 📊 Key Insights:
* Model can reliably identify high-risk patients
* ST Slope and Chest Pain Type are strongest predictors
* Exercise-induced symptoms highly predictive
* Age and sex remain significant factors

### 🔬 Future Enhancements:
* Collect additional lifestyle factors
* Implement ensemble methods
* Deploy as web application
* Continuous model monitoring and updates



