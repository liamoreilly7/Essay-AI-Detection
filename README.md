# Project to detect if an essay is AI generated.
Cornell Tech cs5785 Final Project

### Plan for final project:

1. implement Bert Model
2. analyze using techniques discussed in lecture
3. follow rubric

### Given a toolbox of ML techniques, how do we analyze their performance and decide what models to apply and when?
12/2:
- error analysis
- bias variance analysis

12/4:
### Metrics for binary classification
1. Confusion matrix
2. Sensitivity (true positive rate) and Specificity (true negative rate) include these
    - Balanced accuracy (average of tpr and tnr)
3. Precision, Recall, and F-score

### Advanced Classification Metrics
1. ROC
2. Learning curves
   - show performance as a function of training set size
   - not realistic for NN
3. Loss Curve
  - Loss/epoch -> necessary for NN
