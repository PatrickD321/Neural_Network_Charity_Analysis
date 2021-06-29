# Neural Network Charity Analysis

## Overview 
The dataset from Alphabet Soup shows organizations that have received funding for various projects over the years. We will attempt to use a Neural Network Model to predict how successful, or if the funding was put to meaningful use by the various organization. This analysis should be able to determine if Alphabet Soup will be continued with its program or make major changes to the existing format.

## 1.	Results
### Data Preprocessing 
- What variable(s) are considered the target(s) for your model?  
Looking at the dataframe that was downloaded from “charity_data.csv”, the question  was asked in the Project Overview, the outcome of the charity work, “IS_SUCCESSFUL” variable column is considered our target for the model.  
- What variable(s) are considered to be the features for your model?  
Usually an entire dataset has all the information that is necessary to train and build our model but these information should be categorical, that is belonging to a group. Data with columns that have names, ID number and sometimes address are not needed in the analysis and are considered as noise.
