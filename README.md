# ModelForge

Welcome to the ModelForge repository! This project contains a collection of machine learning models developed from scratch for various tasks. Each model is implemented to showcase different machine learning techniques and methodologies.

## Overview

- **ModelForge**: A collection of machine learning models created for educational and practical purposes.
- **Languages**: Python
- **Libraries**: Numpy , pandas , scikit-learn

## Models

### K-Nearest Neighbors (KNN)

- **Description**: A classification algorithm that assigns a class based on the majority vote of its k-nearest neighbors.
- **Key Features**: Simple and effective for small to medium-sized datasets.
- **Usage**: 
    ```python
    from knn import KNN
    model = KNN(k=3)
    model.train(training_data, training_labels)
    predictions = model.predict(test_data)
    ```

### Lasso Regression

- **Description**: A regression analysis method that performs L1 regularization to enhance prediction accuracy and interpretability.
- **Key Features**: Useful for feature selection and regularization.
- **Usage**: 
    ```python
    from lasso import Lasso
    model = Lasso(alpha=0.1)
    model.train(training_data, training_labels)
    predictions = model.predict(test_data)
    ```

### Linear Regression

- **Description**: A linear approach to modeling the relationship between a dependent variable and one or more independent variables.
- **Key Features**: Simple and widely used for regression tasks.
- **Usage**: 
    ```python
    from linear_regression import LinearRegression
    model = LinearRegression()
    model.train(training_data, training_labels)
    predictions = model.predict(test_data)
    ```

### Logistic Regression

- **Description**: A statistical model that uses a logistic function to model a binary dependent variable.
- **Key Features**: Ideal for binary classification problems.
=- **Usage**: 
    ```python
    from logistic_regression import LogisticRegression
    model = LogisticRegression()
    model.train(training_data, training_labels)
    predictions = model.predict(test_data)
    ```

### Support Vector Machine (SVM) Classifier

- **Description**: A supervised learning model that finds the hyperplane that best separates the classes in the feature space.
- **Key Features**: Effective in high-dimensional spaces and when the number of dimensions exceeds the number of samples.
- **Usage**: 
    ```python
    from svm_classifier import SVMClassifier
    model = SVMClassifier(kernel='linear')
    model.train(training_data, training_labels)
    predictions = model.predict(test_data)
    ```

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/tatuskarjaiwanth/ModelForge.git
    ```
2. Navigate to the repository directory:
    ```bash
    cd ModelForge
    ```


## Usage

Import and use each model as demonstrated in the examples above.

## Contributing

If you have suggestions for improvements or would like to contribute, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For any questions or feedback, please contact me at [jaiwanthtatuskar@gmail.com].

