# neural-network-challenge-2
## Overview
This project builds a branched neural network to predict:
Employee Attrition: Whether an employee will leave the company.
Best Department Fit: The most suitable department for an employee.
Built with TensorFlow/Keras, using pandas and scikit-learn for preprocessing.

## Getting Started
### Prerequisites
Python 3.7+
Jupyter Notebook / Google Colab

### Install dependencies:
pip install pandas numpy tensorflow scikit-learn matplotlib

## Running the Project
Clone the repository:
git clone https://github.com/your-username/neural-network-challenge-2.git
cd neural-network-challenge-2
Open attrition.ipynb in Google Colab or Jupyter Notebook.
Follow the notebook steps to preprocess data, train the model, and evaluate results.

## Model Architecture
Input Layer: Accepts preprocessed employee data.
Shared Layers: Extract general features.

### Branched Layers:
Sigmoid activation for Attrition Prediction.
Softmax activation for Department Prediction.

## Data Processing

Encoding: OneHotEncoder for categorical data.
Scaling: StandardScaler for numerical features.
Train-Test Split: 80% training, 20% testing.


## Attribution
- Techniques referenced from **TensorFlow/Keras** and **scikit-learn** documentation.
- Snippets adapted from **curriculum content, Stack Overflow, and ML resources**.
.

## License
Licensed under MIT. Contributions welcome!
