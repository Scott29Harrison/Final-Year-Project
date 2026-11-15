# Final-Year-Project
Third Year Data Science project using machine learning to predict the usability of video game menu screens.


# Aims and Objectives

The aims and objectives of this project are to:

a.	Determine possible factors that make in-game menus usable.
This will be done by collecting data from participants via questionnaire and analysing the data gathered to find factors with the largest effect on usability. The analysis will also reveal any potential biases which may affect the results of the project.

b.	Create a machine learning algorithm to predict if a menu will have high usability.
The best models for the problem will be determined by looking at the data types of the features with the highest effect on usability and the data type of the overall usability score. The collected data will then be used to train the models, which will allow the most effective model to be determined.

c.	Determine possible disparities in usability between genres.
The collected data will be compared between genres in order to determine if different genres should place more importance on certain factors than others. This will help provide guidelines for specific genres when creating game menus. 


# Abstract

This project investigates the usability of in game menus across a range of genres and consoles, addressing a gap in existing research, which typically focuses on hardware, overall gaming experience, or visual design rather than the specific factors that make menus usable. Data was collected through an anonymous questionnaire distributed to gaming communities, capturing demographic information, genre preferences, and detailed usability ratings for common menu features. The dataset was pre processed to remove inconsistencies, convert categorical responses into numerical form, and restructure entries with multiple games into individual datapoints.

Exploratory analysis showed minimal demographic bias and revealed that no single feature exhibited a strong linear relationship with overall usability, motivating the use of non linear machine learning models. LASSO feature selection identified several influential factors, including the speed of starting a game, the ease of distinguishing between options, and the ease of finding options, alongside other clarity and navigation related features. Multiple regression models were evaluated, with CatBoost achieving the strongest performance (R-squared = 0.939), outperforming Linear Regression, Logistic Regression, SVR, Random Forest, and XGBoost.

The results demonstrate that menu usability is shaped primarily by clarity, responsiveness, and navigational ease, while aesthetic elements such as theming have comparatively little impact. The findings provide a foundation for predicting menu usability and offer practical guidance for improving interface design across game genres.
