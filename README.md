# Python_ML
Notes from the book "Python Machine Learning" by Raschka

## Bagging vs Boosting vs Stacking

[link](https://stats.stackexchange.com/questions/18891/bagging-boosting-and-stacking-in-machine-learning)

Bagging:

- **parallel** ensemble: each model is built independently
- aim to **decrease variance**, not bias
- suitable for high variance low bias models (complex models)
- an example of a tree based method is **random forest**, which develop fully grown trees (note that RF modifies the grown procedure to reduce the correlation between trees)

Boosting:

- **sequential** ensemble: try to add new models that do well where previous models lack
- aim to **decrease bias**, not variance
- suitable for low variance high bias models
- an example of a tree based method is **gradient boosting**