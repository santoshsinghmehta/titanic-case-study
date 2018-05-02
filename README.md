# titanic-case-study
We all know about the Titanic disaster. The ship collided with an iceberg during its maiden voyage from Southampton to New York City. There were an estimated 2,224 passengers and crew aboard the ship, and more than 1,500 died, making it one of the deadliest disasters in modern history.

Scientists have collected data for a fraction of total passengers and marked if they survived the disaster or not. You can access it here-: https://gist.github.com/avmain/284b549eabc13061ce2b0b58b163c7f9.

Provided the details of a new passenger your task is to study the dataset and design a Machine Learning model to classify, if the passenger survived the disaster or not.

# Here's a brief description of all the features: 
- **PassengerId :** An unique index for passenger rows. It starts from 1 for first row and increments by 1 for every new rows.
- **Survived :** Shows if the passenger survived or not. 1 stands for survived and 0 stands for not survived.
- **Pclass :** Ticket class. 1 stands for First class ticket. 2 stands for Second class ticket. 3 stands for Third class ticket.
- **Name :** Passenger's name. Each name has a prefix title like "Mr" for man, "Mrs" for woman, "Miss" for girl and "Master" for boy.
- **Sex :** Passenger's sex. It's either Male or Female.
- **Age :** Passenger's age. "NaN" values in this column indicates that the age of that particular passenger has not been recorded.
- **SibSp :** Number of siblings or spouses travelling with each passenger. That is the count of the offsprings and better halves.
- **Parch :** Number of parents or children travelling with each passenger. That is the count of the family members related by blood.- 
- **Ticket :** Ticket number
- **Fare :** How much money the passenger has paid for the travel journey.
- **Cabin :** Cabin number of the passenger. "NaN" values in this column indicates that the cabin number of that particular passenger has not been recorded.
- **Embarked :** Port from where the particular passenger was embarked/boarded.

# data analysis 
- **Statistical Analysis of Data :** We try to find relations between different features. The idea is to find and retain the features which help describe the main characteristics of the data set.
- **Visual Analysis of Data :** We plot graphs and charts to analyse the data better. The idea is to find patterns amongst the features which describe the data set in the best possible way.


# Import these modules:-
```
pandas
matplotlib
seaborn
sklearn
Imputer
LabelEncoder
OneHotEncoder
train_test_split
LogisticRegression
accuracy_score  
KNeighborsClassifier
GaussianNB
DecisionTreeClassifier
RandomForestClassifier
```   
