# CVD-Risk-model

The project aims to create a tool for the early detection and prevention of coronary heart disease (CHD), leveraging machine learning techniques to tackle a critical public health challenge.

# Problem statement 
Cardiovascular diseases (CVDs) are a group of disorders affecting the heart and blood vessels, often leading to serious health complications such as heart attacks and strokes. One of the most common and critical forms of CVD is coronary heart disease (CHD), which arises due to the narrowing or blockage of coronary arteries, primarily caused by atherosclerosis. This condition significantly increases the risk of life-threatening events and poses a major burden on global healthcare systems. 

The importance of early detection and prevention of CHD cannot be overstated. Identifying individuals at risk before the onset of symptoms allows for timely interventions that can mitigate disease progression, reduce healthcare costs, and ultimately save lives. With advancements in data-driven approaches, there is an opportunity to leverage patient information—such as age, blood pressure, cholesterol levels, smoking status, diabetes presence, and other health metrics—to predict the likelihood of developing CHD.

The goal of this project is to design and implement a machine learning-based classification model that accurately predicts a patient’s 10-year risk of developing coronary heart disease. The model will use historical and clinical data to provide actionable insights, enabling clinicians to target at-risk patients with tailored preventive measures, such as lifestyle modifications, medication, or closer monitoring. By combining innovative technology with clinical expertise, this project aims to contribute to reducing the global burden of CHD and improving patient outcomes.

# Dataset 
The dataset is publically available on the Kaggle website, and it is from an ongoing cardiovascular study on residents of the town of Framingham, Massachusetts. The classification goal is to predict whether the patient has 10-year risk of future coronary heart disease (CHD).The dataset provides the patients’ information. It includes over 4,000 records and 15 attributes.
https://www.kaggle.com/datasets/christofel04/cardiovascular-study-dataset-predict-heart-disea

# Risk model pipline 

1)Data Collection and Preprocessing

Data Sources: Collect patient data from reliable sources, including electronic health records (EHRs), health surveys, and clinical databases.
Data Cleaning: Handle missing values, remove duplicates, and address inconsistencies to ensure data quality.
Feature Engineering: Select relevant features such as demographic details, clinical history, lab results, and lifestyle factors. Normalize and encode data as required.

2)Exploratory Data Analysis (EDA)

Descriptive Statistics: Analyze distributions and relationships within the data to identify trends and correlations.
Visualization: Use tools like histograms, scatter plots, and correlation matrices to detect patterns and anomalies.


3)Feature Selection and Optimization

Feature Importance Analysis: Use statistical methods and algorithms like recursive feature elimination (RFE) or LASSO regression to identify the most predictive features.
Dimensionality Reduction: Apply techniques like PCA (Principal Component Analysis) if needed to simplify the dataset while retaining critical information.

4)Model Development

Algorithm Selection: Experiment with various machine learning algorithms (e.g., Logistic Regression, Random Forests, Gradient Boosting Machines, Neural Networks) to find the most suitable one for CHD risk prediction.
Training: Split the dataset into training, validation, and test sets. Train the model on the training data while fine-tuning hyperparameters.
Validation: Evaluate the model’s performance using validation data to avoid overfitting.

5) Model Evaluation

Performance Metrics: Assess the model using metrics such as accuracy, precision, recall, F1-score, and AUC-ROC to gauge its effectiveness.
Bias and Fairness Testing: Ensure the model does not introduce bias against any demographic group.

