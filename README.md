Step 4: Write a Report on the Neural Network Model
For this part of the assignment, you’ll write a report on the performance of the deep learning model you created for Alphabet Soup.

The report should contain the following:

**Overview of the analysis: **
This analysis is designed to create a deep learning model using a neural network to predict the success and failure of charitable organizations funded by Alphabet Soup. The model is designed to help determine which applicants will be successful based on a number of variables in the dataset.

Results:

Data Preprocessing

What variable(s) are the target(s) for your model?
Target Variable(s): The target variable for our model is "IS_SUCCESSFUL", which indicates whether the charitable organization's funding was successful (1) or not (0).
What variable(s) are the features for your model?
Feature Variables: The feature variables for our model include all columns in the dataset except for "IS_SUCCESSFUL".
What variable(s) should be removed from the input data because they are neither targets nor features?
Variables to be Removed: The variables "EIN" and "NAME" were removed from the input data as they aren't applicable to this prediction model as the name and identity shouldn't affect their success viability.

Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
The neural network model consists of four hidden layers with the following number of neurons: 80 (first layer), 60 (second layer), 40 (third layer), and 20 (fourth layer). However, this was changed multiple times to find a method to increase the accuracy, which I failed to do.
Were you able to achieve the target model performance?
I was not able to increase the accuracy to 75%.
What steps did you take in your attempts to increase model performance?
Methods used to increase Accuracy:
1) Changed unit counts in the two hidden layers to 50 and 30. Accuracy went down.
2) Increased hidden layer amounts to 80, 50, 30, 10. Accuracy went down.
3) Increased hidden layer amounts to 50, 40, 30, 20. Accuracy went down.
4) Decreased hidden layer amounts to just 50. Accuracy went down.
5) Increased epoch count to 300. Accuracy went down.
Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
The deep learning model was able to predict accurately the 'IS_SUCCESSFUL' applicants at a rate of 73%. This indicates a workable accuray, but it could be improved to receive better results. A potential method to investigate in the future to increase accuracy could be to remove two columns from the dataset: 'Affiliation' and 'Organization'. These are both variables that potentially do not affect the outcome and so could be removed to increase accuracy.
