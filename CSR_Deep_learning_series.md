# Week 3 Tuning Process

2024/12/25

0000<->0200

# Week 2 Adam Optimization Algorithm

2024/12/25

- adaptive moment estimation
- adam
- high dimensional would more end with saddle point
- problem of plateaus

# Week 2 RMSprop

2024/12/25

0300<->0700 End

- RECORD_WEIGHT 166.2
- disseminate

# Week 2 RMSprop

2024/12/24

0000<->0300

- root mean square propagation

# Week 2 Understanding Exponentially Weighted

2024/12/24

- RECORD_WEIGHT 166.1
- computation and memory efficiency
- momentum terms, from the past, velocity
- accerleration terms
- singnal from the past , present, future

# Week 2 Mini-batch Gradient Descent

2024/12/23

0200<->1100 End

- {1} as batch
- RECORD_WEIGHT 166.8
- nx number of examples
- X{1}, Y{1}
- epoch
- 1 pass through training set
- mini batch size
- batch gradient descent
- mini batch gradient descent
- stochastic gradient descent if size = 1
- keep marching
- stochastic lose speedup from vectorization
- make progress without needing to wait
- small training set, use batch gradient descent
- less than 2000
- typical mini batch size, 64, 128, 256, 512
- make sure minibatch fit in CPU GPU memory
- celcius
- adjust the past average vs value at this moment

# Week 2 Mini-batch Gradient Descent

2024/12/22

0000<->0200

- deep learning work better on big data

# Week 1 Weight Initialization for Deep Networks

2024/12/22

- RECORD_WEIGHT 167.4
- RECORD_GYM 3 times
- gradient checking
- 10^-7 means error small, -3 means error big and possibly wrong

# Week 1 Vanishing / Exploding Gradients

2024/12/21

- squared norm
- 166.9
- keep-prob
- downside
- J is not well defined everywhere
- check if it is still monotonically decreasing
- data augmentation
- early stopping
- dev set error
- orthogonalization of optimize gradient J, and not overfit, introducing L2 and try different lambda, computationally expensive
- early stopping cheap, but not orthogonal
- normalizing training sets

# Week 1 Dropout Regularization

2024/12/20

- inverted drop out
- dropout vector
- np.multiply
- dropout by iteration

# Week 1 Why Regularization Reduces Overfitting?

2024/12/20

- RECORD_WEIGHT 166.1
- penalize
- lambda big, w small, as lambda effect with 1, 1-lambda w

# Week 1 Regularization

2024/12/20

- J cost, is sum of loss function y and y hat
- regularization
- sparse
- setting w to be small
- lambd instead of lambda
- Frobenius norm
- weight decay

# Week 1 Basic Recipe for Machine Learning

2024/12/19

- get rid of bias problem
- if not to test bias, test set can be skipped
- 

# Week 1 Bias / Variance

2024/12/19

- bias variance tradeoffs
- underfitting high bias
- train set error, dev set error comparasion
- train < dev, high variance
- benchmark human error, bayes error
- train > human, high bias

# Week 1 Train / Dev / Test sets

2024/12/19

- domain, application area
- hold out crosss validation
- train, dev cross validation set, test
- 70 30 split
- 60 20 20
- decide algorithm choices on dev set
- million example , 98 train, 1 dev, 1 test
- 99.5 train, .4 dev, . test
- mismatched train/test distribution

--------------------

# Week 4 Building Blocks of Deep Neural Networks

2024/12/18

- cache z[l]
- momentum, minibatch size, regularizations
- no theory to guide how to choose hyper parameters

# Week 4 Building Blocks of Deep Neural Networks

2024/12/17

0000<->0330

# Week 4 Why Deep Representations?

2024/12/17

0400<->1030 End

- shallow network, require exponentially more hidden units
- one layer, exponentially large
- o log n, vs 2^n
- pratically 2^n-1 the similar
- circuit theory

# Week 4 Why Deep Representations?

2024/12/16

0000<->0400

- edges, parcels, faces
- convolutional

# Week 4 Getting your Matrix Dimensions Right

2024/12/16

0500<->1100

- dimension check
- when stacking it, it is stacked column wise

# Week 4 Deep L-layer Neural Network

2024/12/15

0000<->0500

- the input x is also an activation a0

# Week 4 Deep L-layer Neural Network

2024/12/15

0000<->0500 End

- shallow model doesn't work a lot

# Week 3 Random Initialization

2024/12/09

- 165.0
- 0.01 or other small numbers

# Week 3 Backpropagation Intuition (Optional)

2024/12/06

0000<->0500

# Week 3 Gradient Descent for Neural Networks

2024/12/05

- forward propogation
- backpropogation

# Gradient Descent for Neural Networks

2024/12/04

0000<->0200

0000<->0800 end

- conversely
- cost function is formed by lost function

# Activation Functions

0000<->1000

2024/11/29

- tanh function
- sigmoid for the output layer, tan h for the hidden layer
- g[1] may be different from g[2]
- rectified linear unit
- leaky ReLu
- ReLu learning is faster, because of derivative
- sigmoid never used 
- tanh is superior than sigmoid
- default ReLu
- optional leaky ReLu

# Activation Functions

0000<->0500

2024/11/28

- sigmoid function vs activation function

# Week 3 Vectorizing Across Multiple Examples

2024/11/25

0400<->0900 End

- stacking up the lower case xs
- activation of the first hidden unit of the training example
- hidden unit num

https://www.coursera.org/learn/neural-networks-deep-learning/home/week/2

# Week 3 Vectorizing Across Multiple Examples

0000<->0300

2024/11/17

# Week 3 Vectorizing Across Multiple Examples

0000<->0500

2024/11/12

# Module 1 more examples of vectrization

2024/11/06

---

# Module 4

# Structuring Machine Learning Projects Week 1 Single Number Evaluation Metric

2024/11/11

0000<->0300

- precision, recall


# Structuring Machine Learning Projects Week 1 Orthogonalization

- training set, dev set, test set
- to relate back to

2024/11/11

# Structuring Machine Learning Projects Week 1 Why ML Strategy

2024/11/11

- collect more diverse training set
