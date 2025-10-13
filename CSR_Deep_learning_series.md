
# Sequential model
https://www.coursera.org/learn/nlp-sequence-models/lecture/0h7gT/why-sequence-models

# Convolutional NN
https://www.coursera.org/learn/convolutional-neural-networks/lecture/XAKNO/why-resnets-work

# Deep RNNs

2025/10/12

0000<->0200

- [l] layer l
- <t> time t
- neural network with 3 hidden layers

# Long Short Term Memory (LSTM)
2025/10/11

0000<->1000 End

# Long Short Term Memory (LSTM)

2025/10/10

0000<->0500

# Gated Recurrent Unit (GRU)
2025/10/10

1200<->1700 End

# Gated Recurrent Unit (GRU)
2025/10/09

0400<->1400

# Gated Recurrent Unit (GRU)

2025/10/08

0000<->0400

- c memory cell
- firstly train the model, forward and backward, to get w and b
- then sampling novel sequences, to get lines based on the trained w and b

# Vanishing Gradients with RNNs
2025/10/08

0000<->0600 End

- for error to be backpropogated to the beginning position
- long range dependencies
- vanishing and exploding
- gradient clipping

# Sampling Novel Sequences

2025/10/07

0000<->0800 End

- to get what the RNN learned, Sampling Novel Sequences
- keep sampling until EOS
- character level language model
- no UNK
- bad in capturing long range dependencies

# Language Model and Sequence Generation
2025/10/07

1000<->1200 End

# Language Model and Sequence Generation

2025/10/06

0000<->1000

- EOS
- can be attached to every sentence in the corpus
- add period or not add period in the vocabulary
- UNK, analyze the chance of unknown word
- xt=yt-1
- when nothing get inputted, what is the most likely word in the first place, this is to learn a model

# Different Types of RNNs
2025/10/06

0500<->1000 End

- a0
- because you can have one to many and many to one, then why not many to many

# Different Types of RNNs

2025/10/05

0000<->0500

- machine translation
- how does it decide the last Ty

# Recurrent Neural Network Model
2025/10/04

0000<->1500 End

- REVIEWING
- shaded box
- we can compress them by xxx

# Picking the Most Likely Sentence

2025/10/03

0000<->0800 End

- find the prob of Eng sentences condition on Fre sentences
- eng sentence y in maximizing the prob
- beam search
- gready search
- less optimal result given the intention in always choosing the best one
- contemplate

# Basic Models
2025/10/03

0000<->0600 End

- input sequnce x with length a and output sequence with length b
- image captioning

# Debiasing Word Embeddings

2025/10/02

0000<->1000

- Debiasing
- neutralize, gender neutral
- definitional, has gender meaning carried by it
- sorority
- fraternity

# Sentiment Classification
2025/10/02

0200<->0700 End

- ambience
- average and many to 1
- RNN

# Sentiment Classification

2025/09/30

0000<->0200

# GloVe Word Vectors
2025/09/30

0300<->1100 End

- introduce a convention 0log0=0
- learn the weight attachments for each word

# GloVe Word Vectors

2025/09/28

0000<->0300

# Negative Sampling
2025/09/28

0000<->1200 End

- turn 10000 softmax problems to binary classification problem

# Word2Vec

2025/09/27

0000<->1200 End

- plus or minus 10 words window
- context c to target t
- sum of 10 thousand words
- hierachical softmax

# Learning Word Embeddings
2025/09/27

0500<->1000 End

- language model, context
- last few words before the target word
- the one previous word
- nearby 1 word
- this video is for learning a word embedding

# Learning Word Embeddings

2025/09/26

0000<->0700

- TBRT, shift

# Embedding Matrix

2025/09/26

0000<->0400 End

# Properties of Word Embeddings
2025/09/26

0600<->1100 End

- t-SAE

# Properties of Word Embeddings

2025/09/25

0000<->0600

- difference between words
- find the word maximize similarity

# Using Word Embeddings

2025/09/25

0000<->0900 End

- featured representation
- durian
- bidirectional RNN
- learn word embedding from large text corpus
- dense vector
- sparse vector
- transfer learning
- true for many NLP problems
- encoding, embedding

