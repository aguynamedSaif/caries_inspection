# caries_inspection

This repository contains the code for a project that analyzes a private dataset to predict the number of caries in a patient. The dataset includes the following parameters:

#HEIGHT: height of respondent
#CARIES: No of caries
#INCOME: Household income
#P31.2: Do you drink Ribenna everyday?
#P31.6: Do you drink milk tea with sugar every day?
#P31.8: Do you drink coffee with sugar everyday?
#ASCORE: score of attitude towards dental caries prevention
#PSCORE: Score of practise towards dental caries prevention
#kns: Knowledge score towards dental caries prevention
#The project is divided into the following steps:

Data preprocessing: The data is preprocessed to remove missing values and outliers.
Feature selection: The features are selected using a statistical method called ANOVA.
Model training: A logistic regression model and a neural network model are trained on the selected features.
Model evaluation: The models are evaluated using the accuracy metric.
The results show that the logistic regression model has a higher accuracy than the neural network model.

Instructions
To run the project, you will need to have Rstudios
Once you have installed the required libraries, you can run the project by following these steps:

Clone the repository to your local machine.
Open the caries_inspection.Rmd notebook in R Notebook.
Run the cells in the notebook.
Results
The results of the project are shown in the caries_inspection.Rmd notebook. The notebook includes the following:

A table of the accuracy scores of the logistic regression model and the neural network model.
A plot of the ROC curves of the two models.

#Conclusion
The results of the project show that the logistic regression model is a better predictor of caries than the neural network model. This is likely because the logistic regression model is a simpler model that is less prone to overfitting.

The project can be improved by using a larger dataset and by using a more sophisticated feature selection method.