# Ensuring Fairness in Machine Learning to Advance Health Equity

## Objective
* To ensure fairness in Machine learning.

## Method
* Biases in model design
*Label bias: A label that does not mean the same thing for all patients because it is an imperfect proxy that is subject to health care disparities rather than an adjudicated truth. This is a generalization of test-referral and test-interpretation bias in the statistics literature.
Cohort bias: Defaulting to traditional or easily measured groups without considering other potentially protected groups or levels of granularity (e.g., whether sex is recorded as male, female, or other or more granular categories).

* ##Biases in training data##
Minority bias: The protected group may have insufficient numbers of patients for a model to learn the correct statistical patterns.
Missing data bias: Data may be missing for protected groups in a nonrandom fashion, which makes an accurate prediction hard to render (e.g., a model may underdetect clinical deterioration in patients under contact isolation because they have fewer vital signs).
Informativeness bias: Features may be less informative to render a prediction in a protected group (e.g., identifying melanoma from an image of a patient with dark skin may be more difficult).
Training–serving skew: The model may be deployed on patients whose data are not similar to the data on which the model was trained. The training data may not be representative (i.e., selection bias), or the deployment data may differ from the training data (e.g., a lack of unified methods for data collection or not recording data with standardized schemas).
Biases in interactions with clinicians

* Automation bias: If clinicians are unaware that a model is less accurate for a specific group, they may trust it too much and inappropriately act on inaccurate predictions.
Feedback loops: If the clinician accepts the recommendation of a model even when it is incorrect to do so, the model's recommended versus administered treatments will always match. The next time the model is trained, it will learn to continue these mistakes.
Dismissal bias: Conscious or unconscious desensitization to alerts that are systematically incorrect for a protected group (e.g., an early- warning score for patients with sepsis). Alert fatigue is a form of this.
Allocation discrepancy: If the protected group has disproportionately fewer positive predictions, then resources allocated by the predictions (e.g., extra clinical attention or social services) are withheld from that group.
Biases in interactions with patients

* Privilege bias: Models may be unavailable in settings where protected groups receive care or require technology/sensors disproportionately available to the nonprotected class.
Informed mistrust: Given historical exploitation and unethical practices, protected groups may believe that a model is biased against them. These patients may avoid seeking care from clinicians or systems that use the model or deliberately omit information. The protected group may be harmed by not receiving appropriate care.

* Agency bias: Protected groups may not have input into the development, use, and evaluation of models. They may not have the resources, education, or political influence to detect biases, protest, and force correction.
Distributive justice options for machine learning
Equal patient outcomes: The model should lead to equal patient outcomes across groups.
Equal performance: The model performs equally well across groups for such metrics as accuracy, sensitivity, specificity, and positive predictive value.
Equal allocation: Allocation of resources as decided by the model is equal across groups, possibly after controlling for all relevant factors.

## Result
* content
