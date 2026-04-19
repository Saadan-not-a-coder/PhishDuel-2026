# PhishDuel: Anonymous Code and Data Repository

This repository contains the supplemental code and datasets for the paper "PhishDuel: Adaptive Resilience Against LLM-Generated Phishing via Structural Feature Evaluation."

## Contents
1. `phishduel_real_dataset.csv`: The evaluation corpus containing mixed benign and adversarial URIs.
2. `feature_extractor.py`: The 7-D mathematical feature extraction pipeline.
3. `adaptive_evaluation.py`: The script used to generate the Semantic Dilution and Stealth payloads.
4. `results/`: PDF plots of the F1-Score maintenance and Vulnerability Gap.

## Requirements
- Python 3.8+
- pandas
- xgboost
- python-Levenshtein

Note: This repository has been anonymized for double-blind peer review.