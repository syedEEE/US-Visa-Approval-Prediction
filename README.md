# US-Visa-Approval-Prediction

# Process:
Data Ingestion --> Data Validation --> Transformation --> Model Training --> Model Eval --> Push to Cloud(S3)
## WorkFlow
1. Constant -> Contains all the Variable/config values
2. Config_entity -> Contains all the folder structure
3. Artifact_entity -> Contains all the output layer from the components
4. Components -> Contains the core part of the code
5. Pipeline -> Connects the component one-after-another
6. app.py/demo.py -> deployment/testing

# To Make data from skewness -> Normal Distribution we use Power Transformation
## We find Data Drift(check distribution between train and test ) using Evidently;  --> DataDriftTab, CatTargetDriftTab for Numerical and Categorical data