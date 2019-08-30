# LEAP: Learning to Prescribe Effective and Safe Treatment Combinations for Multimobidity.

### Author
* Yutao Zhang(Tsinghua) Jimeng Sun(gatech)

### Paper link
* http://keg.cs.tsinghua.edu.cn/jietang/publications/KDD17-Zhang-et-al-LEAP-DL-pred-Healthcare.pdf

## Objective
* In this work, the objective is to learn a prediction model from an EHR that take a set of disease conditions as input 
and gives a set of medications and their mappings to those disease conditions. This is a Multi-instance and Multi-label problem.

* difficulty: There have drug-drug/ drug-disease/ disease-disease interactions and different mapping situations: one-one mapping, many-one, many-many.
![](https://github.com/trx14/paper-reading/blob/master/img/Screen%20Shot%202019-08-30%20at%2011.44.02.png)

## Method
* (1) using a RNN based model to model label dependency, using an atteniton mechanism to map label-instance dependency.
* The model is shown below:
![](https://github.com/trx14/paper-reading/blob/master/img/Screen%20Shot%202019-08-30%20at%2011.44.10.png)
* This model can't avoid all adverse drug interactions. Because the training set didn't have negative training samples.
This paper propose fine-tuning model via model-free reinforcement learning. They sellected many pairs from the training set. The reward comes from two parts. (1)the prediction quality, according to the similarity. (2)Avoid adverse, if the prediciton contain some adverse interaction, the reward will be zero.

## Result
* content

