# Predicting Forest Fire Severity Using Meteorological and Fire Danger Indices: A Machine Learning Approach

## Aim
The aim of this project is to develop a predictive model for forest fires by analyzing weather and environmental data. The model will forecast the likelihood of fires based on various meteorological variables and indices, enabling better preparedness and mitigation efforts.

## Dataset
The dataset contains 246 records representing different environmental factors recorded over time in a fire-prone region. Key features include:
- **day**: Day of the recording
- **month**: Month of the recording
- **year**: Year of the recording
- **Temperature**: Recorded temperature
- **RH**: Relative Humidity
- **Ws**: Wind Speed
- **Rain**: Rainfall amount
- **FFMC, DMC, DC, ISI**: Fire danger indices
- **Classes**: Fire severity classification (target variable)

## Methodology

1. **Data Preprocessing**:
   - Handle missing values and clean the dataset.
   - Encode categorical variables like day and month.
   - Normalize features where necessary for improved performance.

2. **Exploratory Data Analysis (EDA)**:
   - Analyze the distribution of variables and target classes.
   - Visualize relationships between environmental factors and fire severity.
   - Explore correlations between fire danger indices (FFMC, DMC, DC) and fire incidents.

3. **Model Training**:
   - Split the dataset into training (80%) and testing (20%) sets.
   - Train models such as Random Forest, Decision Tree, and Logistic Regression to predict fire severity.
   - Evaluate the models using metrics like accuracy, precision, recall, and F1-score.

4. **Visualization**:
   - Plot feature importance and correlation heatmaps.
   - Use pair plots to explore patterns across fire severity classes.
   - Display confusion matrices and ROC curves to assess model performance.

5. **Hyperparameter Tuning**:
   - Use GridSearchCV or RandomizedSearchCV to optimize model parameters.
   - Tune parameters like the number of estimators and tree depth in Random Forest.
   - Perform cross-validation to ensure model generalization.

## Exploratory Data Analysis (EDA)
- Descriptive statistics and correlation analysis were conducted to examine variables like temperature, humidity, and wind speed.
- Visualizations included correlation heatmaps, pair plots, and class distribution charts to understand patterns in the data.

## Model Training
- Models such as Random Forest and Decision Tree classifiers were trained on the dataset.
- 80% of the data was used for training and 20% for testing.
- Accuracy, precision, recall, and F1-score were used as performance metrics.

## Hyperparameter Tuning
- GridSearchCV was applied for hyperparameter tuning of the Random Forest model.
- Parameters like the number of trees and maximum depth were optimized to achieve the best results.

## Final Results and Conclusion
- The Random Forest model achieved an accuracy of approximately 85%, making it the best-performing model for predicting fire severity.
- The model demonstrated high precision and recall, proving its effectiveness in forecasting fire occurrences.
- This project concludes that meteorological data and fire danger indices can be used to accurately predict forest fires, aiding in proactive fire management and risk mitigation.

## Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn (for model building and hyperparameter tuning)
- Matplotlib, Seaborn (for visualizations)
- Jupyter Notebook
