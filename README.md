# Banking Churn Binary Classification

This project focuses on predicting customer churn in the banking sector using binary classification techniques. By analyzing customer data, the model aims to identify clients who are likely to leave the bank, enabling proactive retention strategies.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model Development](#model-development)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

Customer churn is a significant concern in the banking industry, as retaining existing customers is often more cost-effective than acquiring new ones. This project utilizes machine learning to predict the likelihood of a customer leaving the bank, allowing for targeted interventions.

## Dataset

The dataset used in this project is `bank.csv`, which contains various features related to customer demographics, account information, and transaction history. Key features include:

- **Customer ID**: Unique identifier for each customer
- **Age**: Customer's age
- **Gender**: Customer's gender
- **Balance**: Account balance
- **Products**: Number of products held by the customer
- **CreditScore**: Customer's credit score
- **IsActiveMember**: Whether the customer is an active member
- **EstimatedSalary**: Customer's estimated salary
- **Exited**: Target variable indicating if the customer has churned (1) or not (0)

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/AntBap23/Banking-Churn-Binary-Classification.git
   cd Banking-Churn-Binary-Classification
   ```

2. **Set up a virtual environment** (optional but recommended):

   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows, use venv\Scripts\activate
   ```

3. **Install the required dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

   *Note: Ensure that `requirements.txt` is available in the repository with all necessary dependencies listed.*

## Usage

The primary analysis and model development are conducted in the Jupyter Notebook `binary_classification_model.ipynb`. To run the notebook:

1. **Launch Jupyter Notebook**:

   ```bash
   jupyter notebook
   ```

2. **Open** `binary_classification_model.ipynb` and execute the cells sequentially to preprocess the data, train the model, and evaluate its performance.

## Model Development

The project involves the following steps:

1. **Data Preprocessing**:
   - Handling missing values
   - Encoding categorical variables
   - Feature scaling

2. **Model Selection**:
   - Evaluating multiple classification algorithms
   - Selecting the best-performing model based on evaluation metrics

3. **Model Training**:
   - Training the selected model on the processed dataset

4. **Evaluation**:
   - Assessing model performance using metrics such as accuracy, precision, recall, and F1-score
   - Analyzing confusion matrix and ROC-AUC curve

## Results

The final model achieved the following performance metrics:

- **Accuracy**: *e.g., 85%*
- **Precision**: *e.g., 80%*
- **Recall**: *e.g., 75%*
- **F1-Score**: *e.g., 77%*


## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