# Bounding Box Predictions
2025/09/24

0500<->1100 End

0000<->0730

0600<->0730

- TBRT?

# Bounding Box Predictions

2025/09/23

0000<->0600

- YOLO, you only looks once

# Convolutional Implementation of Sliding Windows
2025/09/23

0200<->1100 End

- different ways in plaing FCs
- FC may not mean traditional FC, it can also represent other types FC

# Convolutional Implementation of Sliding Windows

2025/09/22

0000<->0200

- to resolve high computational cost issue

# Object Detection

2025/09/22

0000<->0500 End

- sliding windows detection
- 

# Landmark Detection

2025/09/22

0000<->0600 End

- AR and landmark detection
- annotate

# Object Localization
2025/09/22

1000<->1200 End

Unit 2.3: Functions: Abstraction

2025/09/22

0000<->0330

- operating system that has functions

# Object Localization

2025/09/21

0000<->1000

- bounding box
- conditional loss function

# State of Computer Vision

2025/09/20

0000<->0730

- ensembling, doing well on benchmarks

# Data Augmentation

2025/09/20

0200<->0930 End

- color shiftling
- yellowish
- PCA is deemed as advanced
- PCA color augmentation
- distortion
- hard disk, CPU thread
- loading data and implementing distortion
- CPU/GPU training
- augmentation parameters

# Data Augmentation

2025/09/19

0000<->0200

- flip the image
- random cropping

# Transfer Learning

2025/09/19

0000<->0800 End

- training would take several weeks and require many GPUs
- trainable parameter=0, freeze=1
- more data, freeze less layers

# MobileNet Architecture
2025/09/18

0000<->0600

- POOL FC SOFTMAX
- how it works for reduction
- project down

# MobileNet
2025/09/18

0700<->1600 End

- poing wise convolution
- depth wise, point wise

# MobileNet

2025/09/17

0000<->0700

- mobilenet is not computational expensive
- depthwise seperable conolution
- number of filter positions

# Inception Network
2025/09/17

0000<->0800 End

- goo LeNet
- inception paper, knor your meme, we need to go deeper, motivation for deeper neuron networks

# Inception Network Motivation

2025/09/16

0000<->1000 End

0400<->0900

- bottleneck layer

# Inception Network Motivation

2025/09/15

0000<->0700

- reduce it by a factor of 10

# Networks in Networks and 1x1 Convolutions

0000<->0200

0000<->0600

2025/09/15

- 1 1 conv add non linearity

# Why ResNets Work?

0000<->0800 0800<->0900 End

2025/09/14

- learning the identity function
- assuming same dimension z l+2 and al
- padding the a to let a and z on the same dimension
- fc fully connected layer

# ResNets
2025/09/14

0000<->0700 End

- block turned to residual block

# ResNets

2025/09/13

0000<->0300

- Res net allow you to train very deep NN
- short cut, skip connection

# Why ResNets Work?

2025/09/13

0000<->0500 0200<->0900 End

- ResNet guanrantee performance is not hurt instead of helping it
- 

- ReLU 0 or positive
- 

# Bidirectional RNN

2025/09/12

0000<->0500

- BRNN
- backward connection
- both a -> and a<- are forward propogation

# Gated Recurrent Unit (GRU)
2025/09/11

0000<->1700 End

- c memory cell
- ct at the same for GRU
- at stand for output cell
- c tilda is candidate
- u stand for updated weight
- gamma either close to 0 or close to 1
- g for gamma g for gate
- c decide for output, gate decide whether to update it
- don’t update it ; don’t forget what this value was
- gamma r, r stand for relevance

# Gated Recurrent Unit (GRU)
2025/09/11

1200<->1700 End

- use different bits to
- LSTM is another version
- to capture long term dependency

# Gated Recurrent Unit (GRU)
2025/09/10

0700<->1200

- gate times candidate value + 1- gate times old value
- don't forget what this value was

# Gated Recurrent Unit (GRU)
2025/09/09

0200<->0700

- tanh

# Gated Recurrent Unit (GRU)
2025/09/08

0000<->0500

- GRU c
- LSTM
- c is memory cell
- gama u
- TBRT shift 3 mins

