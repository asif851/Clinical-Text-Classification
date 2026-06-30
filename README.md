# Clinical Text Classification

## Overview
The goal of this project is to classify medical transcriptions into their corresponding medical specialties using natural language processing.

## Dataset
- Source: MTSamples
- Total samples: 4999
- Classes used: 15 (filtered from 40)
- Input: transcription column
- Output: medical_specialty label

## Preprocessing
- Lowercase conversion
- Punctuation and special character removal
- Stopword removal
- Lemmatization

## Models Evaluated
- Logistic Regression
- Linear SVC
- Naive Bayes
- Passive Aggressive Classifier
- Random Forest
- XGBoost

## Results
| Model | Train | Test | Gap | 95% CI |
|-------|-------|------|-----|--------|
| Logistic Regression | 0.4984 | 0.4443 | 0.0540 | (0.4106, 0.4780) |
| LinearSVC | 0.4981 | 0.4407 | 0.0573 | (0.4070, 0.4744) |
| Naive Bayes | 0.4663 | 0.4287 | 0.0376 | (0.3952, 0.4623) |

## Future Work
- Combine transcription and description as input
- Explore BioBERT or ClinicalBERT for better medical text understanding

## Author
Maria Rahman
