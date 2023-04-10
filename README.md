# Neural_Network_Charity_Analysis
Knowledge of Machine learning and Neural Network Model used to predict which non-profits will be successful if funded by Alphabet Soup.

## Building the Deep Learning Model
- [AlphabetSoupCharity](https://github.com/MSF2141/Neural_Network_Charity_Analysis/blob/58d0ac033a4baf437d77323942b3a6066e821a48/AlphabetSoupCharity.ipynb)
Python code for a deep learning model, a binary classification model, that can predict if an Alphabet Soup–funded organization will be successful based on the features in the dataset. 

- [AlphabetSoupCharity](https://github.com/MSF2141/Neural_Network_Charity_Analysis/blob/ad4cef78fb844eb4c1ec3c05d42f55596d25acd7/AlphabetSoupCharity.h5)
Callback checkpoints that save the model's weights every 5 epochs.

## Optimization of the Deep Learning Model
- [AlphabetSoupCharity_optimization](https://github.com/MSF2141/Neural_Network_Charity_Analysis/blob/6431928dd7091aab17bc3d5fdb8b7feabcda2ba2/Optimization/AlphabetSoupCharity_optimization.ipynb)
Python code for optimization of the model using three approaches
  - Noisy variables are formatted for binning
  - Additional hidden layers are added
  - Acivation function of output layer is changed for optimization

- [AlphabetSoupCharity_optimization](https://github.com/MSF2141/Neural_Network_Charity_Analysis/blob/1e3e0490d6dfc4c9033f4bf3dddebed9b29a7202/Optimization/AlphabetSoupCharity_optimization.ipynb)
Callback checkpoints for the optimization of the deep learning model; it saves the model's weights every 5 epochs.

## Accuracy of the Deep Learning model
72.34%.

## Summary
- What variable(s) are considered the target(s) for your model?
'IS_SUCCESSFUL' column.
- What variable(s) are considered to be the features for your model?
clean_application_df without 'IS_SUCCESSFUL' column.
- What variable(s) are neither targets nor features, and should be removed from the input data?
'EIN' and 'NAME'columns.
- How many neurons, layers, and activation functions did you select for your neural network model, and why?
Two hidden layers. First layer has 8 neurons with relu activation function. Second layer has 5 neurons with sigma activation function.
- Were you able to achieve the target model performance?
The model reached 72.34% accuracy.
- What steps did you take to try and increase model performance?
Noisy variables were formatted for binning. Additional hidden layer was added. Acivation function of output layer was changed for optimization from sigma to relu. This approach did not improve the accuracy of the model.

