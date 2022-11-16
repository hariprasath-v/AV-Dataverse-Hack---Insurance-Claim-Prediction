# AV-Dataverse-Hack---Insurance-Claim-Prediction


### Competition hosted on <a href="https://datahack.analyticsvidhya.com/contest/dataverse/#ProblemStatement">Analyticsvidhya</a>

# About

### Create a machine learning model to predict if the policyholder will file a claim in the next 6 months or not based on the set of car and policy features.

### Final Competition score is 0.1749408983

### Leaderboard Rank is 38

### Evaluation Metric is F1-score.

### File information
 
 * av-dataverse-hack-insurance-claim-prediction-eda.ipynb [![Open in Kaggle](https://img.shields.io/static/v1?label=&message=Open%20in%20Kaggle&labelColor=grey&color=blue&logo=kaggle)](https://www.kaggle.com/hari141v/av-dataverse-hack-insurance-claim-prediction-eda)
    #### Basic Exploratory Data Analysis
    #### Packages Used,
        * seaborn
        * Pandas
        * Numpy
        * Matplotlib
* av-dataverse-hack-insurance-claim-prediction-model.ipynb [![Open in Kaggle](https://img.shields.io/static/v1?label=&message=Open%20in%20Kaggle&labelColor=grey&color=blue&logo=kaggle)](https://www.kaggle.com/hari141v/av-dataverse-hack-insurance-claim-prediction-model)
    #### Data Pre-processing and model. 
    #### Packages Used,
        * Sklearn
        * Pandas
        * Numpy
        * Matplotlib
        * shap
     #### Created Random forest classifier model and evaluated with f1-score. 
     #### [For more detailed information about the model.](https://github.com/hariprasath-v/AV-Dataverse-Hack---Insurance-Claim-Prediction/blob/main/Approach_AV%20Dataverse%20Hack%20-%20Insurance%20Claim%20Prediction.pdf)
     

### Random Forest Model Feature Importances
![Alt text](https://github.com/hariprasath-v/AV-Dataverse-Hack---Insurance-Claim-Prediction/blob/main/Model%20Visualization/Randomforest%20model%20-%20top%2010%20feature%20importances.png)

### Random Forest Model - SHAP Feature Importances
![Alt text](https://github.com/hariprasath-v/AV-Dataverse-Hack---Insurance-Claim-Prediction/blob/main/Model%20Visualization/Randomforest%20model%20-%20SHAP%20top%2010%20feature%20importances.png)

### SHAP Top feature influences the class 0
![Alt text](https://github.com/hariprasath-v/AV-Dataverse-Hack---Insurance-Claim-Prediction/blob/main/Model%20Visualization/Randomforest%20model%20-%20SHAP%20Top%20feature%20influences%20the%20class%200.png)

### SHAP Top feature influences the class 1
![Alt text](https://github.com/hariprasath-v/AV-Dataverse-Hack---Insurance-Claim-Prediction/blob/main/Model%20Visualization/Randomforest%20model%20-%20SHAP%20Top%20feature%20influences%20the%20class%201.png)

### Threshold Tuning Results - Optimal threshold: 0.0745, F1-score: 0.16929
![Alt text](https://github.com/hariprasath-v/AV-Dataverse-Hack---Insurance-Claim-Prediction/blob/main/Model%20Visualization/Probability%20Threshold%20Tuning%20-%20Optimal%20threshold%200.0745%2C%20F1-score%20%200.16929.png)
