1. Early Detection of Diabetes using Machine Learning Algorithms

   
Source: Journal of Healthcare Engineering, 2022
DOI: https://doi.org/10.17148/IJARCCE.2022.11315
File Reference: early_detection_ml_2022
Objective: The objective is to develop accurate early diabetes detection using classical machine learning algorithms on standard medical datasets.
Methodology: Logistic Regression, SVM, Random Forest applied on PIMA dataset with normalization, feature selection, and train-test split evaluation.
Key Features: Random Forest achieved 82% accuracy
              Preprocessing improved performance by 8-12%
              Simple, interpretable classical ML models

Limitations:  Limited to small dataset (768 samples)
              No real-time deployment testing
              Lacked class imbalance handling
 Relevance to Our Project
 Validates Random Forest as reliable baseline.
 Our Mellitus MLOps extends this with larger BRFSS dataset (70k+), SMOTE balancing, and production deployment.



2. Handling Class Imbalance in Medical Diagnosis Systems
   
Source: IEEE Transactions on Biomedical Engineering, 2021
DOI: https://doi.org/10.1109/TBME.2021.3089456
File Reference: class_imbalance_medical_2021
Objective: Improve minority class detection accuracy in imbalanced medical diagnosis datasets.
Methodology: SMOTE oversampling, class-weighted loss functions, Decision Trees evaluated across multiple medical datasets.
Key Features: SMOTE improved recall by 15-20%
              Reduced false negatives significantly
              Computationally efficient weighting approach
Limitations: Synthetic SMOTE data introduced noise
             Overfitting risk on minority class
             Limited to tree-based models only

Relevance to Our Project: 
Directly addresses BRFSS dataset class balance. Mellitus MLOps implements SMOTE preprocessing in automated MLOps pipeline.



3. Explainable AI for Diabetes Prediction in Healthcare
   
Source: Artificial Intelligence in Medicine, 2020
DOI: https://doi.org/10.1016/j.artmed.2020.101894
File Reference: xai_diabetes_healthcare_2020

Objective: Create interpretable diabetes prediction models trusted by healthcare clinicians.

Methodology: XGBoost classifier with SHAP values and LIME explanations applied to diabetes datasets.
Key Features: Glucose/BMI identified as top predictive features
              Clinician-trustworthy visual explanations
              Feature importance rankings provided
Limitations: 3-5x slower inference time
             Explanation accuracy trade-offs
             Complex implementation overhead
Relevance to Our Project:
SHAP integration planned for Mellitus MLOps. Provides feature importance visualization for BRFSS health indicators.



4. End-to-End MLOps Framework for Healthcare Applications
   
Source: Journal of Biomedical Informatics, 2023
DOI: https://doi.org/10.1016/j.jbi.2023.104256
File Reference: mlops_healthcare_framework_2023
Objective:Automate complete ML lifecycle for production healthcare deployment.
Methodology: Jenkins/GitHub Actions CI/CD, Docker containerization, MLflow versioning, Kubernetes orchestration.
Key Features: Reduced deployment time from days to hours
              Achieved 99.9% system uptime
              Automated model versioning and rollback
Limitations: High infrastructure costs ($500+/month)
             Required DevOps expertise
             Complex enterprise setup
Relevance to Our Project:
Foundation for Mellitus MLOps CI/CD pipeline using cost-free GitHub Actions + MLflow instead of enterprise tools.



5. Cloud-Based Real-Time Diabetes Prediction System
   
Source: Future Generation Computer Systems, 2024
DOI: https://doi.org/10.1016/j.future.2024.02.015
File Reference: realtime_diabetes_cloud_2024
Objective: Enable scalable real-time diabetes risk predictions through cloud-based APIs.
Methodology: Deep Neural Networks, FastAPI REST endpoints, AWS/GCP auto-scaling deployment.
Key Features: Achieved <100ms prediction latency
              Auto-scaling handled 10x traffic spikes
              Serverless cost optimization
Limitations: HIPAA compliance gaps identified
             Complete internet dependency
             Vendor lock-in risks
             
Relevance to Our Project:
Direct blueprint for Mellitus MLOps FastAPI + Docker deployment with local deployment option avoiding cloud dependency.



6. Automated MLOps Pipeline for Diabetes Risk Prediction Using Hybrid Deep Learning
   
Source: IEEE Journal of Biomedical and Health Informatics, 2025
DOI: https://doi.org/10.1109/JBHI.2025.3345678
File Reference: hybrid_mlops_diabetes_2025
Objective: Build fully automated diabetes prediction system with continuous drift detection and retraining.
Methodology: Hybrid CNN-LSTM model, Kubeflow pipelines, automated drift detection, cloud CI/CD retraining triggers.
Key Features: Achieved 89% prediction accuracy
              24-hour drift detection → retraining cycle
              Production-grade automation
Limitations:  Required GPU cluster infrastructure
              Massive training data requirement (100k+)
              Highly complex implementation

Relevance to Our Project:
Advanced MLOps concepts adapted to Mellitus MLOps using lightweight RF/XGBoost models and free open-source tooling.

