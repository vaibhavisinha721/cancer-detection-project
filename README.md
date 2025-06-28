# cancer-detection-project
The Cancer Detection Prediction System is a robust machine learning pipeline that predicts cancer type, stage, and diagnosis from clinical metrics (age, gender, tumor size, blood biomarkers). It leverages essential Python data science tools and best practices:
pandas for data manipulation and preprocessing
scikit‑learn for modeling: data splitting, encoding, feature management, and training three separate Random Forest classifiers (150 trees each) 
joblib for efficient model persistence (using serialization and parallel capabilities) 
The pipeline includes preprocessing (missing value handling, encoding categorical variables), model training and evaluation (accuracy and classification report metrics), and a user-friendly predict_cancer() function that returns human-readable predictions. Trained models are stored as .joblib files, enabling easy deployment and reuse.
Ideal for educational purposes, research, or as a foundation for a clinical decision-support tool. Built using best practices in modular design, reproducibility, and model maintenance.
