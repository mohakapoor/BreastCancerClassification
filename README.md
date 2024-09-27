# Breast Cancer Detection Using Machine Learning

This repository contains code and resources for detecting breast cancer using machine learning algorithms. The project uses the **Breast Cancer Wisconsin (Original) Dataset** with preprocessing steps applied to prepare it for machine learning model training, aiming to predict whether a tumor is benign or malignant.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Models](#models)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Breast cancer is one of the most common forms of cancer in women worldwide. Early detection can significantly improve the chances of successful treatment. This project applies machine learning techniques to classify breast tumors as either benign or malignant based on features related to cell characteristics from breast cancer samples.

The dataset has undergone preprocessing, which includes handling missing values, normalization, and other transformations necessary for effective model training.

## Dataset

The dataset used in this project is the **Breast Cancer Wisconsin (Original) Dataset**, which contains features that describe various characteristics of cell nuclei. After preprocessing, the dataset includes the following features:

- **Features**:
  1. `Clump Thickness`
  2. `Uniformity of Cell Size`
  3. `Uniformity of Cell Shape`
  4. `Marginal Adhesion`
  5. `Single Epithelial Cell Size`
  6. `Bare Nuclei`
  7. `Bland Chromatin`
  8. `Normal Nucleoli`
  9. `Mitoses`
  
- **Target**:
  - `Class`: 
    - `2`: Benign tumor
    - `4`: Malignant tumor
  
This dataset, after preprocessing, is used for building a machine learning model to classify tumors.

## Models

This project compares multiple machine learning algorithms for breast cancer detection:

1. **Logistic Regression**
2. **Support Vector Machine (SVM)**
3. **Random Forest**
4. **K-Nearest Neighbors (KNN)**
5. **Naive Bayes**

Each model is trained on the preprocessed dataset, and their performance is evaluated using various metrics. The models are compared to determine which performs best for breast cancer classification.

### Evaluation Metrics:
- **Confusion Matrix**: A matrix showing true positives, true negatives, false positives, and false negatives, which helps visualize the performance of the model.
- **Accuracy Score**: Measures the proportion of correctly predicted labels out of all predictions.
- **Cross Validation Score**: The model is trained and validated on different folds of the data, and an average accuracy score is computed.

## Contributing

We welcome contributions to this project! If you would like to contribute:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Submit a pull request with a detailed description of your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
