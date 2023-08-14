# lda
A class that performs multiclass classification using linear discriminant analysis which utilizes self made softmax activation function, and maximum liklelihood estiamtion function.
## Techniques used
- Maximum Likelihood Estimation
- LDA
- Softmax Activation Function
- Discriminant Functions
- Supervised Learning
- NumPy


## LDA Class
### Fit Method
- For each class the Fit Method Computes:
  - The mean vectors
  - The covariance matrix for each class using which it creates the shared covariance matrix
  - The weight and bias for each class
  - Likelihood for each class
  - Uses the weights and biases to create a linear decision boundary
### Predict Method
- Computes the discriminant function for each class
- Computes class probabilities using the softmax function
- Assigns the sample to the class with the highest probability
### Softmax Method
- Computes the softmax function
### Likelihood Estimation Method
- Computes the sample's (mean vector's) probability of belonging to each class (likelihood ratio)
