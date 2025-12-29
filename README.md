# DBA5106 Project 2: Classification model implemented on Kaggle dataset
Kaggle dataset: [Stack Overflow Developer Employability Analysis](https://www.kaggle.com/datasets/ayushtankha/70k-job-applicants-data-human-resource/code)

## Highlights:
- Built an end-to-end ML pipeline to predict developer employability under asymmetric misclassification costs using survey-based profile data.
- Systematically compared glassbox vs. blackbox models across multiple skill-representation strategies and loss functions.
- Identified log-loss logistic regression with a bag-of-skills vectorizer as the most robust model (AUC ≈ 0.995) with cost-sensitive threshold optimization.
- Demonstrated via SHAP that fine-grained technical skills drive predictions, yielding a high-performing, interpretable, and deployment-ready hiring model.
