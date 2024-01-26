#Data Preprocessing

1. What variable(s) are the target(s) for your model?

**ANSWER** The target is the IS-SUCCESSFUL column

2. What variable(s) are the features for your model?

**ANSWER** The features list of this model are as follows:
name, application type, affliation, classification, use_case, organization, income, special consideration status and ask amount.


3. What variable(s) should be removed from the input data because they are neither targets nor features?

**ANSWER** EIN(Employee identification)


#Compiling, Training, and Evaluating the Model

1. How many neurons, layers, and activation functions did you select for your neural network model, and why?

**ANSWER** For this model 3 hidden layers each with many neurons because the compute seems to increate the accurcay above 75%. This is expensive and costly. The first activations is relu and the other layers are sigmoid. It might boost accuracy using the functions. Readjusting my data that names as a get dummies can factor in with better scores.


2. Were you able to achieve the target model performance?

**ANSWER** Yes.


3. What steps did you take in your attempts to increase model performance?

**ANSWER** Required to convert the NAME into data points which has the biggest impact on improving efficiency but costly and it requires adding third layer using sigmoid activation function.

#Summary: Summarize the overall results of the deep learning model. 

**ANSWER**
Overall, the accuracy above 75% we are able to correctly classify each in the test 75% of the time.
And an applicant has a 80% chance of being successful if they following this:
Name of applicants appears more than 5 times type of applications following T3 T4 T5 T6 T7 T8 T10 T19 application of following classification.

#Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.

**ANSWER** RandomForest model
