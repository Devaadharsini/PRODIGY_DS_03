TASK 3: 
Build a decision tree classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data. Use a dataset such as the Bank Marketing dataset from the UCI Machine Learning Repository.

Dataset name : Bank Marketing dataset
Dataset link : https://archive.ics.uci.edu/dataset/222/bank+marketing

1)Loaded the Bank Marketing dataset

2)Exploratory Data Analysis (EDA)

- Analyzed Age based on Job and Marital status
- Examined Number of Previous Contacts by Communication Type and Campaign Outcome
- Analyzed Frequency of Contacts during Campaign by Communication Type and Campaign Outcome
- Studied Average Yearly Bank Balance distribution by Education and Campaign Outcome

3)Data Preparation

- After splitting data into input variables and target variable, found unique values in each categorical variable
- Mapped categorical data into numeric form
- Created a correlation matrix of input variables

4)Model Building

-Trained a Decision Tree Classifier 
-Achieved an accuracy of 96%

5)Model Evaluation

-Evaluated model performance with classification report and visualized it through heatmap
-Predicted customer purchases using unseen data
