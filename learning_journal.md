## Session 1

Today I learned:
- How to interpret box plots.
- Why fraud datasets should not automatically remove outliers.
- How to think about Git commits as milestones rather than save points.
- How to interpret correlations from a business perspective.

Questions for next session:
- How do we identify the most important features before training models?

## interview question
Why Is It Called "Random" in Random Forest?

Two reasons.

Every tree is trained on:

1. A random sample of the data

Not the whole dataset.

2. A random subset of features

Instead of considering every feature at each split, each tree considers only a random subset.

That diversity is what makes the forest stronger than any individual tree.

## What is Generalization?

This is one of the most important concepts in machine learning.

**Generalization is a model's ability to perform well on new, unseen data rather than just the data it was trained on.**

That is the real goal of machine learning.

Not memorization.

Not accuracy.

Generalization.

## cross validation

Cross-validation estimates how well a model is likely to perform on unseen data by repeatedly training and evaluating it on different subsets of the dataset.

## Parameters vs Hyperparameters

This distinction is asked in interviews all the time.

Parameters	Hyperparameters
Learned by the model	Chosen before training
Example: tree split values	Example: number of trees
Model discovers them	We specify them

Interview definition:

Parameters are learned from the training data, while hyperparameters are configured before training and control how the learning process occurs.

## If an interviewer asks:

"How would you explain a Random Forest prediction to a business stakeholder?"

SHAP helps us to give a good answer because SHAP tells us which features actually influence predicitions.