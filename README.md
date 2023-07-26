# deep-learning-challenge

Report on Performance of Deep Learning Model for Alphabet Soup

Overview of the Analysis:
The purpose of this analysis was to create a deep learning model that can classify whether funding applicants from Alphabet Soup, a philanthropic organization, will be successful. The model aims to analyze the historical data of the applicants, including various features such as the type of application, the amount requested, the organization's name, income, etc., to predict whether the applicant will be successful if funded. By accurately predicting the success or failure of funding, Alphabet Soup can make more informed decisions, maximize the impact of their contributions, and minimize the risk of funding unsuccessful projects.


Results: for the First Model

Data Preprocessing:

•	Target Variable: The target variable for the model is 'IS_SUCCESSFUL', which indicates whether funding applicants were successful (1) or not (0).

•	Features: All the other columns in the dataset, after preprocessing, serve as the features for the model. These features are used to make predictions about the target variable 'IS_SUCCESSFUL'.

•	Variables to Remove: The variables 'EIN' and 'NAME' were removed from the input data during preprocessing because they are neither targets nor features. They are non-beneficial ID columns that do not provide meaningful information for the predictive task.

Compiling, Training, and Evaluating the Model:

•	The model has three hidden layers with 80, 30, and 30 neurons, respectively. The number of neurons was chosen based on experimentation and some common practices. Larger numbers of neurons in hidden layers allow the model to learn more complex patterns in the data, but they also increase the risk of overfitting. Smaller numbers of neurons might lead to underfitting and insufficient model capacity.

•	The evaluation of the model on the test dataset shows an accuracy of approximately 73.03%.


Results for the Second Model – Optimization

Data Preprocessing:

•	Target Variable: The target variable for the model is 'IS_SUCCESSFUL', which indicates whether funding applicants were successful (1) or not (0).

•	Features: All the other columns in the dataset, after preprocessing, serve as the features for the model. These features are used to make predictions about the target variable 'IS_SUCCESSFUL'.

•	Variables to Remove: The variables 'EIN', “STATUS’  and ''SPECIAL CONSIDERATIONS” were removed from the input data during preprocessing because they do not provide meaningful information for the predictive task.

Compiling, Training, and Evaluating the Model:

•	The model has three hidden layers with 80, 30, and 30 neurons, respectively. The key difference between the two models is the optimization I incorporated optimization techniques like adjusting the number of hidden nodes in each layer and using a third hidden layer, which may improve the model's performance.

•	The evaluation of the model on the test dataset shows an accuracy of approximately 78%. The evaluation results show Soup Charity Optimization achieved better performance compared to Model 1 (Soup Charity) in terms of accuracy. Model 2 has a higher accuracy, indicating that the optimization process has likely led to a more effective model.


Summary:
Overall, the deep learning model shows promising results in predicting the success of funding applicants for Alphabet Soup. To potentially improve the model's performance, a different approach could be considered, such as using a more advanced deep learning architecture.
