**GridSearchCV** is a tool that automatically searches over combinations of hyperparameters to find the best-performing one based on cross-validation.

You give it:

              1. A model
              2. A grid of hyperparameters to try
              3. A scoring metric

It returns: ✅ the best combination

**RandomizedSearchCV**

Instead of trying all hyperparameter combinations like Grid Search, it picks a random subset — much faster, 
especially when the search space is huge.
