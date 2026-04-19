# PhishDuel: Anonymous Code and Data Repository

This repository contains the supplemental code, datasets, and high-resolution figures for the paper **"PhishDuel: Adaptive Resilience Against LLM-Generated Phishing via Structural Feature Evaluation."**

## Repository Contents

### 1. Codebase
* `Python_Scripts_Phishduel.py`: The core implementation containing the 7-D mathematical feature extraction pipeline, XGBoost model training, and the adaptive evasion simulation scripts (Semantic Dilution and Stealth attacks).

### 2. Datasets and Empirical Results
* `phishduel_test_data.csv`: The base evaluation corpus.
* `phishduel_features.csv`: The extracted 7-D mathematical features for the dataset.
* `phishduel_mixed_traffic_results.csv`: Results from the enterprise noise and active learning baseline evaluations.
* `phishduel_simulation_results.csv`: The raw inference logs from the LLM zero-day generative siege.
* `phishduel_FINAL_RESULTS.csv`: The aggregated performance metrics and confusion matrices.
* `phishduel_checkpoint.csv`: Model checkpoint data for the asynchronous recovery tests.

### 3. Serialized Model Weights
* `phishduel_v2_97pct.json`: The exported XGBoost model weights and decision tree architecture utilized to achieve the benchmarked 99.75% balanced accuracy.

### 4. High-Resolution Figures
The repository includes the original high-resolution vector plots utilized in the manuscript:
* `ACM_Accuracy_Maintenance.pdf`
* `ACM_Evasion_Gap.pdf`
* `ACM_F1_Score.pdf`
* `ACM_SHAP_Autopsy.pdf`
* `ACM_Vulnerability_Gap.pdf`
* `System_Recovery.pdf`
* `Threat_Containment.pdf`

## Requirements
To execute the scripts in this repository, the following dependencies are required:
- Python 3.8+
- `pandas`, `numpy`
- `xgboost`
- `python-Levenshtein`
- `scikit-learn`

---
*Note: This repository has been rigorously anonymized to comply with double-blind peer review guidelines for ESORICS 2026. All author affiliations and identifying metadata have been removed from the codebase and datasets.*
