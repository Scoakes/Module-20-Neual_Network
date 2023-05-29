# Module-20-Neual_Network Overview 

We have recieved a csv with data on 34,000 organizations previously funded by Alphabet Soup. Using this data we will construct a classifier to help predict whether future applicants will be successful, if funded. 

##Analysis 

Data Preprocessing
What variable(s) are considered the target(s) for your model?
Is_Successful

What variable(s) are considered to be the features for your model?
ORGANIZATION
STATUS
INCOME_AMT
SPECIAL_CONSIDERATIONS
ASK_AMT
APPLICATION_TYPE
AFFILIATION
CLASSIFICATION
USE_CASE

What variable(s) are neither targets nor features, and should be removed from the input data?
NAME
EIN

Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
hidden_nodes_layer1 = 80
hidden_nodes_layer2 = 30
number_input_features = 42

Were you able to achieve the target model performance?
I was able to achieve ~60% accuracy with this model

What steps did you take to try and increase model performance?
Increasing the number of hidden nodes in layer 1 
Increasing the number of hidden layers to include a 3rd
Changing the activation functions: tried linear, tanh, sigmoid for a combination of hidden layers and output layer

###Summary 
This model was able to help us predict whether potential applicants would be worth while to fund. While there was attempts at increasing accuracy, this classifier should really only be used as a tool. If more time was spent optimizing the hidden layers and tweaking features this tool may be able to be more reliable. Since this model relies on past data, which is all labeled, a neural network may not be necessary; a random forest may be more effective at finding effective ways to classify future applicants. The random forest model can reach similar accuracy scores but are typically less complex than neural nets with less complex code and shorter training times.
