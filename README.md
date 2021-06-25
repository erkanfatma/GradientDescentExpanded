## Gradient Descent
 
 If the problem needs to find minimum of a function, the derivative will be set to the zero and solve the equation for the parameters. These search for minimum is done by using a method called gradient descent. Gradient descent operations begin at a random place in a parameter space. Then, iteratively reduces the error until find to the local minimum. The aim of the gradient descent method is “how to minimize error?”. 

 ## Batch Gradient Descent
 
 Batch gradient descent calculates all training set at each step as a result. The method is too slow for large training data. So that, it is very expensive to work with batch gradient descent. Batch gradient descent is fine for convex error manifolds. In addition to these, the behavior of the function is also depending on the number of features of the dataset.
 
 ## Stochastic Gradient Descent 
 
 Stochastic gradient descent is used to solve the problem in the batch gradient descent that is used to train the system with whole training data to calculate gradients in each step. Stochastic gradient descent selects a random instance of the training data at each step and calculates the gradient to make the operation faster. There is small data to manipulate at a time. So, the method is much faster than the batch gradient descent.
Batch gradient descent is not suggested for large training data samples. On the other hand, stochastic gradient descent can be used for huge training data samples. Batch gradient descent gives optimal solution for given
 
## Mini-Batch Gradient Descent

Mini batch gradient descent splits training data into small batches to calculate model error and edit model coefficients. The frequency of model is updated is higher than the other gradient descent algorithms. It does not get the whole data; it just gets the small amount of data such as 50 data and uses them for optimization. The method updates the model more efficient than the stochastic gradient descent.

## Results 

Gradient descent algorithms are one of the most popular algorithms for optimization. It is also most common way to optimize neural networks.
Depend on comparison of batch gradient descent, stochastic gradient descent, and mini-batch gradient descent, the best optimizer depends on the size of training data. For small dataset, batch gradient descent gives a good solution for the problem. On the other hand, if the dataset is too huge, stochastic gradient descent is much more useful than the batch gradient descent. In addition to these, stochastic gradient descent selects a single data from the training dataset to get solution. However, mini-batch gradient descent method selects a small part of the dataset and it optimizes it depend on the subset dataset. To sum up, the methods are selected depend on the dataset size and properties. Following diagram shows the different between them more clearly.

![alt text](https://github.com/erkanfatma/GradientDescentExpanded/blob/main/img/picture1.png)
