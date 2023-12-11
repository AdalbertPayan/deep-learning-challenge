# deep-learning-challenge
* Module 21 Challenge focuses on Machine Learning and Neural Networks

## Overview of the analysis: 

In addressing the requirements of the nonprofit foundation Alphabet Soup, the task involves creating a binary classifier capable of predicting the success of organizations in their ventures based on features present in a dataset. The dataset encompasses data from over 34,000 organizations that have received funding from Alphabet Soup. 

* The objective is to employ machine learning and neural networks to construct a binary classifier that aids Alphabet Soup in selecting applicants with the highest likelihood of success. This classifier will utilize the provided features to predict whether organizations will be successful when funded by Alphabet Soup.

* To execute this task, I have leveraged machine learning techniques, including data preprocessing, feature engineering, and the development of a neural network model. The predictive performance of the model can be evaluated, and refinements can be implemented to enhance its accuracy based on historical data.



## Results
* Data Preprocessing:
    * The target variable for this model is 'IS_SUCCESFUL'
    * The feature variable are the following: 'APPLICATION_TYPE', 'AFFILIATION', 'CLASSIFICATION', 'USE_CASE', 'ORGANIZATION', 'STATUS', 'INCOME_AMT', 'SPECIAL_CONSIDERATIONS' and 'ASK_AMT'.
    * There are two variable that were removed because they did not add to the model. They are 'EIN' and 'NAME'.
    
* Compiling, Training, and Evaluating the Model:
    * Buidling the model is a process of experimentation. To start out, I chose to start out with 2 hidden layers followed by an output layer. There are different choices available to activate the model, I chose to use 3 different options, 'relu', 'tanh' and 'sigmoid'.

    * The target for the optimized model was 75 percent accuracy. My optimized model has an accuracy of about 73%. 

    
* Summary:
    Overall, this model has an accuracy of 73%. 