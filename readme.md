# Fraudulent Transaction Detection using Isolation Forest and LOF

### Business Objective

Fraudulent transactions in the banking or payment industry pose a significant challenge, resulting from illegal credit card usage without the cardholder's knowledge. Detecting fraudulent charges in real-time can help prevent financial losses and protect customer trust. 

---

### Objective

This project employs machine learning techniques to identify fraudulent transactions, specifically using unsupervised learning with Isolation Forest and Local Outlier Factor (LOF) algorithms.

---

### Data Description

The dataset used in this project contains approximately 140,000 masked credit card transactions, each represented by 15 numerical features. These features are the result of PCA transformation, and due to confidentiality reasons, we lack specific information about the attributes.

---

### Tech Stack

- Language: `Python`
- Libraries: `scikit-learn`, `pandas`, `matplotlib`, `numpy`, `seaborn`

---

### Approach

The project follows a structured approach:

1. Import the required libraries and packages.
2. Open the `config.ini` file, a configuration file that can be edited to adapt to different datasets.
3. Read the dataset containing masked credit card transaction data.
4. Perform exploratory data analysis to understand the dataset.
5. Handle missing values and preprocess the data.
6. Determine the contamination amount for Isolation Forest.
7. Train models using Isolation Forest and Local Outlier Factor.
8. Make predictions and identify fraudulent transactions.

---

### Modular Code

- **input**: Contains dataset files and a `config.ini` configuration file.
- **src**: The core of the project, with modularized code organized into the `engine.py` file and the `ml_pipeline` folder. The `ml_pipeline` folder contains functions in separate Python files, used within `engine.py`.
- **output**: Contains pre-trained models saved as `.pkl` files for future use.
- **lib**: A reference folder containing the IPython notebooks.

---



