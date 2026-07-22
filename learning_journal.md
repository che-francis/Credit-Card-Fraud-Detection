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