Business Understanding

The government is preparing itself to prevent avoidable car accidents in order to reduce the care accident severity issues. This is possible with the methods that will help in the following features such as alerting the drivers, police informing them to be more careful in critical situations and also letting the drivers know the weather conditions and visibility conditions.
In most of the accident cases the main reason happens to be the driver not paying attention during driving  due to lack of sleep And alcohol consumption. The other reasons for the accidents are high speed.
The target audience of this project are the government and the other officials who will help in controlling the accidents occurring in the society for the betterment of the public. This model is going to help the target audience to have an insight so to reduce the number of accident and injuries in the society.

Data Understanding

The data consists of 37 independent variables and 194,673 rows. The dependent variable, “SEVERITYCODE”, contains numbers that correspond to different levels of severity caused by an accident from 0 to 4.
Our predictor or target variable will be 'SEVERITYCODE' because it is used measure the severity of an accident from 0 to 5 within the dataset. Attributes used to weigh the severity of an accident are 'WEATHER', 'DRIVER CONDITION’ and ‘ROAD CONDITION’
Severity codes are as follows:

0: Little to no Probability (Clear Conditions)

1: Very Low Probability — Chance or Property Damage

2: Low Probability — Chance of Injury

3: Mild Probability — Chance of Serious Injury

4: High Probability — Chance of Fatality


Extract Dataset & Convert

The data is not fit for analysis therefore features should be changed to numerical type from object type.
With the new columns, we can now use this data in our analysis and ML models!

Balancing the Dataset

Our target variable should be balanced perfectly for the correct results to occur.

Methodology

Our data is now ready to be fed into machine learning models.

We will use the following models:

K-Nearest Neighbor (KNN)

KNN will help us predict the severity code of an outcome by finding the most similar to data point within k distance.

Decision Tree

A decision tree model gives us a layout of all possible outcomes so we can fully analyze the consequences of a decision. It context, the decision tree observes all possible outcomes of different weather conditions.

Logistic Regression

Because our dataset only provides us with two severity code outcomes, our model will only predict one of those two classes. This makes our data binary, which is perfect to use with logistic regression.

Train/Test Split

We will use 30% of our data for testing and 70% for training.

Results & Evaluation

Now we will check the accuracy of our models.

Conclusion

Based on the report it is evident that the weather has an impact on the accidents along with the driver’s state of mind while driving the vehicle.

