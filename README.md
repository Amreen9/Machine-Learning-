Machine Learning 

A collection of fundamental machine learning concepts with code examples.

Topics Covered

· Supervised Learning
  · Linear Regression
  · Logistic Regression
  · Decision Trees
  · Random Forest
  · SVM
· Unsupervised Learning
  · K-Means Clustering
  · PCA
· Evaluation Metrics
  · Accuracy, Precision, Recall
  · Confusion Matrix
  · ROC-AUC
· Core Concepts
  · Train/Test Split
  · Cross-Validation
  · Overfitting & Underfitting
  · Bias-Variance Tradeoff

Setup

```bash
pip install -r requirements.txt
```

Run Examples

```bash
# Linear Regression
python examples/linear_regression.py

# Classification
python examples/logistic_regression.py

# Clustering
python examples/kmeans.py
```

Notebooks

Explore interactive examples:

```bash
jupyter notebook notebooks/
```

Key Takeaways

· Supervised: Labeled data → Predict outcomes
· Unsupervised: Unlabeled data → Find patterns
· Classification: Predict categories
· Regression: Predict numbers
· Overfitting: Model too complex, poor generalization
· Underfitting: Model too simple, poor performance

Dependencies

· Python 3.8+
· numpy
· pandas
· scikit-learn
· matplotlib
· seaborn

Resources

· scikit-learn Documentation
· Andrew Ng ML Course
