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
* size: the total number of elements