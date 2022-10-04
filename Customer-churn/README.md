# Outflow of bank customers

Clients began to leave Beta-Bank. Every month. A little, but noticeable. Banking marketers figured it was cheaper to keep current customers than to attract new ones.
It is necessary to predict whether the client will leave the bank in the near future or not. I have been provided with historical data on customer behavior and termination of agreements with the bank.
Build a model with an extremely large F1-measure. It is necessary to bring the metric to 0.59.


- Loading and preparation of data.
- Study of the class balance, training the model without taking into account the imbalance. Brief description of findings.
- Improving the quality of the model, given the imbalance of classes. Training different models and finding the best one.
- Testing: final testing.

***Signs:***
- `RowNumber` - row index in the data
- `CustomerId` - unique customer ID
- `Surname` - surname
- `CreditScore` - credit rating
- `Geography` - country of residence
- `Gender` - gender
- `Age` - age
- `Tenure` - how many years a person has been a client of the bank
- `Balance` - account balance
- `NumOfProducts` - the number of bank products used by the client
- `HasCrCard` - the presence of a credit card
- `IsActiveMember` - client activity
- `EstimatedSalary` - estimated salary
- ***Target feature***
- `Exited` - the fact that the client left
