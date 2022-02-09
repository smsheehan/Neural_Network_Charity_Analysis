# Neural_Network_Charity_Analysis

## Overview of the analysis: Explain the purpose of this analysis.
The premise of the analysis is to create a binary classifier that is capable of predicting whether applicants will be successful if funded by the fictional agency Alphabet Soup.  As part of the exercise, the data was processed to make it suitable for our neural network models.  An initial neural network model was run with two layers and the mosel weights were checkpointed along the way.  The rest of the exercise involved attampting to optimize the model for improved accuracy.

## Results: Using bulleted lists and images to support your answers, address the following questions.

### Data Preprocessing

* What variable(s) are considered the target(s) for your model? The target is the "IS_SUCCESSFUL" category
* What variable(s) are considered to be the features for your model?  The features are all of the rest of the columns, with the exception of "EIN" and "NAME" which were dropped from the table because these two features have no logical bearing on whether an agency successfully utilizes funding.
* What variable(s) are neither targets nor features, and should be removed from the input data? As described above, "EIN" and "NAME" were dropped.

### Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why? In deliverable 2, our model utilized 2 layers whith the "relu" activation function:
![image](https://user-images.githubusercontent.com/90977689/153240515-c2520399-c4ab-4ebe-a2ef-0333c07708d4.png)

Were you able to achieve the target model performance?
What steps did you take to try and increase model performance?
## Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.
