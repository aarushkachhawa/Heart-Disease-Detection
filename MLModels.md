| [Datasets](./Datasets.md)       | [Data Analysis](./DataAnalysis.md)      | [Machine Learning Models](./MLModels.md)      | [Results](./Findings.md)         |

# Machine Learning Models 

## Artificial Neural Network 

The neural networks have proven to be the most
popular and evolving branch of machine learning in recent
studies. In this project we'll use the neural
network algorithm multi-layer perceptron (MLP) to train and
test the dataset.
 Multi-layer perceptron algorithm is a supervised
neural network algorithm in which there is one layer for
the input, one for the output and one or more hidden layers between these two layers. Each node in the input layer is
connected to output nodes through the hidden layers. The
connections between any two nodes are assigned weights to it
and the resultant input is calculated using the following formula

<img width="194" alt="Screen Shot 2022-02-24 at 10 21 24 PM" src="https://user-images.githubusercontent.com/85214375/155665041-4369958b-424d-4ba9-9eb6-29d5f72227e9.png">

Where xi is the ith input and wi is the corresponding weight.
There is another identity input with weight b called as **Bias**,
which is added to the node to balance the perceptron. The
connection between the nodes can be either feedforward or
feedback based on the requirement. The activation function is applied on the weighted input to get
the output. The role of hidden layer is to connect the input and
output layer and to process the data internally.

<img width="608" alt="Screen Shot 2022-02-24 at 10 20 05 PM" src="https://user-images.githubusercontent.com/85214375/155665128-ddbdac68-b554-4338-906a-07a4df90f7e5.png">


## Random Forest Classifier
Random forest is a supervised learning algorithm in which an ensemble of decision trees is built using the input data. The "forest" refers to the collection of decision trees that are used together to get a more accurate and stable prediction. The decision trees are usually trained with the “bagging” method. The general idea of the bagging method is that a combination of learning models increases the overall result.

<img width="611" alt="Screen Shot 2022-02-24 at 10 34 13 PM" src="https://user-images.githubusercontent.com/85214375/155666676-8b74a5c3-a8be-40d1-b36b-f7fa07a1263c.png">


## Logistic Regression
Logistic regression is used to predict the categorical dependent variable with the help of independent variables. The output of Logistic Regression problem can only be between 0 and 1. Logistic regression can be used where the probabilities between two classes is required. For example, whether it will rain today or not, either 0 or 1, true or false etc. Logistic regression is based on the concept of Maximum Likelihood estimation. According to this estimation, the observed data should be most probable. In logistic regression, we pass the weighted sum of inputs through an activation function that can map values between 0 and 1. The activation function is also known as sigmoid function and the curve obtained is called the sigmoid curve or S-curve. 

<img width="498" alt="Screen Shot 2022-02-24 at 10 46 47 PM" src="https://user-images.githubusercontent.com/85214375/155667938-6a3679ba-ba14-4774-816c-9cdc8fe3ecd9.png">


## Gradient Boosting
In gradient boosting decision trees, we combine many weak learners to come up with one strong learner. The weak learners here are the individual decision trees. All the trees are conncted in series and each tree tries to minimise the error of the previous tree. Due to this sequential connection, boosting algorithms are usually slow to learn, but also highly accurate. In statistical learning, models that learn slowly perform better.

