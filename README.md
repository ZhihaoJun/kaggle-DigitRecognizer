# kaggle DigitRecognizer
## TODO
1. read train data √
 * use panda lib √
2. signle image visualization √
 * use matplot lib √
3. handle data √
 * vectorize label √
4. simple bp nerual network 
 * sigmoid function √
  * sigmoid gradient √
 * feedforward √
 * cost function √
  * regularized √
 * back propagation
  * random start √
  * Set the input layer’s values (a(1)) to the t-th training example x(t) √
  * err3 √
  * err2
  * Accumulate the gradient
  * Obtain the (unregularized) gradient
 * gradient checking
 * regularized back propagation
 * learning parameters
5. evaluate algorithm
6. cnn rnn or dnn

## bp
input 28*28 = 784 + 1(bias) row vector 1x785 marked as x  
hidden 1000  
output 10 = [0..9] marked as y  

theta1 is 785x1000  
theta2 is 1001x10  

### forward

```
z1 = x*theta1
a1 = sigmoid(z1)
z2 = a1*theta2
y = a2 = sigmoid(z2)
label = max index of y
```
