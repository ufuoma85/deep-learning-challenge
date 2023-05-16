# deep-learning-challenge
the purpose of this analysis is to predict whether applicants will be successful if funded by Alphabet Soup.


Data Preprocessing

The target variable used for the model is IS_SUCCESSFUL and the feature variables were all the other columns excluding NAME and EIN are the feature variables. The Name was reintroduced for optimization.

Compiling, Training, and Evaluating the Model
2 hidden layers with 80, 30 neurons and activation function of relu was used with one output layer with activation function of sigmoid.

the target model performance was achieved with the reintroduction of Name column thereby increasing the features. the features were increased and decreased at different interval to train and test the model 



Summary: The final automatically optimized neural network trained model from the keras tuner method achieved 76% prediction accuracy with a 0.49 loss, using a sigmoid activation function with input node of 73; 2 hidden layers neurons split and 100 training epochs. Performing better than the non automized model. Keeping the Name column was essential in achieving the accuracy beyond 75%. The shape and details of the datasets is very important in achieving a high accuracy.

