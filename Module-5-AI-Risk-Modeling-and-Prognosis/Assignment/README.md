# Module 5 – AI Risk Modeling and Prognosis

## Purpose
This module focused on how machine learning models are used to predict patient risk across healthcare settings. The material covered key applications in cardiovascular disease, cancer recurrence, sepsis detection, and hospital readmissions, along with the performance metrics and validation approaches used to evaluate these models.

## Key Takeaways
I learned that ML risk models can predict patient outcomes with impressive accuracy when developed and validated properly. One study I reviewed used the MIMIC-IV database and a Random Forest model to predict sepsis in ICU patients with intracerebral hemorrhage, achieving an AUROC of 0.912 during training and 0.798 in external validation, with LASSO regression used to select the strongest predictors. Another study built a stacking ensemble that merged the three best-performing models out of nine tested to predict early lung cancer recurrence within two years after surgery, achieving an AUC of 0.81 and a Brier score of 0.03 across multiple centers. These studies showed me that combining multiple algorithms through ensemble methods can push prediction accuracy beyond what any single model can do alone.

## Insights
What stuck with me most from this module was the question I raised in my discussion: when ML risk models are built using patient data from one specific population or region, how can researchers make sure those models perform fairly and accurately for patients from different backgrounds? Feature selection, ensemble methods, and external validation are essential for building models clinicians can trust, but so is SHAP analysis and other explainability tools that show which features are driving each prediction. Without that transparency, even a high-performing model can feel like a black box to the people relying on it.
