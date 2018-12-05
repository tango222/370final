#Project Overview

The purpose of our project is to create a machine learning model to predict whether or not a person has heart disease based on a variety of factors. Heart disease is the leading cause of death in the United States, with 1 of 4 deaths. Learning about causes of heart problems and healthy habits to prevent heart disease can be beneficial in the long run. Early detection of heart disease can be an effective technique to reducing deaths from heart diseases.
In our broader problem domain, our research would help doctors predict cases of heart disease based on the patient’s health history and habits. The Center of Disease Control and Prevention mentions that early action is important for heart attacks. There are also risk factors such as high blood pressure and high cholesterol putting Americans at a higher risk for heart disease. In an article linked to the problem description for the competition, there have been research into using machine learning and data mining techniques to prevent heart disease. The goal of that study was to find hidden patterns to prevent the presence of heart disease in patients. They used methods such as Decision Trees, J48, Logistic and Random Forest algorithm for their analysis.
Citations/ Potential Articles:
Aha, D., and Dennis Kibler. "Instance-based prediction of heart-disease presence with the Cleveland database." University of California 3.1 (1988): 3-2.

Dangi, Gaurav, Tanupriya Choudhury, and Praveen Kumar. "A smart approach to diagnose Heart disease through machine learning and Springleaf Marketing Response." Recent Advances and Innovations in Engineering (ICRAIE), 2016 International Conference on. IEEE, 2016.

Rao, P. Sambasiva, and Dr T. Uma Devi. "A Parameter Based Heart Disease Detection Technique using Mining Technique." International Journal of Latest Trends in Engineering and Technology 7.3 (2016): 077-087.

Menotti, Alessandro, et al. "The strength of the multivariable associations of major risk factors predicting coronary heart disease mortality is homogeneous across different areas of the Seven Countries Study during 50-year follow-up." Acta cardiologica 73.2 (2018): 148-154.

Slomka, Piotr. "Machine learning for predicting death and heart attacks from CCTA." (2018).

Steele, Andrew J., et al. "Machine learning models in electronic health records can outperform conventional survival models for predicting patient mortality in coronary artery disease." bioRxiv (2018): 256008.

J Steele, Andrew & Aylin Cakiroglu, S & Shah, Anoop & Denaxas, Spiros & Hemingway, Harry & Luscombe, Nicholas. (2018). Machine learning models in electronic health records can outperform conventional survival models for predicting patient mortality in coronary artery disease. 10.1101/256008.

In our project we are going to test whether blood flow to the heart, the quality of blood flow to the heart, resting blood pressure, chest pain, the number of major vessels, fasting blood sugar, ekg results, cholesterol, ST depression, sex, age, maximum heart rate, and exercise-induced angina can predict heart disease.
We will be using a dataset that comes from the DrivenData “Warm Up: Machine Learning with a Heart” competition. The dataset is from a study of heart disease and includes measurements on patient health and cardiovascular statistics. It is provided by the Cleveland Heart Disease Database via the UCI Machine Learning Repository.
To test our hypothesis, we will be using  Logistic regression. Logistic regression is a statistical method for predicting binary classes. The outcome or target variable is dichotomous in nature. Dichotomous means there are only two possible classes. For example, it can be used for cancer detection problems. It computes the probability of an event occurrence.
It is a special case of linear regression where the target variable is categorical in nature. It uses a log of odds as the dependent variable. Logistic Regression predicts the probability of occurrence of a binary event utilizing a logit function. Source from Data camp blog. Because we have a binary outcome, heart disease present or not present, we will use logistic regression.To avoid over-fitting and under-fitting, we should include all significant variables. A good approach to ensure this practice is to use a step wise method to estimate the logistic regression

Our target audience includes people who are more likely to be diagnosed with heart disease as well as people who want to learn about how to prevent heart disease. It can also be for doctors to predict and detect cases of heart disease early on, based on the results. Based on our resource, our audience should learn more about the factors that make it more likely for them to get heart disease.

#Technical Description

The format of our final web resource will be in python. WE will use the bokeh library for interactive graphs that can be published to a HTML page. Because our data set is from DrivenData there won’t be many challenges with data collection. In terms of data management, we will need to decide how to handle missing variables, if any.
To complete the project we will learn how to use the bokeh library, which we can learn through data camp, and we would need to learn how to code Logistic regression with a stepwise variable selection in Python.
To conduct our analysis we will first research the problem domain, by reading through the articles we compiled for research. Then based on our research we will wrangle the data to answer or hypotheses. We will explore the data with statistical tests, and create visualizations to help us understand the problem domain through the dataset, and we will measure the association of certain variables with statistical modeling. We will create new features for our model using machine learning approaches. Since many of us in the group have just learned python in this class we anticipate challenges in using python, and also using bokeh to make the report.
