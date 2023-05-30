# Heart-Disease-Prediction
Overview
Heart disease is a leading cause of death worldwide, and early detection is critical for effective treatment. In this project, I built a machine learning model to predict the likelihood of heart disease based on patient data. The dataset used for this project is the Cleveland Heart Disease dataset, which contains 303 instances and 14 attributes.

Data Preprocessing
The data contained duplicate entries, which were handled by removing the duplicates. To identify the outlier box plot is used, and the data was standardized using the StandardScaler() function from scikit-learn.

Exploratory Data Analysis
I created several visualizations to explore the data, including histograms, scatterplots, and box plots. The visualizations helped me identify some key features that were strongly correlated with heart disease, such as age, chest pain type, and maximum heart rate achieved.

Feature Selection
I used a combination of different feature selection to select the most important features for predicting heart disease. The final features selected were ST depression induced by exercise, exercise induced angina, chest pain type, and maximum heart rate achieved.

Model Selection
I experimented with several machine learning models, including logistic regression, decision trees, and random forests. After comparing the performance of the different models, I chose the support vector classifier as the final model due to its high accuracy and F1 score.

Model Evaluation
The final model achieved an accuracy of 85 % and an F1 score of 0.85 on the test data. 

Conclusion
The heart disease prediction model I developed using machine learning showed promising results and could be used to identify patients at risk of heart disease. Future work could include incorporating additional features, such as lifestyle factors and medical history, to improve the accuracy of the model.
