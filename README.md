# Retail-Sales-Prediction-


![640px-Rossmann_Logo svg](https://user-images.githubusercontent.com/104754645/174442537-0a299233-58b6-4ebf-9208-a62f5a7d82c5.png)
# 📖PROBLEM STATEMENT
Rossmann operates a network of over 3,000 drug stores spanning 7 European countries. Presently, Rossmann store managers face the challenge of forecasting their daily sales for the next six weeks. The sales of each store are influenced by diverse factors such as promotions, competition, school and state holidays, seasonality, and local nuances. Given the multitude of individual managers predicting sales based on their unique circumstances, the accuracy of these predictions can vary significantly. My work in this project encompasses the creation of various plots, graphs, and visualizations, as well as feature engineering, ensemble techniques, application of different machine learning algorithms with corresponding parameter tuning, and thorough analysis of trends. The goal is to predict the daily sales for the upcoming six weeks across 1,115 stores located throughout Germany.
# 📖ALGORITHMS USED:
### I. Linear Regression
### II. Linear Regression With Regularization
### III. Decision Tree
### IV. Ensemble Of Random forest.


# 📖Solution Strategy
My approach to address this challenge involved the following steps:

1. Data Description: Utilize statistical metrics to identify data distributions.

2. Feature Engineering: Generate new attributes based on the original variables to enhance the description of the phenomenon being modeled.

3. Exploratory Data Analysis: Investigate the data to uncover insights and gain a better understanding of how variables impact model learning.

4. Feature Selection: Select the most significant attributes for training the model.

5. Machine Learning Modeling: Train the machine learning model.

6. Hyperparameter Fine-Tuning: Choose the optimal values for each parameter of the model selected in the previous step.

7. Convert Model Performance to Business Values: Translate the performance of the machine learning model into a business result.

8. Deploy Model to Production: Release the model in a cloud environment, enabling other individuals or services to use the results to improve business decisions.


# 📖CONCLUSION
Initially, we conducted Exploratory Data Analysis (EDA) on each feature in our dataset during our investigation. Our dependent variable, Sales, was the first to undergo analysis and transformation. Subsequently, we scrutinized categorical variables, eliminating those dominated by a single class. Numerical variables were examined using the corr() function to ascertain their correlation, distribution, and relationship with the dependent variable. For detecting multicollinearity, the developed VIF function was employed. Additionally, we hot-encoded categorical variables and removed several numerical features with a substantial percentage of zero values.

Observations:

1. Sales peak during three specific months: July, November, and December, while May experiences the lowest sales.
2. Sales exhibit an annual increase due to discounts offered by stores.
3. School closures impact some store sales, with no effect observed in B-type stores.
4. Sales are predominantly associated with B-type assortment.
5. Maximum sales occur during public holidays, whereas religious occasions like Easter or Christmas see lower sales, particularly for B-type assortment.
6. Store type A records the highest sales, attributed to the high number of type A stores in the dataset, with types A and C having similar sales and customer share.
7. Most stores remain closed during state holidays, but interestingly, more stores open during school holidays than during state holidays.
   
Model Evaluation:
1. Linear Regression algorithms, both with and without regularization, yield a commendable R-squared score of 0.70.
2. Decision Tree Regressor achieves a strong R-squared score of 0.94 on the test set.
3. Random Forest Regressor stands out as a top-performing model.
4. Gradient Boosting Regressor performs well, with an R-squared score of 0.82 on the test set. GridSearchCV optimization improves the score from 0.94 to 0.96, nearly matching the Random Forest Regressor.
5. No overfitting is observed.
   
Conclusion: Considering the comprehensive evaluation, the Random Forest Regressor model emerges as the optimal choice for deployment.

# 📋 Execution Instruction
The given IPython Notebook can be either downloaded to be run on your local Jupyter Notebook or can be directly run on Google Colab.

# 📜 Credits
 Kajal Wasnik| Data Scientist | Machine Learning Engineer | Data Science enthusiast

Special thanks to AlmaBetter



