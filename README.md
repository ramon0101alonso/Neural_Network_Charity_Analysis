# Neural_Network_Charity_Analysis

# Overview
###### I will help Beks create a binary classifier that is capable of predicting weather applicants will be successful in funded by Alphabet Soup. A CSV with more than 34,000 organizations will be used to create three Neural Network Model to find out which combination of input features, nodes and hidden layers give the best loss and accuracy test data.

# Results:
## Data Preprocessing
###### What variable(s) are considered the target(s) for your model?
- IS_SUCCESSFUL column
###### What variable(s) are considered to be the features for your model?
- All variables except EIN, NAME, and USE_CASE 
###### What variable(s) are neither targets nor features, and should be removed from the input data?
- EIN, NAME, and USE_CASE

# Compiling, Training, and Evaluating the Model
###### How many neurons, layers, and activation functions did you select for your neural network model, and why?
###### The three different models used various combinations to reach a 75% success rate.  Here is the breakdown of the models:
- Model 1: 170 neurons, 2 hidden layers and activation function relu and sigmoid
- Model 2: 120 neurons, 3 hidden layers and activation function relu and tanh
- Model 3: 170 neurons, 2 hidden layers and activation function sigmoid
###### Were you able to achieve the target model performance?
###### After performing three different Neural Network Models, I was not able to obtain a performance higher than 75%.  The highest was 65% and the lowest was 48%.
- Model 1
![Model 1](https://github.com/ramon0101alonso/Neural_Network_Charity_Analysis/blob/main/Resources/Model%201%20Evaluation.png)
- Model 2
![Model 2](https://github.com/ramon0101alonso/Neural_Network_Charity_Analysis/blob/main/Resources/Model%202%20Evaluation.png)
- Model 3
![Model 3](https://github.com/ramon0101alonso/Neural_Network_Charity_Analysis/blob/main/Resources/Model%203%20Evaluation.png)        
###### What steps did you take to try and increase model performance?
###### By changing the amount of neurons, layers and activation functions, I was able to change the accuracy rate of my models.  The goal of 75% was not reached.

# Summary
###### The model with the highest accuracy was at 65%.  Changing the neurons, hidden layers and activation will definately increase or decrease the accuracy.  Higher neurons can decrease the accuaracy  because it is unecessary.  Using different combinations would take a long time but can be possible to obtain a closer goal accuracy of 75%