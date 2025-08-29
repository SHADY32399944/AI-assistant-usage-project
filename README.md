# Python Data Science & Machine Learning Practice

This repository contains **40 practice questions** covering Python-based Data Science and Machine Learning tasks, using a synthetic dataset on **AI Assistant Usage in Student Life**. The project is organized into six parts: EDA, Visualization, GroupBy & Aggregations, Feature Engineering & Encoding, Machine Learning, and Model Evaluation.

## Dataset
- **Name:** AI Assistant Usage in Student Life (Synthetic)
- **Features:** Includes `SessionLengthMin`, `TotalPrompts`, `StudentLevel`, `Discipline`, `TaskType`, `FinalOutcome`, `AI_AssistanceLevel`, `SessionDate`, and `UsedAgain`.

---

## Part A: Basic EDA
- Load dataset & display first 5 rows
- Check dataset shape, columns, and data types
- Identify missing values
- Compute summary statistics for `SessionLengthMin` & `TotalPrompts`
- Count unique values in `StudentLevel`, `Discipline`, `TaskType`
- Determine the most common `TaskType`
- Calculate average `SessionLengthMin` per `StudentLevel`

## Part B: Visualization
- Histogram of `SessionLengthMin`
- Bar chart of session counts by `StudentLevel`
- Countplot of `TaskType`
- Boxplot of `SessionLengthMin` by `StudentLevel`
- Pie chart for `FinalOutcome` proportions
- Scatterplot: `SessionLengthMin` vs. `TotalPrompts`
- Line chart of average `AI_AssistanceLevel` over time
- Correlation heatmap of numeric features

## Part C: GroupBy & Aggregations
- Average `SessionLengthMin` per `TaskType`
- Discipline with the most sessions
- Compare `AI_AssistanceLevel` across `StudentLevel`
- Most common `FinalOutcome` for Graduate students
- Median `SessionLengthMin` for each `FinalOutcome`

## Part D: Feature Engineering & Encoding
- Convert `SessionDate` into Year, Month, Day
- Label encode `StudentLevel`
- One-Hot encode `TaskType`
- Create `PromptsPerMinute = TotalPrompts / SessionLengthMin`
- Bin `SessionLengthMin` into Short, Medium, Long

## Part E: Machine Learning (Classification)
- Predict `FinalOutcome` using:
  - Decision Tree, Random Forest, Naive Bayes, XGBoost
- Predict `UsedAgain` using:
  - Logistic Regression, KNN, Gradient Boosting
- Train/test split (80/20)
- Model evaluation: accuracy, confusion matrix, classification report

## Part F: Model Evaluation & Hyperparameter Tuning
- Cross-validation for Logistic Regression
- GridSearchCV for Decision Tree hyperparameters
- Random Forest tuning (`n_estimators`, `max_depth`)
- Compare models (Logistic Regression, Decision Tree, Random Forest, Naive Bayes, KNN, Gradient Boosting, XGBoost) for `UsedAgain` prediction

---

## References
- W3Schools Pandas, Matplotlib, Seaborn, Sklearn tutorials  
- GeeksforGeeks Python and Machine Learning guides  
- TutorialsPoint Pandas GroupBy examples  
- Programiz handling missing data tutorials  

---

This project is ideal for **students and practitioners** looking to practice Python, data analysis, visualization, feature engineering, and applying multiple ML classification models in a structured workflow.
