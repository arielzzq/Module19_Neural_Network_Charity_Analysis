# An Analysis to predict the investment success for different organizations

## Overview of the analysis
The purpose of this analysis is to use neural network and deep learning to help the foundation predict where to make investments.

## Results

### Data Preprocessing
- IS_SUCCESSFUL is considered the target for my model.
- APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION (type) ,(Active) STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS and ASK_AMT are considered to be the features for my model.
- EIN and NAME are removed

### Compiling, Training, and Evaluating the Model
- I used 48 neurons for the first layer, the activation function was tahn. 24 neurons were used for the second layer, the activation function was tanh. I used 8 neurons for the third layer, and I chose relu as activation function.
- I didn't achieve the target model performance
- I first increased the number of layers from 2 to 3 layers, it did work
- Then I increased the number of neurons for each layer.
- I decrease the threshold for binning, so there will be less categories fall into "others"
- I chose tanh over relu because the input value had many negative value.

## Summary
Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.

The accuracy of the model was 72.14% before optimization, and was 72.47% afterwards. Random Forest could also solve this classification problem, it can solve the problem faster.