# Vanishing Gradients with RNNs
2025/09/07

0200<->0700 End

- KOL and theories behind
- info flow chain
- decrease or increase exponentially
- gradient clipping
- clip based on some maximum values
- vanishing gradient is much harder to solve than gradient exploding

# Vanishing Gradients with RNNs
2025/09/06

0000<->0500

- language and long term dependency
- RNNs can’t handle very long term dependency
- TBRT

# Sampling Novel Sequences
2025/09/05

0300<->0800 End

- space puctuations
- character level language model, word level language model
- pros and cons
- unkown word token
- if mau is not in the vocabulary, then mau is unk
- computation expensive
- word level language model is more popular
- trained from A, then more likely to speak like A

# Sampling Novel Sequences

2025/09/04

0000<->0300

# Language Model and Sequence Generation

2025/09/03

0500<->1000

# Language Model and Sequence Generation

2025/09/02

0000<->0500

- corpus is from NLP

# Language Model and Sequence Generation
2025/09/01

0000<->0500

- sample sequence to generate novel sequence of words
- TBRT

# Language Model and Sequence Generation
2025/08/31

0000<->0500

- P(sentence)=?
- corpus, large set of English sentences
- EOS
- TBRT shift 2 mins

# Language Model and Sequence Generation

2025/08/29

0000<->0100

- language model and sequence generation
- language model and language modeling

# Different Types of RNNs
2025/08/29

0500<->1000

# Different Types of RNNs

2025/08/28

0000<->0500

# Different Types of RNNs

2025/08/27

0000<->0300

- Tx and Ty different
- TBRT

# Backpropagation Through Time
2025/08/27

0400<->0600 End

# Backpropagation Through Time

2025/08/26

0000<->0400

- loss for single prediction

# Recurrent Neural Network Model
2025/08/26

1500<->1600 End

# Recurrent Neural Network Model
2025/08/25

1000<->1500

- aa input a to produce a,  ax input x to produce a, ya input a to produce y
- tanh, relu, sigmoid

# Recurrent Neural Network Model
2025/08/23

0500<->1000

- bracket stand for one hot of each word
- wax, waa
- wya
- bidirectional RNN, BRNN
- used to compute some a quantity

# Recurrent Neural Network Model

2025/08/22

0000<->0500

- bracket stand for one hot vector
- doesn’t share features learned across different positions of text
- is pass onto

# Recurrent Neural Network Model
2025/08/21

0000<->0100

# Notation

2025/08/20

0000<->0500

- search and index names
- round bracket is training example, angle bracket is which word it is
- t element in the i training example
- dictionary

# Notation

2025/08/19

0000<->0200

- index
- name recogntition system, currency name e.g.,
- TBRT

# Why Sequence Models?

2025/08/19

0000<->0300

- sequence
- supervised learning and sequence problems

# CNN
https://www.coursera.org/learn/convolutional-neural-networks/lecture/wfUhx/strided-convolutions

# ResNets

0000<->0700 End

2025/08/18

- vanishing and exploding gradient type of problem

# Classic Networks
1200<->1800 End

2025/08/17

- You can read this paper Alexnet
- deep network is used when there are many channels
- CONV 128 means there are 128 filters
- 138 M parameters, large even by today standards
- parameters need to be trained
- VGG16 does the same as VGG19
- nh nw go down, and nc go up at a factor of 2

# Classic Networks

0700<->1200

2025/08/16

- AlexNet similar to LeNet but much bigger
- GPU communication
- this paper convinced CV communities to take serious look at deep learning

# Classic Networks

0200<->0700

2025/08/15

- 60K parameters
- sigmoid and tanh was used in history, ReLu is nowadays
- constraints in the paper, limitation of computer

# Classic Networks

0000<->0200

2025/08/14

- while the paper was published, average
- nowadays people use max pooling
- back then people didn’t use pooling

# Yann LeCun Interview

2025/08/13

0000<->0500

- perceptron

# Why Convolutions?

2025/08/12

0300<->End

- guess that the filter itself would be updated throughout the backward propagation, but only one filter
- each output value only depend on 9 input instead of the entire picture

# Why Convolutions?
2025/08/11

