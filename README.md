**Titanic Survival Prediction**

A Python project (`titanic_decision_tree.ipynb`) that builds and optimizes a Decision Tree classifier to predict Titanic passenger survival based on demographic and ticket data.

**Project Workflow**

* **Preprocessing:** Cleans missing data and encodes categorical variables (gender, embarkation port).
* **Modeling:** Trains a baseline Scikit-Learn `DecisionTreeClassifier`.
* **Tuning:** Optimizes hyperparameters (`max_depth`, `criterion`) using `GridSearchCV`.
* **Evaluation:** Assesses model performance using accuracy scores, classification reports, and a visual tree plot.

**Tech Stack:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn.
