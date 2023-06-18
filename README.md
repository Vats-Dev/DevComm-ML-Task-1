# DevComm-ML-Task-1
# SVM Models Comparative Study

This repository contains a comparative study of four SVM (Support Vector Machine) models: Linear SVM, Polynomial SVM, RBF (Radial Basis Function) SVM, and Sigmoid SVM. The study utilizes the scikit-learn, NumPy, pandas, and Matplotlib libraries to implement and analyze the models.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Implementation](#implementation)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Support Vector Machines (SVMs) are powerful machine learning models used for classification and regression tasks. They work by finding an optimal hyperplane that separates different classes in the dataset. SVMs can handle both linear and non-linear data by using different kernel functions.

This comparative study aims to compare the performance of four commonly used SVM models: Linear SVM, Polynomial SVM, RBF SVM, and Sigmoid SVM. By using the scikit-learn library, we can easily implement these models and evaluate their effectiveness on a given dataset.

## Installation
To use the code in this repository, you need to have Python 3 installed on your system. You also need to install the following dependencies:

- scikit-learn
- NumPy
- pandas
- Matplotlib

You can install these dependencies using pip:

```
pip install scikit-learn numpy pandas matplotlib
```

## Usage
Follow the steps below to use this repository:

1. Clone the repository to your local machine:

   ```
   git clone https://github.com/your-username/repository-name.git
   ```

2. Navigate to the repository directory:

   ```
   cd repository-name
   ```

3. Run the Python script that contains the SVM models' implementation and comparative study:

   ```
   python svm_comparative_study.py
   ```

4. The script will execute the SVM models on a given dataset and display the comparative results.

## Dataset
The dataset used in this comparative study is located in the `dataset` directory. You can find a file named `data.csv`, which contains the input features and corresponding target labels. Make sure to preprocess or format your own dataset in a compatible format if you wish to use a different dataset.

## Implementation
The implementation of the SVM models and the comparative study can be found in the `svm_comparative_study.py` file. The file contains the necessary code to import the dataset, split it into training and testing sets, implement the four SVM models, train them, and evaluate their performance.

## Results
After running the `svm_comparative_study.py` script, you will see the comparative results of the four SVM models. The results will include metrics such as accuracy, precision, recall, and F1 score for each model. Additionally, the script will generate visualizations using Matplotlib to help understand the performance differences between the models.

## Contributing
Contributions to this comparative study are welcome. If you have any ideas for improvement or want to add more SVM models, feel free to open a pull request with your changes.

## License
The code in this repository is licensed under the [MIT License](LICENSE). Feel free to use and modify the code for your own purposes.
