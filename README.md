# HR-Analytics-Job-Change-Prediction
Problem Statement

A company which is active in Big Data and Data Science wants to hire data scientists among people who successfully pass some courses which was conducted by the company. Many people signup for their training. Company wants to know which of these candidates really wants to work for the company after training or looking for a new employment because it helps to reduce the cost and time as well as the quality of training or planning the courses and categorization of candidates.


Features and Descriptions
---------------------------



enrollee_id: Unique ID for each candidate.

city: Code for the city.

city_development_index: Index indicating the development level of the city.

gender: Gender of the candidate.

relevent_experience: Whether the candidate has relevant experience.

enrolled_university: Type of university course enrolled in, if any.

education_level: Education level of the candidate.

major_discipline: Major discipline of the candidate's education.

experience: Total years of experience of the candidate.

company_size: Number of employees in the candidate's current company.

company_type: Type of the candidate's current company.

last_new_job: Number of years since the candidate's last job.

training_hours: Number of training hours completed.

target: Indicates if the candidate is looking for a job change (0: Not looking, 1: Looking).

Preprocessing Steps


Handling Missing Values: Missing values in categorical columns were replaced with the mode.
Balancing the Dataset: SMOTE (Synthetic Minority Over-sampling Technique) was used to balance the dataset.


Classification Models and Evaluation


Various classification models were applied to predict the target variable, including:

K-Nearest Neighbors (KNN)

Support Vector Classifier (SVC)

Bernoulli Naive Bayes

Decision Tree Classifier

Random Forest Classifier

Gradient Boosting Classifier

Evaluation Metrics: Accuracy, precision, recall, and F1-score were used to evaluate the models.
