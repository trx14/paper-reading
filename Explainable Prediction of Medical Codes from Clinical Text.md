# Explainable Prediction of Medical Codes from Clinical Text

### Author
* James Mullenbach(gatech) Jimeng Sun(gatech)

### Paper link
* https://www.aclweb.org/anthology/N18-1100

## Objective
* Developed a CNN based model for automatic ICD code assignment based on text discharge summaries from intensive care unit(ICU). The motivation is that important information for code assignment usually contained in short snippets of text.
The problem can be seen as a Multi-label problem.

* Difficulty: (1) Large label space, ICD-9 taxonomy has 15,000 codes, 140,000 codes combined in the newer ICD-10-CM.
(2) Small training set problem: some labels only have few training samples.

## Method
* The model architexture is shown below:
![architecture] (https://github.com/trx14/paper-reading/blob/master/img/figure1.png)

## Result
* content

