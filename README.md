This project develops a predictive model for pharmacogenomics-guided anticoagulant (Warfarin) dosing, integrating both clinical and genetic factors to support safer and more effective personalized therapy. Warfarin dosing varies widely among patients due to differences in age, weight, concurrent medications, and genetic polymorphisms such as CYP2C9 and VKORC1. Inaccurate dosing can lead to severe complications, including bleeding or thrombosis.

Using a combination of exploratory data analysis (EDA), feature engineering, and machine learning, this project builds a dosing model that improves dose accuracy compared to fixed-dose or clinical-only approaches. The goal is to demonstrate how precision medicine and data science can work together to inform individualized dosing decisions in real-world clinical workflows.

🎯 Key Objectives

Analyze the relationship between genetic variants and Warfarin dose requirements

Incorporate both genomic and clinical predictors into a unified dataset

Train and evaluate machine learning models for dose prediction

Compare model performance against standard clinical dosing approaches

Provide a foundation for clinical decision support in precision medicine

🧬 Data Inputs

Patient demographics (age, weight, ethnicity, etc.)

Clinical factors (concurrent medications, INR history)

Genotype information (CYP2C9, VKORC1, ± others)

🤖 Methods & Tools

Python (Pandas, NumPy, Scikit-Learn, XGBoost/LightGBM)

Machine Learning Regression Models

Model performance evaluation (RMSE, MAE, R²)

Feature importance + interpretability insights (SHAP or LIME optional)

📦 Outputs

Predictive Warfarin dosing model

Visualizations demonstrating genotype-dose relationships

Reproducible Jupyter Notebook pipeline

Ready-for-deployment model structure (optional: mlflow or API step)

🩺 Impact

This work highlights the clinical value of pharmacogenomics, demonstrating how integrating genetic data into therapeutic dosing can:

Reduce adverse drug reactions

Improve time-in-therapeutic range (TTR)

Support safer, more individualized patient care
