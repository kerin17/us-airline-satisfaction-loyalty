# US Airline Passenger Satisfaction and Loyalty Prediction

The project leverages machine learning to predict airline passenger satisfaction and identify the key features contributing to customer loyalty. Utilizing passenger survey data, the project seeks to enable the airline to modify its services to enhance passenger experience and loyalty.

## Prediction 1 
Model Development and Evaluation: Five models were evaluated for predicting passenger satisfaction: Logistic Regression, Decision Tree, SVM, Random Forest, and Gradient Boosting, with accuracy scores of 0.883, 0.914, 0.883, 0.963, and 0.957, respectively. Random Forest, which had the highest accuracy, was further refined using GridSearchCV, leading to optimal parameters of max_depth 15 and max_features 13. It also achieved the top AUC score of 0.994. The Mean Decrease Impurity (MDI) identified influential features like Online Boarding, Inflight WiFi, and Business Class, which aligned with patterns observed during the Exploratory Data Analysis (EDA) indicating higher satisfaction among business class and long-distance travelers.

## Prediction 2 
Model Development and Evaluation: Customer loyalty was analyzed using several models, with Random Forest and Gradient Boosting performing best, likely due to their effectiveness in handling large datasets. Key factors influencing loyalty included flight distance, age, travel type, and satisfaction, with business travelers showing higher loyalty. Other factors like easy booking, online boarding, and convenient flight times also significantly impacted loyalty. The analysis suggests that enhancements in customer service aspects such as booking ease and airport navigation could significantly affect loyalty retention.


## Insight and Recommendations
[hide]

## Limitations
The analysis and dataset face limitations primarily due to the age of the data, having been recorded in 2015, which reduces its applicability to current real-life scenarios without tests on
more recent or new data. Additionally, the presence of multicollinearity among some variables may complicate the interpretation of the results. To enhance the model effectiveness, conducting churn analysis or entering loyalty memberships with data from various time periods is recommended, which would provide insights into changing patterns over time and improve the relevance and accuracy of the findings.
