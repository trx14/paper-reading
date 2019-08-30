# Explainable Prediction of Medical Codes from Clinical Text

### Author
* James Mullenbach(gatech) Jimeng Sun(gatech)

### Paper link
* https://www.aclweb.org/anthology/N18-1100

## Objective
* Developed a **CNN based** model for automatic ICD code assignment based on text discharge summaries from intensive care unit(ICU). The motivation is that important information for code assignment usually contained in short snippets of text.
The problem can be seen as a Multi-label problem.

* Difficulty: (1) Large label space, ICD-9 taxonomy has 15,000 codes, 140,000 codes combined in the newer ICD-10-CM.
(2) Small training set problem: some labels only have few training samples.

## Method
* The model architexture is shown below:
![alt text](https://github.com/trx14/paper-reading/blob/master/img/figure1.png)
* First we have de-dimensional pre-trained embeddings for each word in the document. (1) concatenated the document words into a metrix **X = [x1, x2, x3, ..., xN]**. (2) Using convolutional filter W project the X into H. For each label, caculating a attenion vector A for that. Using the A*H get the final embedding vector V. After a fully connect layer and a sigmoid function get the probability Y(0 or 1).

## Result
* content

