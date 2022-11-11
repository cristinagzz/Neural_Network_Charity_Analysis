# Neural_Network_Charity_Analysis

## Overview of the analysis

In this project we used the attributes in the supplied dataset developing a binary classifier that can determine if applicants will be financed by Alphabet Soup using  machine learning and neural networks.

## Results

### Data Preprocessing

### What variableS are considered the targetS for your model? 
IS_SUCCESSFUL

### What variable(s) are considered to be the features for your model?
APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME ATM, SPECIAL CONSIDERATIONS, ASK ATM

### What variable(s) are neither targets nor features, and should be removed from the input data?
EIN and NAME

### Compiling, Training, and Evaluating the Model

### How many neurons, layers, and activation functions did you select for your neural network model, and why?

As you can see on the image, i used 8 neurons in the first layer and 5 neurons in the second layer. 

In the hidden layers i used "Relu" and "Sigmoid" in the output layers.

<img width="507" alt="First model" src="https://user-images.githubusercontent.com/108194577/201245779-13c77765-b312-41b8-8495-46d890fb587a.PNG">


### Were you able to achieve the target model performance?
No, my accuracy was .443

<img width="577" alt="accuracy" src="https://user-images.githubusercontent.com/108194577/201245757-46dfb92e-0f63-406a-a151-17ce5ff9b7c1.PNG">


#### What steps did you take to try and increase model performance?
I used the following neurons,
hidden_nodes_layer1 = 80
hidden_nodes_layer2 = 25
hidden_nodes_layer3=40 

"Relu" has hidden layers and "Sigmoid" as output

## Summary

Based on the study, it is clear that the deep neural network machine learning model developed a binary classifier that is only marginally beneficial for determining if lending money to a particular applicant will result in successful outcomes. However, even after repeated optimization testing, the predictive capability doesn't exceed 75% accuracy. As a result, it could be worthwhile to explore either more optimization methods for this model or an entirely different supervised learning classification model for AlphabetSoup's requirements. An ensemble-based random forest classifier, for instance, would be a workable choice as a structural comparison to a neural network. 
