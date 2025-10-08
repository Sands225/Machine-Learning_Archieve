# Basic Guide to Modeling
<p style="text-align: justify;">Modeling in machine learning refers to the process of training algorithms to recognize patterns and make predictions or decisions based on data. It involves choosing the right model, training it using suitable data, and evaluating its performance to ensure it generalizes well to unseen data.</p>

## Introduction to Modeling
<p style="text-align: justify;">A <b>machine learning model</b> is a mathematical representation of a real-world process built using data. The goal of modeling is to capture the underlying relationships in data so that the model can make accurate predictions or classifications on new inputs.</p>
<p style="text-align: justify;">There are many types of models — from simple linear regression to complex neural networks. Among these, <b>ensemble learning</b> is one of the most powerful approaches because it combines the strengths of multiple models to achieve higher accuracy and robustness.</p>

## Ensemble Learning
<p style="text-align: justify;">Ensemble learning is a technique that combines multiple base models (often called <b>weak learners</b>) to create a single, more accurate predictive model. The idea is that while individual models may make errors, combining them reduces overall variance, bias, or improves generalization.</p> <p style="text-align: justify;">In essence, ensemble learning “aggregates wisdom” — just as a group’s collective decision is often better than an individual’s guess.</p>

### Bagging (Bootstrap Aggregating)
<p style="text-align: justify;">Bagging is short for <b>Bootstrap Aggregating</b>. It trains multiple versions of the same model on different subsets of the training data (created through bootstrapping — random sampling with replacement). The final prediction is obtained by averaging (for regression) or majority voting (for classification).</p>

<b>How It Works</b>
- Create random samples (with replacement) from the original dataset.
- Train a base model (e.g., Decision Tree) on each sample.
- Combine predictions by averaging or voting.

<b>Advantages</b>
- Reduces variance and overfitting.
- Works well with high-variance models like Decision Trees.

#### Decision Tree
<p style="text-align: justify;">A Decision Tree is a flowchart-like model that splits data into branches based on feature conditions. It’s intuitive but prone to overfitting. Bagging methods like Random Forest help mitigate this limitation.</p>
<b>Key Points</b>
- Simple and interpretable.
- Splits data recursively based on feature thresholds.
- Sensitive to noisy data and small variations.

#### Random Forest

### Boosting

#### Ada Boost

#### Extreme Gradient Boost

#### Light Gradient Boost

#### Cat Boost

### Voting 

#### Hard Voting

#### Soft Voting

### Stacking

