# US Airline Passenger Satisfaction and Loyalty Prediction

The dataset presents a view of passenger experiences and satisfaction levels with various aspects of airline services. The shape of the database (satisfaction_2015) is (129880, 24). 
●	Customer satisfaction prediction: Predict the satisfaction levels of passengers based on the various service dimensions and personal preferences. This could help in identifying key factors that drive satisfaction and areas needing improvement.
●	Churn prediction for disloyal customers: Identify patterns and factors leading to customer disloyalty. By predicting which customers are at risk of becoming disloyal, airlines can implement strategies to improve their experience and retain them.

### High-Level Solution Overview 
Step 1: Data Preparation
We will clean the data to ensure that it is suitable to run through our model. This includes replacing or deleting missing values, doing preliminary data analysis, ensuring our data is formatted correctly, and selecting or dropping features as needed.

Step 2: Model Training
We will start with simple models to train our data on first, like logistic regression and decision trees, then segue into more complicated models, like neural networks, to compare evaluation metrics between models. 

Step 3: Model Improvement
We will consider accuracy as our main evaluation metric. We will also evaluate whether our model might be making assumptions incorrectly, based on inconsistencies in the data or flawed model formatting. Depending on the type of model we are using, we will adjust our hyperparameters in order to improve our main evaluation metrics.
