# Machine Learning Classification with WEKA

## Overview
This project explores supervised machine learning classification using the WEKA toolkit. The work focuses on dataset preparation, feature selection, experiment configuration, and comparative evaluation of multiple classifiers across training and test datasets.

The project was completed as part of a university machine learning module and emphasises experimental methodology and result interpretation.

## Datasets
The project uses a Facial Action System (FAS) dataset, provided in CSV format and converted into ARFF format for use with WEKA.

- Raw datasets were split into training and test sets
- Feature-selected versions of the datasets were generated
- Multiple ARFF datasets were produced for different experimental tasks

## Experiments
Experiments were configured using WEKA `.exp` files and executed across multiple tasks:

- Task 1: Baseline classification on the full dataset
- Task 2: Classification with alternative configurations
- Task 3: Training and testing using feature-selected datasets

Each experiment was evaluated using WEKA’s standard evaluation framework.

## Algorithms Evaluated
- Random Forest
- Support Vector Machines (SVM)
- Multilayer Perceptron (MLP)
- Other WEKA-supported classifiers

## Project Structure
- `data/` – Raw CSV files and generated ARFF datasets
- `experiments/` – WEKA experiment configuration files
- `results/` – Classification results and outputs
- `README.md` – Project documentation

## Key Learning Outcomes
- Preparing real-world datasets for machine learning experiments
- Designing reproducible classification experiments
- Comparing classifier performance using consistent evaluation methods
- Interpreting experimental results and trade-offs between models

## Notes
This project was completed as part of assessed university coursework. The focus is on experimental design, evaluation, and analysis rather than production deployment.
