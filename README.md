# Students-Habits-and-Performance



---

## Project Notes: Lifestyle vs Academics

### Objective

To investigate how different lifestyle habits impact students' academic performance and identify which factors have the strongest correlations. The goal is to derive actionable insights that support student well-being and academic success.

---

### Dataset Overview

* **Data Type**: Survey or observational dataset on student lifestyle and academic metrics.
* **Key Features**:

  * Sleep duration (hours per night)
  * Screen time (hours per day)
  * Physical activity (frequency or hours per week)
  * Diet quality (qualitative or scored)
  * Study hours
  * Academic performance (e.g., GPA or letter grades)

---

### Data Preprocessing

* **Missing Values**: Removed or filled using statistical imputation (e.g., mean or median).
* **Categorical Variables**: Encoded using label encoding or one-hot encoding depending on the model.
* **Normalization**: Applied to numeric features for consistent scale, especially for modeling.

---

### Exploratory Data Analysis (EDA)

* **Distribution Analysis**: Histograms and box plots used to understand data spread and detect outliers.
* **Correlation Analysis**:

  * Heatmaps and pair plots used to find relationships between variables.
  * Example: Sleep duration positively correlated with GPA.
* **Group Comparisons**: Compared academic performance across categories like diet quality or screen time levels.

---

### Modeling (if applicable)

* **Approach**: Regression (e.g., linear regression) or classification (e.g., logistic regression, decision trees).
* **Target Variable**: Academic performance.
* **Key Predictors**: Sleep, screen time, physical activity, and diet.
* **Evaluation Metrics**: R² score for regression; accuracy and confusion matrix for classification.
* **Model Validation**: Train-test split or k-fold cross-validation used for model robustness.

---

### Key Findings

* Students sleeping 7–8 hours per night performed better academically.
* Excessive screen time (more than 4 hours/day) was associated with lower grades.
* Regular physical activity and a healthy diet contributed positively to academic outcomes.

---

### Limitations

* Reliance on self-reported data may lead to bias or inaccuracies.
* The sample may not be large or diverse enough to generalize findings.
* Only correlation is shown; causation cannot be established.

---

### Future Work

* Include mental health variables (e.g., stress, anxiety).
* Collect longitudinal data for better causal insights.
* Develop an interactive dashboard for visual exploration of trends.
* Explore more complex models such as random forests or neural networks.

---


