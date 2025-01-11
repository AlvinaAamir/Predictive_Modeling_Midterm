# Predictive Modeling Midterm Exam

## Objective
This project involves predictive modeling tasks, including Generalized Method of Moments (GMM) analysis and logistic regression for a global bank’s credit assessment system.

---

## Datasets
- **midterm_partone.csv**:
  - Used for GMM analysis of stock returns.
- **midterm_parttwo.csv**:
  - Contains credit assessment data with features like credit rating, marital status, requested credit amount, and income levels.

---

## Tools & Techniques
- **Language**: Python (Pandas, Scikit-learn, Statsmodels)
- **Models**:
  - GMM for part 1
  - Logistic Regression for part 2
- **Evaluation Metrics**:
  - Confusion Matrix
  - Precision, Recall, F1-Score
  - Threshold-based prediction adjustment

---

## Key Insights
1. **GMM Analysis (Part 1)**:
   - Updated GMM model to include a bias term and evaluated statistical justification of the industry expert’s claims.
2. **Logistic Regression (Part 2)**:
   - Achieved precision, recall, and F1-scores for credit rating prediction.
   - Adjusted the model’s threshold to grant only 15% credit approvals, analyzing the impact on metrics.

---

## Recommendations
1. **Credit Approval Policy**:
   - Use adjusted logistic regression thresholds to manage credit risk.
2. **Customer Engagement**:
   - Identify demographic segments with high default risk for targeted interventions.

---

## Files
1. **Jupyter Notebook**: [OMIS_midterm.ipynb](./OMIS_midterm.ipynb)
2. **Datasets**:
   - [midterm_partone.csv](./midterm_partone.csv)
   - [midterm_parttwo.csv](./midterm_parttwo.csv)
3. **Summary Report**: [OMIS_midterm_summary.doc](./OMIS_midterm_summary.doc)

---

## How to Use
1. Download the Jupyter Notebook and datasets.
2. Run the notebook to reproduce the GMM analysis and logistic regression models.
3. Refer to the summary report for detailed insights and recommendations.

