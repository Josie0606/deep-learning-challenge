# deep-learning-challenge
**Overview**

The objective of this analysis is to develop a machine learning model that can effectively identify a fictitious charitable organization with the highest likelihood of success in their endeavors. The dataset used for this analysis is sourced from Alphabet Soup, a nonprofit foundation, and consists of information on over 34,000 organizations that have previously received funding from Alphabet Soup. The dataset includes details such as application type, affiliation, classification, funding use case, organization type, active status, income, special considerations, requested funding amount, and the success or failure of each applicant.

The ultimate goal is to utilize this dataset to build a model capable of accurately predicting the success of charitable organizations, thereby enabling Alphabet Soup to make more informed decisions when reviewing and approving funding applications. Specifically, a binary classification model will be employed to predict whether funding requests will be approved or denied.

The analysis encompasses various steps, including data cleaning and preprocessing, feature engineering, model selection and training, as well as evaluation of the model's performance. The objective is to create a model that can effectively predict funding success based on the available data, thereby assisting in future funding approval decisions.

**Results**
* Data Preprocessing
 * What variable(s) are the target(s) for your model?
   - Targer variable is the "IS_SUCCESSFUL" data 
 * What variable(s) are the features for your model?
   - My variables in my model is 'APPLICATION_TYPE', 'AFFILIATION', 'CLASSIFICATION', 'USE_CASE',
       'ORGANIZATION', 'STATUS', 'INCOME_AMT', 'SPECIAL_CONSIDERATIONS',
       'ASK_AMT' data.
 * What variable(s) should be removed from the input data because they are neither targets nor features?
   - Variable that should be removed from the data are "EIN", "NAME" as they were neither targets nor features.

* Compiling, Training, and Evaluating the Model
 * How many neurons, layers, and activation functions did you select for your neural network model, and why?
   - For this classification problem, a neural network model with four layers was selected. The first layer had 80 neurons, the second layer had 30 neurons, and both the third and output layers consisted of 10 neurons each.
   
 * Were you able to achieve the target model performance?
   - The target goal of achieving an accuracy above 75% was not met.

**Summary**

The deep learning model developed for this classification problem achieved an accuracy score of approximately 72%. While this accuracy score surpasses random guessing, it is not particularly high, suggesting potential for improvement.

One potential approach to enhance the model's performance is to explore alternative algorithms, such as a Random Forest model. These algorithms have demonstrated favorable performance across a wide range of classification problems and may be better suited to the specific features of this dataset.