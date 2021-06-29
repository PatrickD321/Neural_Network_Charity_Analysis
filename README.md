# Neural Network Charity Analysis

## Overview 
The dataset from Alphabet Soup shows organizations that have received funding for various projects over the years. We will attempt to use a Neural Network Model to predict how successful, or if the funding was put to meaningful use by the various organization. This analysis should be able to determine if Alphabet Soup will be continued with its program or make major changes to the existing format.

## Results
### Data Preprocessing 
- What variable(s) are considered the target(s) for your model?  
Looking at the dataframe that was downloaded from “charity_data.csv”, the question  was asked in the Project Overview, the outcome of the charity work, “IS_SUCCESSFUL” variable column is considered our target for the model.  
- What variable(s) are considered to be the features for your model?  
Usually an entire dataset has all the information that is necessary to train and build our model but these information should be categorical, that is belonging to a group. Data with columns that have names, ID number and sometimes address are not needed in the analysis and are considered as noise. The features for this model are shown in figure1![fig1](https://user-images.githubusercontent.com/78861458/123720198-84fc2600-d851-11eb-8310-ddd106067276.png)  
- What variable(s) are neither targets nor features, and should be removed from the input data?  
As mention previously any data that are not considered as categorical such as “EIN” and “NAME” from the dataframe should be dropped. 

### Compiling, Training, and Evaluating the Model  
- How many neurons, layers, and activation functions did you select for your neural network model, and why?  
Using the rule of thumb we should use a neural network model with six neurons in the hidden layer to properly model our linear and nonlinear datasets, seven neurons were chosen for the model. The optimal size of the hidden layer is usually between the size of the input and size of the output layers. The addition hidden layer with 4 neurons was added just to improve the model. 
- 

