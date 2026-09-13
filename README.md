** Prediction using Decision Tree and Grid Search CV**

** Workflow**

* **Preprocessing:** Cleans missing data and encodes categorical variables (gender, embarkation port).
* **Modeling:** Trains a baseline Scikit-Learn `DecisionTreeClassifier`.
* **Tuning:** Optimizes hyperparameters (`max_depth`, `criterion`) using `GridSearchCV`.
* **Evaluation:** Assesses model performance using accuracy scores, classification reports, and a visual tree plot.

**Tech Stack:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn.
