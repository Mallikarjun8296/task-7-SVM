Task 7 Support Vector Machine (SVM) Classifier

## Objective
Apply the SVM model on various kernels (Linear, RBF) on Breast Cancer dataset and tune the hyperparameters, plot the decision boundaries and cross-validate.


##  Dataset
Dataset: Breast cancer Wisconsin Dataset
It is loaded using `sklearn.datasets.load_breast_cancer()`


##  Tools & Libraries
- NumPy, Pandas, Python
`Scikit-learn` (`SVC`, `StandardScaler`, `cross_val_score`)
Matplotlib to visualise decision boundary


## 2 Workflow Summary

###  Step 1: Load Data Set
Loaded using the in-built library of Scikit-learn
- Used 30 features and binary target (malignant/ benign)

Step 2: Preprocessing
- **StandardScaler** scaled features (SVM is a distance based)

### 3: Linear SVM
Trained on kernel =linear
Accuracy was ~97 per cent

###  Step 4: RBF SVM
learned with `kernel='rbf'`
Achieved accuracy of ~97.3 %

### 5. Step 5: Hyperparameter Tuning
Tested many `C` and `gamma` values
- Best: `C=10`, `gamma=0.01` `accuracy=98.25 percentage`

### WARRANTY Step 6: Visualization
Graphical analysis on decision boundary of mean radius and mean texture
RBF displayed smooth and curvy class separation boundary

### 7. Cross-Validation
- 5fold CV mean accuracy: **97-98%**
-High generalization and low variance

##  Files Included
- `task7_svm_classifier.ipynb`
- `README.md`
- `svm_decision_boundary.png`

---

##  Author
Mallikarjun SY – AI & ML Intern
