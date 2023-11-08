## project-4
# MediSmart Futures: Sharp Health Predictions

Welcome to our innovative health prediction project, ["MediSmart Futures: Sharp Health Predictions"]. We're dedicated to leveraging advanced technology and data analytics to forecast heart, liver, and diabetes conditions. Our mission is to empower individuals with early insights and personalized guidance for a healthier tomorrow.
Our goal is to develop and implement predictive models that enable early detection and proactive management of heart, liver, and diabetes conditions. We aim to provide individuals with accurate risk assessments, personalized health recommendations, and the knowledge they need to make informed decisions, ultimately improving their overall well-being and quality of life.





![Alt text](Analytics-Medical-IoT-1600x900.jpeg)

# Dashboard
Dashboard created using The visualisation is to include a Python Flask-powered API, HTML/CSS, Javascript and  database (SQL, MongoDB, SQLite)to configure some of the attributes of the application. From Application configuration objects store metadata for an application.

![Alt text](<Screenshot 2023-11-08 154154.png>)

## Project Overview

The project's scope is to provide a valuable tool for General Practitioners (GPs) in Australia. It involves developing a comprehensive healthcare prediction system that assists GPs in early detection and severity assessment of heart, liver, and diabetes conditions. The system offers personalized health recommendations and facilitates referrals to specialists when required. The project aims to empower GPs with data-driven insights, aiding in more informed decision-making and enhancing patient care. By enabling GPs to catch conditions early and offer proactive management, the project can improve patient outcomes and reduce healthcare costs, ultimately benefiting both GPs and their patients.

This task requires the group to work cohesively to tell a story using a range of data extraction and visualisation tools.

# Requirements

# Data Model Implementation 

   * A Python script initialises, trains, and evaluates a model.

   * The data is cleaned, normalised, and standardised prior to modelling.

   * The model utilises data retrieved from SQL or Spark.

   * The model demonstrates meaningful predictive power at least 75% classification accuracy or 0.80 R-squared. 

# Data Model Optimisation 

   * The model optimisation and evaluation process showing iterative changes made to the model and the resulting changes in model performance is documented in either a CSV/Excel table or in the Python script itself.

   * Overall model performance is printed or displayed at the end of the script.

# GitHub Documentation

   * GitHub repository is free of unnecessary files and folders and has an appropriate .gitignore in use.

   * The README is customised as a polished presentation of the content of the project.

# Group Presentation 

   * All group members speak during the presentation. 

   *  Content, transitions, and conclusions flow smoothly within any time restrictions.

    * The content is relevant to the project.

    * The presentation maintains audience interest.

## File structure

    * Images: contains images of the plots and background for readme file.

    * Notebook: contains Ds_Store, diabetes_prediction.ipynb, heart_prediction.ipnyb,Liver_prediction.ipynb

    * Resources: Contains raw data, cleaned CSV data files and SQLite Database.

    * Templetes: style.css ,disease.html,health_info.html,home.html,insurance.html Interactive Dashboard files.

    * js:javascript

    * README.md: README file, you're already here!

# Tools
    Pandas
    Python
    Flask API
    SQLite
    D3 Library
    Javascript
    HTML/CSS
    Tensflow
    Logistic regression
    keras for importing pickle
    json
    Neural networks

## Project details

# Findings and Summary
In summary, we have successfully fulfilled the project's initial objectives, which included developing predictive models and designing a user-friendly front-end interface for general physicians to assess disease probabilities in patients. Nevertheless, given the project's medical nature, the utmost importance lies in achieving a high degree of accuracy and precision in disease prediction. To this end, we propose the following strategic actions to further enhance the accuracy.

# Resources and Acknowledgements

# Source of datasets: 

 https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset

 "In our project, we embark on an in-depth analysis of a diabetes prediction dataset. Our journey begins with data ingestion and visual exploration to unveil intricate feature correlations. We then focus on feature scaling for consistent data treatment.The heart of our analysis lies in the creation of a logistic regression model, rigorously evaluated to assess its predictive accuracy. Notably, we address class imbalance concerns through expertly applied random oversampling, enhancing model performance.
## Data Exploration and Visualization:
   * This stage involves loading the diabetes prediction dataset and visually exploring its characteristics, including correlations between features.
## Feature Scaling and Data Preparation:
   * Feature scaling is applied to ensure uniform data treatment, enhancing model performance. The dataset is carefully prepared for modeling.
## Model Construction and Evaluation:
   * A logistic regression model is meticulously crafted, followed by rigorous evaluation to assess its predictive accuracy.
## Addressing Class Imbalance:
   * Recognizing the presence of class imbalance in the dataset, this phase employs random oversampling to rectify the issue, ultimately improving model reliability.
## Resampling and Performance Assessment:
   * After resampling, data is re-scaled for integrity. The model is then re-evaluated, with its performance post-resampling meticulously assessed.


 https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction

 "Our project is a comprehensive machine learning endeavor focused on predicting heart disease. We embark on this journey by meticulously preparing our data, uncovering insights through thoughtful exploration and compelling visualization. With the power of Keras, we craft a neural network model designed to unveil patterns in the data. Our dataset is cleaned, and categorical variables are artfully transformed. We divide our data into training and testing sets, ensuring a well-balanced model. As we scale the data, our neural network takes shape, learning from the training data. In the end, we evaluate our model using a confusion matrix, showcasing its predictive prowess. We also illuminate the path for future predictions, demonstrating the importance of data standardization and model scaling. The result? A powerful tool for heart disease prediction, ready to make an impact.“

## Data Preprocessing and Exploration:
  * Data is loaded and explored.
  * Missing values are checked and summary statistics are calculated.
## Correlation Analysis:
  * Correlations between features are visualized using a heatmap.
## Data Visualization:
  * Scatter plots and pair plots are used to examine relationships between features and heart disease.
  * A box plot shows age distributions based on heart disease status.
## Model Building and Training:
  * A neural network model is constructed and trained.
## Model Evaluation and Deployment:
  * The model is evaluated with a confusion matrix.
  * The trained model and scaler are saved for future predictions.


 https://www.kaggle.com/datasets/abhi8923shriv/liver-disease-patient-dataset

 liver disease prediction model using a liver dataset. It commences with meticulous data exploration, addressing missing values, and encoding categorical features for model readiness. Engaging visualizations offer insights into the data's intricacies. A correlation heatmap highlights relationships between age and bilirubin levels. The dataset is thoughtfully divided into training and testing sets, followed by feature scaling for consistent data treatment. A neural network model is crafted using TensorFlow's Keras API, featuring hidden layers with ReLU activation. Model performance is evaluated on the test set, emphasizing its predictive accuracy. This project underscores the significance of data preprocessing and neural network modeling for precise liver disease prediction.
## Data Acquisition and Inspection:
  * The project initiates with data acquisition, loading data from a liver dataset.
  * It includes an initial inspection of data, checking for missing values, and tail data exploration.
## Data Preprocessing and Encoding:
  *  Missing data is addressed, and categorical variables like 'Gender of the patient' and 'Result' are one-hot encoded for   model readiness.
## Insightful Data Visualization:
  *  Visualizations provide insights into data quality, featuring missing value visualizations and pie charts for gender distribution.
  *  Histograms offer a deeper understanding of feature distributions concerning liver disease outcomes.
## Correlation Analysis:
  *  A correlation heatmap explores the relationship between age and total bilirubin levels, unveiling potential connections.
## Model Development and Evaluation:
  *  A neural network model is created using TensorFlow's Keras API with hidden layers featuring ReLU activation functions.
  *  The model is compiled and evaluated for its predictive accuracy on the test dataset.








    




