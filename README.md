This project develops predictive models using text mining and machine learning to analyze hotel reviews.

**Approach:** Built multiple models in Weka using review text and metadata to predict ratings, review impact, and reviewer influence.

**Analysis:**
- Predicted overall ratings (1–5) from review text using word frequency
- Modeled review helpfulness (≥15 heplful votes) using binary classification, applying SMOTE to address class imbalance  
- Predicted reviewer influence (≥15 cities visited) based on behavioral features (e.g., number of reviews, helpful votes)

**Methods:**
- Random Forest, J48, and Neural Networks  
- 10-fold cross-validation for model robustness  
- Feature selection using information gain  
- Cost-sensitive analysis for business impact   

**Outcome:** Developed robust predictive models and identified key textual and behavioral factors influencing ratings, review impact, and reviewer credibility.
