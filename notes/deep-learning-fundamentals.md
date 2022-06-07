# Nodes

## what is deep learning

* AI -> ML -> DL
* Turning data into numbers, then find the pattern inside it. Then we can use the pattern to predict things.
* Traditional approach: we figure out input & rules, then we get output; ML approach: we have input and expected ouput, the code figure out the rules.

## Why need it?

* because the rule is complicated. we can't figure it out in a reasonable cost.
* because the rules are changing, you need to redo a lot of work.
* big data, which cause long list & complicated rules

## DL is not fit for

* need explain why
* can't tolerate with errors
* when we can use rules to resolve it
* when you don't have data for DL

## ML vs DL
* structured data vs unstructured data

## configure VSCode to support jupyter notebook
* Reference: https://techbrij.com/setup-tensorflow-jupyter-notebook-vscode-deep-learning

## set_seed, get random number
1. global-level: get same value in different session, but different value in same session
2.  op level: different value in same session, but same value in differnt session

## import attributes
* Rank: the number of dimension, tf.ndim
* shape: how many elements in each dimension? tf.shape
* axis or dimension: a particular of a dimension, tf[0][1]
* size: the total number of elements; tf.size(a)

## Neural Networks Regression

### Steps to create a model in tensorflow

1. creating a model: define input, output and hidden layers 
2. compiling a model:
    * loss function: tell how wrong the model is
    * optimizer: tell model how to improve the patterns
    * evaluation metrics: interpret the performance of model
3. fitting model: let the model find the patterns

## ways to improve model

1. During create: add more layers and change activation function of each layer
2. During compiling: change the optimizer function or the learning rate
3. During fit: train more, epoch

## Evaluation Model

### 3 datasets
1. Training set: 80% data set
2. Validation set: 10-15% data set
3. Test set: 10-15% data set

### export Model
1. model.save('file.h5'), then tf.keras.models.loadmodel(file)

### early stop
* we can stop trainning when some metrics didn't improve anymore

### Linear & Non-Linear problem
activation function (linear, sigmoid, relu)