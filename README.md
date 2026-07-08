# Algorithmic Fairness and Accountability Audit of Income Prediction Models

This project evaluates machine learning models not only for predictive accuracy, but also for fairness, transparency, and accountability. It uses the Adult Census Income dataset to study whether income prediction models produce different outcomes across demographic groups such as gender and race.

## Motivation

Algorithmic systems are increasingly used in high-impact areas such as hiring, education, finance, healthcare, and public services. These systems may appear accurate overall while still producing unequal outcomes for different demographic groups.

This project treats a machine learning model as a system that should be audited before deployment.

## Research Question

How do machine learning models trained on socioeconomic data perform across demographic groups, and what fairness risks appear when models are evaluated beyond accuracy?

## Dataset

The project uses the Adult Census Income dataset from the UCI Machine Learning Repository.

The prediction task is to classify whether an individual earns more than $50K per year.

## Methods

The project includes:

- Data preprocessing and exploratory analysis
- Logistic Regression and Random Forest models
- Model evaluation using accuracy, precision, recall, F1-score, and ROC-AUC
- Fairness evaluation across gender and race
- Fairness mitigation using threshold optimization
- Feature importance analysis for model transparency

## Fairness Metrics

The project evaluates:

- Demographic parity difference
- Equalized odds difference
- Selection rate
- False positive rate
- False negative rate

## Results

The models achieved strong predictive performance, but fairness analysis showed differences in selection rates and error rates across demographic groups.

Fairness mitigation reduced demographic parity difference, but also changed other metrics, showing that improving one fairness criterion can affect another.

## Key Finding

Accuracy alone is not enough to evaluate machine learning systems. Responsible AI systems should be assessed using performance, fairness, transparency, and accountability together.

## Tools Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Fairlearn
- Matplotlib
- Jupyter Notebook

## Relevance

This project is related to algorithmic accountability, fairness-aware machine learning, responsible AI, and trustworthy AI.
