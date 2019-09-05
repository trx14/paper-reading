# Men Also Like Shopping

### Author
* jieyu Zhao(UCLA) Kai-Wei Chang(UCLA)

### Paper link
* https://arxiv.org/pdf/1707.09457.pdf

## Objective
* Reducing gender bais Amplification in Structure ouput problem. 
## Identifying bias ##
* First the paper degine the bias score of a given output. For example, the bias towards man for verb b as:
![](https://github.com/trx14/paper-reading/blob/master/img/Screen%20Shot%202019-09-05%20at%2011.59.43.png)
## Evaluating bias amplification ##
* The paper find after model prediction. The some test bias distrubution will be amplify. For example, the rate for woman with cooking is 0.2 in training set. However, in test result, the rate for woman with cooking will be 0.3. The detail figure show below:
![](https://github.com/trx14/paper-reading/blob/master/img/Screen%20Shot%202019-09-05%20at%2011.59.59.png)

## Method
* Lagrangian relaxation. (Adding regularization in training process)

## Result
* content
