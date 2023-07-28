# Charity Funding Prediction Optimization

**Overview**

* The goal of this analysis is to create a neural networks deep learning model that can predict the success of funding applications for Alphabet Soup, a charitable organization. The model was trained on a dataset that includes different features like application type, affiliation, classification, use case, organization type, income amount, and other relevant information.

**Results**

Data Processing:
* The model's target variable was the "IS_SUCCESSFUL" column, which determined whether an application was successful (1) or not (0).
* The features entailed columns such as "APPLICATION_TYPE," "AFFILIATION," "CLASSIFICATION," "USE_CASE," "ORGANIZATION," "INCOME_AMT," and others.
* I removed the "EIN" and "NAME" columns from the input data as they were not relevant as targets or features.

Compiling, Training, and Evaluating the Model:
* The neural network had 3 hidden layers with 9, 18, and 36 neurons. ReLU was used as the activation function and Sigmoid for the output layer. Binary cross-entropy was the loss function and Adam optimizer was used for compiling.
* I trained the model for a total of 858 epochs. The model achieved a loss of 0.7866 and an accuracy of 0.4530,indicating poor performance.
* I increased the test size and still achieved high loss. 

**Summary**

The model is currenly not performing at its best, but there are several ways to enhance its performance. Hope to improve the model's performance by experimenting further, analyzing data, and adjusting hyperparameters.