0100<->0600

- parameters to train, parameter matrix
- filters itself are parameters
- upper left hand, and lower right hand have different distribution
- other pixel doesn’t impact the pixel

# Why Convolutions?

2025/08/10

0000<->0300 0030<->0230

- parameter sharing, and sparse xxx
- 32*32*3 stand for units, cross of different layers, parameters 3072 * 4704
- convolution reduce number of parameters

# Why Convolutions?

2025/08/09

0000<->0500

- weight matrix
- number of parameters
- TBRT
- parameters vs weight?

# CNN Example

0700<->1200 End

2025/08/08

# CNN Example
0500<->1000

2025/08/07

- fully connected unit
- fully connected layer is like normal neural networks

# CNN Example

0000<->0500

2025/08/06

- recognize a digit number
- LeNet-5
- search people get inolved, or new stars
- send emails to them
- one pooling can contain CONV and POOL, because people would consider the layer with weight as a layer

# Pooling Layers

2025/08/05
0500<->1000 End

- do the same computation on that slice
- max pooling computation is done on each repsect
- average pooling

# Pooling Layers

0000<->0500

# Week 1
Simple Convolutional Network Example

2025/08/03

0300<->0800 End

- filter size can also be considered as hyperparameter
- conv layer, pooling layer
- fully connected layer

# Week 1
Simple Convolutional Network Example

2025/08/02

0000<->0500

- HW stand for height and weight

# Week 1
Convolutions Over Volume

2025/08/01

0000<->0500

- 6,6,3 3 stand for color channel
- number of channel in the image has to be the same as number of channel in your filter
- but you can use more than one filter, and stack them all

# Week 1
Simple Convolutional Network Example

2025/07/31

- logistics vs softmax

# Week 1

One Layer of a Convolutional Network

2025/07/30

1000<->End

# Week 1
One Layer of a Convolutional Network

2025/07/29

0500<->1000

- convolution layer

# Week 1
One Layer of a Convolutional Network

0000<->0500

2025/07/28

- In the context of convolutional neural networks (CNNs), a parameter typically refers to the values that the model learns during training. These include:

Weights: Each filter in a convolutional layer has associated weights that are adjusted during training to minimize the error in predictions. The weights determine how much influence each input feature has on the output.

Biases: Each filter also has a bias term, which is added to the output of the convolution operation. This helps the model make better predictions by allowing it to shift the activation function.

# Week 1
Convolutions Over Volume

2025/07/27

0500<->1000

Stride convolution

# Week 1
Convolutions Over Volume

2025/07/26

0000<->0500

# Week 1
Stride convolution

2025/07/25

Begin<->End

# Week 1
Padding

2025/07/25

0500<->1000 End

- solve for p
- f is usually odd, as centric position, and for calculate padding

https://www.coursera.org/learn/convolutional-neural-networks/lecture/4Trod/edge-detection-example

# Week 1 Padding

2025/07/24

0000<->0500

- shrinking output
- throw away info from edge
- valid convolution, no padding
- same convolution

# Week 1
Padding

0000<->0200

2025/07/23

- padding
- TBRT

# Week 1
More Edge Detection

0500<->0800

2025/07/23

- screen chip
- edge detector study to determine how the filter matrix should look like

# Week 1
More Edge Detection

0000<->0500

2025/07/22

- if you convol it
- sobel filter

# Week 1
Edge Detection Example

0500<->1100 End

2025/07/21

- tf.nn.conv2d
- keras
- deep learning framework, tensorflow, keras

# Week 1
Edge Detection Example

0000<->0500

2025/07/20

- filter matrix
- six by six by one, six by six by three
- kernel, filter
- convol denoted as *
- fit a straight line

https://www.youtube.com/watch?v=Mvy5hjAWeZw&list=PLUl4u3cNGP63BZGNOqrF2qf_yxOjuG35j

# Week 1
Edge Detection Example

0000<->0500

- asterisk
- TBRT
- vertical edge detection

https://www.coursera.org/learn/convolutional-neural-networks/lecture/Ob1nR/computer-vision

# Week 1
Computer Vision

2025/07/18

0000<->0500 End

