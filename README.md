# ML-TestingTools
The following reposity contians a collection of tools to test and validate machine learning models and datasets


## Model Analysis

### Yellowbrick [Link](https://www.scikit-yb.org/en/latest/)
Yellowbrick is a Python library that provides visualizations for model selection, evaluation, and validation. It includes tools for generating confusion matrices, learning curves, ROC curves, and other diagnostic plots. It can be used with various machine learning frameworks, such as scikit-learn and TensorFlow.

Visualizers:
- Feature Visualization
  - Rank Features
  - PCA Projections
  - ...
- Regression Visualization
  - Prediction Error Plot
  - Residuals Plot
  - ...
- Model Selection Visualization
  - Learning Curve
  - Feature Importance
  - ...

### Alibi [Link](https://github.com/SeldonIO/alibi)
Alibi is a Python library for machine learning model inspection and validation. It provides functions for testing model fairness, robustness, and explainability. It also includes tools for generating adversarial examples and evaluating model sensitivity.

### SHAP [Link](https://shap.readthedocs.io/en/latest/index.html)
SHAP is a Python library that provides model interpretability and validation tools. It includes functions for computing feature importance, visualizing decision boundaries, and generating explanations for individual model predictions.

### ($) ModelOp Center 
ModelOp Center is a platform for managing and validating machine learning models in production. It includes functions for monitoring model performance, identifying model drift, and validating models against data distribution shifts.

### IBM AI Fairness 360
AI Fairness 360 is an open-source toolkit for detecting and mitigating bias in machine learning models. It includes functions for measuring bias, generating fairness metrics, and applying fairness interventions.

### IBM Watson OpenScale
Watson OpenScale is a platform for managing and monitoring machine learning models in production. It includes functions for detecting model drift, validating models against data distribution shifts, and monitoring model explainability.

### IBM Adversarial Robustness Toolbox (ART): 
ART is an open-source toolkit for testing the robustness of machine learning models against adversarial attacks. It includes functions for generating adversarial examples, measuring model robustness, and applying adversarial defenses.

### Certifai: 
Certifai is a platform for testing and certifying the safety of machine learning models in production. It includes functions for detecting bias, assessing fairness, and quantifying model safety against specific safety criteria.

### Microsoft Counterfactual Fairness: 
Counterfactual Fairness is an open-source toolkit for testing and certifying the fairness of machine learning models. It includes functions for generating counterfactual examples, assessing model fairness, and applying fairness interventions.

<br>

## Data Handling
[Great Expectations](https://greatexpectations.io/) - Great Expectations is an open-source framework for data validation that can be integrated with various machine learning frameworks. It provides tools for defining data expectations, validating data against those expectations, and generating data documentation.

Databricks MLflow - MLflow is an open-source platform for managing the machine learning lifecycle. It includes tools for tracking experiments, packaging code and models, and deploying models. The MLflow data validation component provides functions for schema validation and data quality checks.

Deequ - Deequ is an open-source library for data quality assessment and monitoring. It provides functions for profiling data, defining constraints, and validating data against those constraints. It can be integrated with Apache Spark for distributed data processing.

Datahub - Datahub is an open-source platform for managing metadata and data assets. It provides tools for cataloging and documenting data, as well as functions for data validation and profiling. It can be integrated with various data processing frameworks, such as Apache Spark and Presto.

Apache Griffin - Apache Griffin is an open-source tool for data quality assessment and monitoring. It provides functions for profiling data, defining rules, and validating data against those rules. It can be integrated with Apache Spark for distributed data processing.
