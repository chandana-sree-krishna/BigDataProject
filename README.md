# Exploratory Data Analysis and Predicting Protein Classification 

## Introduction

This project aims to predict the family type of proteins based on their sequences using machine learning techniques. Proteins are essential macromolecules with diverse functions in biological systems. Understanding their family types can provide insights into their structure, function, and interactions within cells.

## Dataset

The dataset used in this project contains a diverse range of biologically significant macromolecules, primarily proteins. It includes information such as the protein sequence, classification, and other relevant attributes.

## Methodology

1. **Data Preprocessing**: The dataset is cleaned by filtering out non-protein molecules, handling missing values, and removing duplicates.

2. **Exploratory Data Analysis (EDA)**: The dataset is analyzed to understand the distribution of protein classifications and visualize the data.

3. **Feature Extraction**: Protein sequences are tokenized and converted into numerical features using techniques like regex tokenization and count vectorization.

4. **Model Training**: A Naive Bayes classifier is trained on the processed dataset to predict the protein family type based on the extracted features.

5. **Model Evaluation**: The trained model's performance is evaluated using metrics such as accuracy to assess its predictive capability.

## Setup and Usage

1. **Environment Setup**: Ensure Python and required libraries are installed. This project utilizes PySpark for distributed computing.

2. **Data Download**: Obtain the dataset containing protein sequences and classifications.

3. **Code Execution**: Run the Python script containing the code provided in this repository.

4. **Model Evaluation**: Evaluate the trained model's performance using metrics such as accuracy.

## Dependencies

- PySpark
- Matplotlib
- Seaborn

## License

This project is licensed under the [MIT License](LICENSE).