https://www.coursera.org/learn/machine-learning-projects/lecture/jyWpn/build-your-first-system-quickly-then-iterate

# Week 2
Build your First System Quickly, then Iterate

2025/07/15

0000<->0500 End

- build your first system quickly, then iterate it
- initial system quickly and start to see how it was doing
- 144.7

2025/01/11

0000<->1000

- 163.2
- DL algorithms are robust to random errors in the training set


- 163.3

# Week 2 Carrying Out Error Analysis

2025/01/08

- is that worth of your effort
- error analysis, whether it is a draw but recognized as win or some other possibilities
- does error tell you something
- analyse different types of mislabelled

2025/01/08

- 161.2

# Week 1 Improving your Model Performance

2025/01/07

# Week 1 Surpassing Human-level Performance

2025/01/07

- natural perception task

2025/01/07

- 163.0

# Week 1 Understanding Human-level Performance

2025/01/06

- avoidable error, bias
- bayes error
- variance

2025/01/06

- 162.9

2025/01/05

- 163.4

2025/01/04

- 164.4 164.1


# Week 1 Understanding Human-level Performance

2025/01/03

0000<->0300

- human level error as a proxy for bayes error

# Week 1 When to Change Dev/Test Sets and Metrics?

2025/01/03

- RECORD WEIGHT 164.7
- bluryer
- and/or
- bayes optimal error
- best possible error
- map x to y to surpass
- RECORD WEIGHT 164.0
- reduce bias or variance
- bias is benchmark vs training
- variance is training vs dev
- tactics
- bayes error
- avoidable bias human vs training error
- variance

# Week 1 When to Change Dev/Test Sets and Metrics?

2024/01/02

0000<->0200

- metic + dev prefer A, you user prefer B

# Week 1 Single Number Evaluation Metric

2024/01/02

- applied machine learning
- recall among the real target, how much are recognized
- harmonic mean
- take an average on the metrics
- maximize accuracy subject to running time less than XX
- optimizing, satisfying
- wake words, trigger words
- subject to at most 1 false positive in every 24 hours
- have dev and test set from the same distribution
- might be different than
- RECORD WEIGHT 164.7
- choose dev and test from the same distribution and reflect the data you expect to get in the future
- dev test, metric
- 70 30, 60 20 20; 98 1 1

# Week 3 TensorFlow

2025/01/01

- RECORD_WEIGHT 165.4
- 

# Week 3 Deep Learning Frameworks

2025/01/01

# Week 3 Training a Softmax Classifier

2025/01/01

- SoftMax in contrast to hard max
- batch gradient, mini batch, stochastic; when the size of the batch is set as 1

# Week 3 Softmax Regression

2024/12/31

- exponentially weighted average

# Week 3 Why does Batch Norm work?

2024/12/31

- RECORD_WEIGHT 167.4
- unlikely event

# Week 3 Why does Batch Norm work?

2024/12/30

0000<->0500

- sorting, classification, fit a straight line
- covariant shift

git.md

https://www.coursera.org/videos/packt-advanced-git-and-github-practices-tgusu/gtbLs?

2024/12/30
- git push origin master


https://www.coursera.org/videos/packt-git-essentials-for-beginners-ctjoh/KVxte?

2024/12/30

# Week 3 Fitting Batch Norm into a Neural Network

2024/12/30

0000<->1200 End

- one epoch is one time of going through all the mini batches?
- b is not needed after the norm step
- RECORD_WEIGHT 166.4

# # Week 3 Derivatives of Activation Functions

2024/12/29

# Week 1 Vanishing / Exploding Gradients

0300<->0600

2024/12/29


0200<->0600

2024/12/29

0000<->0600

2024/12/29

- RECORD_WEIGHT 166.7

# Week 3 Normalizing Activations in a Network

2024/12/26

- batch norm, take norm on each mini batch of data

# Week 3 Using an Appropriate Scale to pick Hyperparameters

2024/12/26

- from the last slide
- diverge
- panda strategy, caviar strategy
- application dependence

# Week 3 Tuning Process

0200<->0700 End

2024/12/26

- RECORD_WEIGHT 166.6
- RECORD_EXERCISE * 3
- coarse to fine

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
