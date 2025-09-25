# Predicting ADHD Diagnosis and Sex in Children and Adolescents
## Project Overview

This project develops a predictive model that uses fMRI brain imaging and socio-demographic, emotional, and parenting data to predict:
ADHD Diagnosis (Yes/No)
Sex (Male/Female)

ADHD affects approximately 11% of adolescents globally (14% of boys and 8% of girls). However, ADHD in girls is often underdiagnosed, leading to untreated symptoms and long-term mental health challenges.
By building accurate predictive models, this research aims to support general practitioners (GPs) in diagnosing ADHD more effectively, particularly in females, thereby reducing misdiagnosis and aligning with the NHS's goals of improving efficiency and patient care.

## Objectives

Predict ADHD diagnosis using multimodal data.
Classify sex (male/female) from combined metadata and fMRI connectome features.
Enhance ADHD detection in girls, where symptoms are often less apparent.
Reduce clinical workload and improve treatment outcomes.

## Dataset

The project integrates two categories of data:
### Metadata (demographics, emotions, parenting styles, etc.)
Age, sex, emotional state, parenting background
Preprocessed with normalization, encoding, and feature selection


### Brain Imaging Data (fMRI connectome)
Connectivity matrices derived from brain scans
Processed using dimensionality reduction techniques (e.g., PCA)

## Methodology
### Data Preprocessing
Demographic & Emotional Data: Cleaned, normalized, and encoded.
fMRI Connectome Data: Reduced dimensionality for efficiency.
Handled missing values and ensured balanced datasets.

### Modeling Approaches
Machine Learning Models: Logistic Regression, Random Forest, SVM
Deep Learning Models: Fully connected neural networks
Hybrid Models: Combined metadata + fMRI features

## Evaluation Metrics
Accuracy
Precision and Recall
F1-Score
Confusion Matrix

## Results and Findings
Metadata-only models performed well in predicting sex but showed limitations in ADHD diagnosis.
fMRI-only models captured brain connectivity patterns but required more data for high accuracy.

Hybrid models (metadata + fMRI) delivered the best balance, improving diagnostic reliability.
Notable improvement in detecting ADHD in females, reducing underdiagnosis bias.

## Future Work

Incorporate larger, more diverse datasets for better generalization.
Explore advanced deep learning architectures (CNNs, GNNs) for connectome analysis.
Develop an interpretable AI system for clinical use.
Integrate the system into NHS workflows for real-world validation.

## Impact

This research contributes to:
Healthcare efficiency: Assists doctors in faster, more accurate diagnosis.
Equity in care: Addresses underdiagnosis of ADHD in girls.
Mental health outcomes: Enables early treatment and support.
