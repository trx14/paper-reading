# RETAIN：An Interpretable Predictive Model for Healthcare using Reverse Time Attention Mechanism

### Author
* Edward Choi Jimeng Sun(Gatech)

### Paper link
* https://papers.nips.cc/paper/6321-retain-an-interpretable-predictive-model-for-healthcare-using-reverse-time-attention-mechanism.pdf

## Objective
* Using two level attention mechanism to help model improve accuarcy as well as offer some interpretations. The recurrence of RETAIN model is on the attention generation compoents. This make the input X don't participate the attention caculate directly. Hence it will be possible to caculate the contribution coefficient for the input value. As blow figure shows:
![](https://github.com/trx14/paper-reading/blob/master/img/retain_1.png)
![](https://github.com/trx14/paper-reading/blob/master/img/retain_3.png)
* By projecting the X into V(simple method), X and the attention value are seperate, which make the model more interpretable.

## Method
* Model structure show below:
![](https://github.com/trx14/paper-reading/blob/master/img/retain_2.png)
* There are two attentions, one for vist level(scalar attention, alpha), anothor for item in one vist(vector attention, beta).
* It should be noted that the input sequence was inverse. This could help model synthesize different attention value.

## Result
* content
