## Linear-Regression-Logistic

This task involves implementing various linear models for regression and classification tasks. The implemented models include Linear Regression, Logistic Regression, and Linear Discriminant Analysis (LDA).

### Linear Regression

Implementing the `LinearRegression` class with methods for fitting, predicting, scoring, and saving/loading weights. The fitting method uses gradient descent with early stopping and validation set. Models are trained on the Iris flower dataset to predict continuous outputs based on input features.

### Implementation Details

- Implements the `fit`, `predict`, and `score` methods.
- Utilizes gradient descent with early stopping for optimization.
- Saves and loads model weights to/from files.
- Trains different regression models using batch gradient descent.
- Records loss during training and plotted it against the step number.
- Observes effects of regularization on one trained model.
- Tests the models onto different feature variant sets.

### Classification

Implementing classification models using Logistic Regression and Linear Discriminant Analysis (LDA). Models are trained and tested on variants of input features from the Iris dataset.

### Logistic Regression

Implementing the `LogisticRegression` class with methods for fitting and predicting. It uses either the normal equations or gradient descent for parameter optimization.

### Linear Discriminant Analysis (LDA)

Implementing LDA with methods for fitting and predicting. It utilizes Maximum Likelihood Estimation for parameter estimation.

### Testing

Evaluating the accuracy of trained models on test sets with different feature variants. Comparing the performance of Logistic Regression and LDA.
