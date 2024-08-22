# Deep Learning Challenge Analysis Report

# Overview of Analysis:
The purpose of this project was to develop a deep learning model which predicts the success of orgainzations funded by Alphabet Soup. The model classified if an organization would be successful based on various features from the dataset. The analysis included data preprocessing, model building, training, evaluation, and optimization to enhance predicative accuracy.

# Results
- Data Preprocessing:
  - The target variable for this model is IS_SUCCESSFUL, which indicates whether an organization was successful.
  - Feature Variable(s):
    - The features used to predict the success include variables such as:
    - APPLICATION_TYPE
    - AFFILIATION
    - CLASSIFICATION
    - USE_CASE
    - ORGANIZATION
    - STATUS
    - INCOME_AMT
    - SPECIAL_CONSIDERATIONS
    - ASK_AMT
 - The following variables were removed as they were neither target variables nor features useful for prediction:
    - EIN
    - NAME

- Compiling, Training, and Evaluating the Model
  -  The model was structured as follows:
    - First Hidden Layer: 100 neurons with ReLU activation.
    - Second Hidden Layer: 50 neurons with ReLU activation.
    - Third Hidden Layer: 25 neurons with ReLU activation.
    - Output Layer: 1 neuron with Sigmoid activation (for binary classification)
  - The layers and neurons were used to balance model complexity and training time. ReLU activation function was used for hidden layers for its effectiveness in deep learning models. The Sigmoid activation was used to predict the probability of success in the model.
  - Model Outcome Performance
    - The final model did not acheive the 75% predictive accuracy, the final model only achieved a 72.64% accuracy prediction.
  - Steps Taken to Increase Model Performance:
    - Increased neurons and added layers to increase the model's capacity to learn more complex patterns
    - Dropout layers were added to prevent overfitting by randomly dropping nearons during the training phase

# Summary
  The deep learning model developed for predicting the success of Alphabet Soup-funded organizations achieved a moderate accuracy of 72.64%. While this is a decent performance, it falls short of the desired accuracy threshold of 75%. A future recommendation would be to    potentially achieve higher accuracy, exploring alternative models such as ensemble methods such as Random Forest or Gradient Boosting or more advanced neural network architectures such as Convolutional Neural Networks. Another recommendation would be to incease the      dataset size to help improve the model accuracy. 
  

