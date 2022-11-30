# Lecture 1
## REX 1 2022/09/20

2022/09/20

5800<->End

- GPU is one of the decision, more GPU to run code more
- if collecting more data, if using another algorithm
- mlyearing.org
- unsupervised learning application, google news
- 10730 mins, other applications of unsupervised learning
- learn analogy is also a application of unsupervised learning
- enforcement learning 11300 mins

2022/09/14

4025<->5800

- visualize classification problem in 2 D chart ad 1 D chart
- supervised learning, x and y are given to train
- 1 lane road, 2 lane road, intersection


# Lecture 2
## REX 1 2022/10/09

## REVIEW 1 2022/10/12

2022/10/12
6800<->7648

- normal equation is has element on the 2 sides of the equal sign

2022/10/09

6621<->End

- 10700 mins, collection the formula, otherwise it might affect understanding
- matrix computation of the linear equation
- 11630 mins normal equation
- one step to get the global minimum
- TBR linear algebra normal equation section and compare

2022/10/08

5121<->6621

- neuro network is not linear
- normal equation, one step lead you to the global optimal
- linear algebra course and this course 5500 mins
- theta belongs to R^n+1
- raw number
- if A is square matrix, trace of A = sum of diagnal entries
- tr A
- det A equals to multiply of diagnal lambda??forget
- fA = trAB then derivative of A = B^T
- 10623 mins, trace properties

2022/10/07

3621<->5121

- batch gradient descent
- when the data set is large, the batch gradient descent would be time consuming
- stochastic gradient descent
- batch is about using all example from the data set just for every one step, and repeatedly
- stochastic gradient never converge, but it is faster
- monitor cost function, which is Jtheta

2022/10/06

2221<->3621

- the theta is the unknown, thus each row from the dataset is the supply that would determines the derivative of the function
- 3217 mins, redo all the diavation, means finishing all the interation of the training examples

2022/10/02

3500<->3900

- theta 0 equal 0, theta 1 equal 0
- iteration by iteration, theta 0 and theta 1 will be changed
- it is different with OLS
- which determines that it is a ML course instead of statistics course
- QA answer why subtract derivative

2022/09/28

2000<->3500

- you have m training examples, so you need to take partial derivative for all those m training examples, theta j = theta j minus simgma of m of partial derivatives
- repeat until convergence
- no local optimal

2022/09/23

1500<->2000

- minimize square difference
- cpls investigation
- 1/2 is to make the math simpler
- gradient descend

2022/09/22

0000<->1500

- input training set output a hypothesis
- how to represent hypothesis
- notations
- how to choose parameter theta

# Lecture 3

2022/10/24

11400<->End

- 11600 mins, linear transformation
- matrix, rotate space or scale your space
- rot 1, scale 2, rot 2, breaking a matrix, decomposition
- eidgun decomposition, rotation scaling complex, rotation inverse
- svd, rotation 1 scaling real, rotation 2, orthonormal diagnal, orthonal
- sum of eigen value = trace of diagnal
- PI of eigen value = determinant
- 12430 mins, ration, determinant

2022/10/23

5900<->11400

- projection matrix, solve linear
- THETA belongs to Rn, space for parameter
- y belongs to Rm
- 10200 mins, understand column space again
- 10800 mins understand the column space
- going back to gradient descent, if y is in the column space, the error can be achieved at 0

2022/10/22

4400<->5900

- bi jection
- input space is row space, output space is column space
- A inverse translate the output space back to the input space, in this case
- outer product, inner product

2022/10/21

3000<->4500

- calculus, start from 3000, f Rn->R
- cost function is f Rn->R, 1st order, gradient Rn->Rn, 2nd gradient Sn Hession
- Rm->Rn, NN layer
- Rmn jacobian, Rnnn T
- kernel methods to measure similar examples
- 4100 bijection, full rank
- 4200 mins, rank 2, create bijection from one plane sub space to another plane sub space
- 4420 mins, there will be some point is inaccessible given the input space and output space
- column space row space? TBRT 4500 mins

2022/10/19

1500<->3000

- 1602 mins, rank 2 matrixes
- min(m,n,k)
- 2000 mins, different way of thinking matrix vector mutiplication
- 2450 mins, rank
- Sn symmetric matrix
- 2700 mins, why LA?
- think data as matix in Rmn
- probability, covariance matrix, gaussian covariance matrix
- 1think data set as matrix in Rmn 2 probability 3 calculus optimization
- f R->R

2022/10/18

0000<->1500

- notation, vector Rn
- 0950 trace is sum of diagnal elements, SIGMA Aii
- inner product
- dot product is positive, similar in some sense, dot product is negative, not similar in some sense
- 1347 mins outer product
- vuT outer product, give you a matrix of m by n
- outer product matrix is rank 1 matrix? TBRT?

# Lecture 4

2022/11/28

1500<->3000

- probability is not conditioned on theta, it is conditioned on xi, so P(y|x;theta), use semicolon

2022/11/26

1500<->3000

- the bigger the tao, the sharper the slope, the overfitting
- fatter thinner curve
- to choose the square error instead of to the 4th power
- unmodeled effects, random noise
- 2800 mins, the formula yi = thetaTx + epsilon implies a probability

2022/11/25

0000<->1500

- define x1=x and x2=x^2 or sqrt (x)
- fixed set of parameters, parametric
- non parametric learning algorithm
- computer memory
- fit theta to minimize SIGMA wi times yi-thetaxi square
- because for each type of prediction, you need to fit theta to minimize a modified cost function
- so you have to keep the data in the memory
- non parametric, amount of data you need to keep grows linearly with the size of data

2022/11/24

1500<->3000

- the change of tao will affect overfitting and underfitting
- P nipselon can be integratd to 1
- 2900 mins theta times x i is mean???

2022/11/23

1500<->3000

- tao, bandwidth
- TBRT
- IID implies that
- RV. mean, variance
- parameterized by
- frequentist, bayesian

2022/11/22

0000<->1500

- locally weighted regression
- feature selection algorithms
- parametric learning algorithm
- non parametric learnin algorithm
- amount of data/parameter you need to keep growth linearly with size of data
