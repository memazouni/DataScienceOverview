theme: Letters from Sweden

# [fit] Introduction to 
# [fit] Machine Learning
<br>
*Amit Kapoor*
@amitkaps
<br>
*Bargava Subramanian*
@bargava

---

> It’s tough to make predictions, especially about the future.
-- Yogi Berra

---

## What is Machine Learning (ML)?

> [Machine learning is the] field of study that gives computers the ability to learn without being explicitly programmed.
-- *Arthur Samuel*

<br>

> Machine learning is the study of computer algorithm that improve automatically through experience
-- *Tom Mitchell*

---

# ML Problems
- “Is this cancer?”
- “What is the market value of this house?”
- “Which of these people are friends?”
- “Will this person like this movie?”
- “Who is this?”
- “What did you say?”
- “How do you fly this thing?”. 

---

# ML in use Everyday
- Search
- Photo Tagging
- Spam Filtering
- Recommendation
- ...

---

# Broad ML Application
- Database Mining e.g. Clickstream data, Business data
- Automating e.g. Handwriting, Natural Language Processing, Computer Vision
- Self Customising Program e.g. Recommendations

---

# ML Thought Process

![inline](img/thought.jpg)

---

# Learning Paradigm
- *Supervised* Learning
- *Unsupervised* Learning
- *Reinforcement* Learning
- *Online* Learning

---

# Supervised Learning
- Regression
- Classification

![inline fit](img/supervised.png)

---

# Unsupervised Learning
- Clustering
- Dimensionality Reduction

![inline fit](img/unsupervised.png)

---

# ML Pipeline

- *Frame*: Problem definition
- *Acquire*: Data ingestion 
- *Refine*: Data wrangline
- *Transform*: Feature creation 
- *Explore*: Feature selection 
- *Model*: Model creation & assessment
- *Insight*: Communication 

---

# Linear Regression

![fit inline](img/linear_regression.png)

---

## Linear Relationship

$$ y_i = \alpha + \beta_1 x_1 + \beta_2 x_2 + .. $$

## Objective Function

$$ \epsilon = \sum_{k=1}^n (y_i - \hat{y_i} ) ^ 2 $$


<br> 
*Interactive Example: [http://setosa.io/ev/](http://setosa.io/ev/ordinary-least-squares-regression/)*

---

# Logit Function

### $$ \sigma (t)={\frac {e^{t}}{e^{t}+1}}={\frac {1}{1+e^{-t}}}$$

![inline](img/logistic-curve.png)

---

# Logistic Regression

![fit inline](img/logistic_regression.png)

---

# Logistic Relationship

Find the $$ \beta $$  parameters that best fit:
$$ y=1 $$  if $$\beta _{0}+\beta _{1}x+\epsilon > 0$$
$$ y=0$$, otherwise

Follows:

$$ P(x)={\frac {1}{1+e^{-(\beta _{0}+\beta _{1}x)}}} $$

---

# Fitting a Model

![fit inline](img/overfitting_2.png)

---

# Bias-Variance Tradeoff

![fit inline](img/biasvariance_2.png)

---
# Train and Test Datasets

Split the Data - 80% / 20%

![fit inline](img/train_test2.png)

---

# Train and Test Datasets

Measure the error on Test data

![fit inline](img/test_train.jpg)

---

# Model Complexity
![fit inline](img/model_complexity.png)

---

# Cross Validation
![fit inline](img/cross_validation.png)

---

# Regularization

Attempts to impose Occam's razor on the solution

![inline](img/regularization.png)

---

# Model Evaluation

Mean Squared Error

$$ MSE = 1/n \sum_{k=1}^n (y_i - \hat{y_i} ) ^ 2 $$

---

# Model Evaluation 

Confusion Matrix

![inline](img/confusion_matrix2.png)

---

# Model Evaluation 

**Classification Metrics**

![fit right](img/precision_recall.png)

Recall (TPR) = TP / (TP + FN)
<br>
Precision = TP / (TP + FP)
<br>
Specificity (TNR) =  TN / (TN + FP)

---
# Model Evaluation

**Receiver Operating Characteristic Curve** 

Plot of TPR vs FPR at different discrimination threshold
 
![100% right](img/roc-curves.png)

---

# Decision Tree

Example: Survivor on Titanic

![inline](img/tree_titanic.png)

---

# Decision Tree

- Easy to interpret
- Little data preparation
- Scales well with data
- White-box model
- Instability – changing variables, altering sequence
- Overfitting

---

# Bagging
- Also called bootstrap aggregation, reduces variance
- Uses decision trees and uses a model averaging approach

---

# Random Forest
- Combines bagging idea and random selection of features.
- Similar to decision trees are constructed – but at each split, a random subset of features is used. 

![inline ](img/random_forest.png)

---

> If you torture the data enough, it will confess.
-- Ronald Case

---

# Challenges
- Data Snooping
- Selection Bias
- Survivor Bias 
- Omitted Variable Bias
- Black-box model Vs White-Box model
- Adherence to regulations

---

# Thank you

Contact us: 

*Amit Kapoor*
@amitkaps
<br>
*Bargava Subramanian*
@bargava

