## Titanic: Machine Learning from Disaster
**Goal**- Predicting the Survival of Titanic Passengers.
1. Dataset Details-
   * The training-set has 891 examples and 11 features + the target variable (survived).
   * Features - 'PassengerId', 'Survived', 'Pclass', 'Name', 'Sex', 'Age', 'SibSp', 'Parch', 'Ticket', 'Fare', 'Cabin', 'Embarked'
2. Approach-
   * Data preprocessing-Converting categorical data into numerical data,Importance of each feature on output label,dropping irrelevant features.
   * Problem can be solved using different Machine learning classification techniques such as Stochastic Gradient Descent, Random Forest, Logistic Regression, K Nearest Neighbor, Linear Support Vector Machine, Decision Tree but here MLP-multilayer perceptron is used to solve the problem.
   * Network Architecture- 5 FC layers are used with 16,8,8,4 units respectively in 4 layers with activation function as 'RELU' and 1 neuron in last layer with 'Sigmoid' activation.
     
    
