# Deep-Learning-Challenge

Overview of the analysis: Overall objective here is to develop a model that can help Alphabet Soup predict which applicants it is selecting for funding has the best chance of success in their ventures.   A binary classification model was developed using machine learning and neural networks along with the dataset provided.  Initial model was developed and optimized by adding layers of neurons and nodes.   Activation function was also changed during optimization to see if it can improve the accuracy. The optimized model can predict success chances to about 74% accuracy.  

Results:

 •	Data Preprocessing

 o	What variable(s) are the target(s) for your model?
 The IS_SUCCESSFUL column is the target of model.

 o	What variable(s) are the features for your model?
 All columns other than IS_SUCCESSFUL column are variables

 o	What variable(s) should be removed from the input data because they are neither targets nor features?
 The two that were removed initially was EIN & NAME that were neither targets nor features.

 •	Compiling, Training, and Evaluating the Model

 o	How many neurons, layers, and activation functions did you select for your neural network model, and why?
 Model had two hidden layers with 9 neurons in the first layer and 18 in the second layer.  I used Relu activation function for the two layers and Sigmoid for the final output layer.  Since Relu is less expensive from processing time standpoint, so for the initial layers it makes sense to use that and then polish the output with sigmoid to improve accuracy.

 o	Were you able to achieve the target model performance?
 No with two hidden layers, I was not able to achieve the target > 75% accuracy but got pretty close at 73.5%

 o	What steps did you take in your attempts to increase model performance?
 I increased one layer, increased the number of Epoch 50 from initial 30.  That got the accuracy to increase to 74%

Summary:   Optimization resulted in 74% accuracy while initially the model has 73.5% accuracy. Therefore we gained very little on accuracy via adding one more hidden layer.   Other models could be explored to see if the accuracy is better for example, Random Forest Clusters. 
