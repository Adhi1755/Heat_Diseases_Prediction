# Heart Disease Prediction Project

## Heart Disease Prediction using Machine Learning

### Problem:
Heart disease is one of the leading causes of death worldwide. Early detection of heart disease can help in reducing mortality rates and improving patient outcomes. The aim of this project is to build a machine learning model that predicts the likelihood of a person having heart disease based on various health indicators.

### Solution:
The project uses machine learning techniques to classify whether a patient is at risk of heart disease based on input medical data. Various models are trained and evaluated to determine the best-performing algorithm.

### Data Information:
The dataset used for this project contains multiple attributes related to patient demographics, medical history, and physical examination data. The key features in the dataset include:

1. **age** - age in years
2. **sex** - (1 = male; 0 = female)
3. **cp** - chest pain type
    * 0: Typical angina: chest pain related decrease blood supply to the heart
    * 1: Atypical angina: chest pain not related to heart
    * 2: Non-anginal pain: typically esophageal spasms (non heart related)
    * 3: Asymptomatic: chest pain not showing signs of disease
4. **trestbps** - resting blood pressure (in mm Hg on admission to the hospital) anything above 130-140 is typically cause for concern
5. **chol** - serum cholestoral in mg/dl
6. **serum** = LDL + HDL + .2 * triglycerides (above 200 is cause for concern)
7. **fbs** - (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)'>126' mg/dL signals diabetes
8. **restecg** - resting electrocardiographic results
     * 0: Nothing to note
     * 1: ST-T Wave abnormality can range from mild symptoms to severe problems signals non-normal heart beat
     * 2: Possible or definite left ventricular hypertrophy Enlarged heart's main pumping chamber
9. **thalach** - maximum heart rate achieved
10. **exang** - exercise induced angina (1 = yes; 0 = no)
11. **oldpeak** - ST depression induced by exercise relative to rest looks at stress of heart during excercise unhealthy heart will stress more
12. **slope** - the slope of the peak exercise ST segment
     0: Upsloping: better heart rate with excercise (uncommon)
     1: Flatsloping: minimal change (typical healthy heart)
     2: Downslopins: signs of unhealthy heart
     ca - number of major vessels (0-3) colored by flourosopy colored vessel means the doctor can see the blood passing through the more blood movement the better (no clots)
13. **thal** - thalium stress result
     1,3: normal
     6: fixed defect: used to be defect but ok now
     7: reversable defect: no proper blood movement when excercising
14. **target** - have disease or not (1=yes, 0=no) (= the predicted attribute)


### Libraries Used:
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computations
- **Matplotlib** - Data visualization
- **Seaborn** - Advanced data visualization
- **Scikit-Learn** - Machine learning modeling

### Project Workflow:
1. **Importing the required libraries**
2. **Loading and understanding the dataset**
3. **Exploratory Data Analysis (EDA)**
   - Handling missing values
   - Checking data distribution
   - Identifying correlations
4. **Data Preprocessing**
   - Normalization and standardization
   - Encoding categorical variables
   - Splitting the dataset into training and testing sets
5. **Model Training and Evaluation**
   - Training multiple machine learning models (Logistic Regression, Decision Tree, Random Forest, etc.)
   - Evaluating model performance using accuracy, precision, recall, and F1-score
   - Plotting confusion matrix
   - Hyperparameter tuning to optimize model performance
6. **Predictions and Final Analysis**

### Results and Conclusion:
The model with the best performance is selected based on evaluation metrics. The findings of the project highlight the significant risk factors contributing to heart disease and demonstrate how machine learning can aid in early diagnosis and prevention.

### Future Scope:
- Implementation of deep learning techniques for better accuracy
- Incorporating real-time patient monitoring data
- Deploying the model as a web or mobile application for accessibility

---

This project demonstrates the potential of machine learning in healthcare, particularly in predicting heart disease risks, which can help in preventive care and early treatment.

