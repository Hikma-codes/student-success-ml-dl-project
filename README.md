# Predicting Student Dropout and Academic Success with Machine Learning and Deep Learning

## Project Description

Ensuring student success is the main problem that is currently facing educational institutions all over the world. Despite the fact that universities and colleges make a great effort to support their students, there are still students who experience difficulties in studying and even fail to pass exams or drop out of studies. Early detection of potentially problematic students may enable educational institutions to provide assistance to those students in time and increase their chances for successful graduation.

The current research explores whether it is possible to predict student academic outcomes with the use of machine learning and deep learning techniques. The project includes comparing several classical machine learning algorithms with neural networks in terms of their ability to predict the fact of a student graduating, being enrolled in university or dropping out.

The project was done within the framework of Introduction to Machine Learning course and shows the full process of building a model from the very beginning of its creation till error analysis.

## Research Question

Can the academic outcomes of the students be predicted with machine learning and deep learning models using demographic, socioeconomic and other information about students?

## Objectives

The objectives of the project include:

* To explore factors that influence students' success and their dropout.
* To compare classical machine learning models and deep learning models.
* To evaluate model performance through the use of several metrics.
* To investigate the influence of feature engineering and hyperparameter tuning.
* To identify most influential factors on students' academic success and dropout.
  
## Data Set

### Predict Students' Dropout and Academic Success

The data set was taken from UCI Machine Learning Repository and consists of information about students of higher educational institutions.

### Data Set Characteristic

* Total number of records: 4,424 students
* Number of input features: 36 variables
* Classes of target variable:

  * Graduate
  * Enrolled
  * Dropout

### Features

The data set includes information about the following aspects of students' lives:

* Demographic characteristics
* Socioeconomic situation
* Information about enrolment
* Academic results
* Prior educational experience
* Financial state

Target variable reflects students' academic outcome.

## Workflow for the Project

The whole process of working on the project is based on the complete machine learning pipeline:

### 1. Data Loading and Exploration

* Dataset loading
* Initial exploration
* Quality checking
* Statistical characteristics calculation

### 2. Exploratory Data Analysis

* Class balance analysis
* Distributions of features
* Correlations analysis
* Detection of outliers
* Missing values analysis

### 3. Data Preprocessing

* Labeling
* Scaling of features
* Cleaning of data
* Splitting into train and test sets

### 4. Feature Engineering

A number of new engineered features was produced.

### 5. Machine Learning Models

The following traditional machine learning models were applied:

#### Logistic Regression

Used as a baseline linear classifier.

#### Random Forest

A machine learning algorithm which can detect nonlinear relationships.

#### Support Vector Machine (SVM)

Utilized in various forms of kernel and regularization parameters.

### 6. Deep Learning Models

#### Sequential Neural Network

A fully connected neural network implemented through TensorFlow and Keras Sequential API.

#### Functional API Neural Network

A neural network architecture created through TensorFlow Functional API.

Some other approaches considered are:

* Dropout
* Batch Normalization
* Learning Rate Optimization
* Model Architecture Selection

## Experiment Setup

Over ten experiments were performed for the purpose of evaluating model performance on various configurations.

Some experiments include:

| Experiment | Model                        | Purpose                        |
| ---------- | ---------------------------- | ------------------------------ |
| 1          | Logistic Regression Baseline | Baseline performance           |
| 2          | Logistic Regression Tuned    | Hyperparameter optimization    |
| 3          | Random Forest 100 Trees      | Ensemble benchmark             |
| 4          | Random Forest 300 Trees      | Complexity analysis            |
| 5          | Tuned Random Forest          | Performance optimization       |
| 6          | SVM Baseline                 | Nonlinear classification       |
| 7          | Tuned SVM                    | Hyperparameter analysis        |
| 8          | Sequential Neural Network    | Deep learning baseline         |
| 9          | Sequential + Dropout         | Regularization analysis        |
| 10         | Sequential + BatchNorm       | Stability improvement          |
| 11         | Functional API Model         | Architecture comparison        |
| 12         | Tuned Functional API Model   | Final deep learning experiment |


## Evaluation Measures

The evaluation of the model was done via:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC
* Confusion Matrix Analysis

All of which give a thorough evaluation of the predictive performance of the model in all classes.

## Visualizations

This project comes with an elaborate visualization section, which involves:

* Class Distribution Visualizations
* Correlation Heat Maps
* Feature Importance Visualization
* Confusion Matrices
* ROC Curves
* Precision-Recall Curves
* Learning Curves
* Validation Curves
* Error Analysis Visualizations

## Project Structure
```text
student-success-ml-dl-project/
│
├── data/
│   └── student_dropout.csv
│
├── notebooks/
│   └── student_success_final.ipynb
│
├── figures/
│   ├── class_distribution.png
│   ├── correlation_heatmap.png
│   ├── feature_importance.png
│   ├── roc_curve.png
│   ├── confusion_matrix.png
│   └── learning_curve.png
│
├── models/
│   └── saved_model.keras
│
├── report/
│   └── final_report.pdf
│
├── README.md
├── requirements.txt
└── .gitignore
```

## Technologies Used

### Programming Language

* Python

### Data Analysis

* Pandas
* NumPy

### Visualization

* Matplotlib
* Seaborn

### Machine Learning

* Scikit-Learn

### Deep Learning

* TensorFlow
* Keras

### Development Environment

* Visual Studio Code
* Jupyter Notebook
* Git
* GitHub

## Key Findings

The research focuses on comparing traditional machine learning approaches to the deep learning techniques and evaluating their efficiency for forecasting student performance.

The study illustrates the impact of various aspects of the modeling process on the prediction quality. It allows us to understand the trade-offs between different factors such as model simplicity/complexity, interpretability, and computational requirements.

## Limitations

There are several limitations that need to be considered:

* The dataset is collected in a particular educational setting.
* Class imbalance i# Predicting Student Dropout and Academic Performance With Machine Learning and Deep Learning

## Project Description

The problem of student success is the biggest challenge for all educational establishments nowadays. There are significant efforts made by universities and colleges in order to assist students; nevertheless, there are still many students who have difficulties and end up failing or even leaving college. Early identification of at-risk students is crucial for helping institutions intervene.

This research evaluates the ability of machine learning and deep learning algorithms to predict the academic results of students. This study compares several traditional machine learning algorithms against neural networks in order to identify which models perform better when it comes to predicting the academic fate of the student (whether he or she will graduate, continue the studies or drop out).

The project is done within the framework of the Introduction to Machine Learning course and illustrates the entire process of machine learning, including data exploration, feature engineering, preprocessing, modeling, optimization, evaluation, and error analysis.

---

## Research Question

Is it possible to use machine learning and deep learning methods for the prediction of the academic performance of students based on demographic, socioeconomic, and academic data?

---

## Objectives

The goals of the project include:

* Analysis of the factors affecting the success and dropout of students.
* Comparison of classic machine learning algorithms against deep learning algorithms.
* Model evaluation with the help of various metrics.
* Investigation of the effect of feature engineering and hyperparameter tuning.
* Identification of key factors influencing the academic performance.
* Obtaining useful insights into different approaches to modeling.

## Dataset

### Predict Students' Dropout and Academic Success Dataset

The dataset was downloaded from the UCI Machine Learning Repository and provides information about students of higher education institutions.

### Dataset Characteristics

* Total Number of Records: 4,424 students
* Features: 36 input features
* Target Categories:

  * Graduate
    * Enrolled
      * Dropout

      ### Variables Included

      The dataset contains information related to:

      * Demographic characteristics
      * Socioeconomic background
      * Enrollment information
      * Academic performance
      * Previous educational history
      * Financial status

      The target variable represents the final academic outcome of each student.

     ## Project Workflow

The project involves a complete machine learning pipeline process.

### 1. Data Loading and Exploration

* Data loading
* Basic exploration
* Data validation
* Statistical summaries

### 2. Exploratory Data Analysis

* Class distribution analysis
* Feature distribution analysis
* Correlation analysis
* Outliers detection
* Missing values analysis

### 3. Data Preprocessing

* Label encoding
* Feature scaling
* Data cleaning
* Train-test split

### 4. Feature Engineering

Several feature engineering processes were carried out in order to improve performance of the model.

### 5. Machine Learning Models

The following classical machine learning models were developed in the project:

#### Logistic Regression

Baseline linear classifier.

#### Random Forest

Ensemble learning algorithm capable of modelling nonlinear relationship.

#### Support Vector Machine (SVM)

Implemented with various configurations of kernel and regularization parameters.

### 6. Deep Learning Models

#### Sequential Neural Network

Fully connected neural network implemented using TensorFlow and Keras Sequential API.

#### Functional API Neural Network

Neural network implemented using TensorFlow Functional API.

Other algorithms considered in the project:

* Dropout Regularization
* Batch Normalization
* Learning rate optimization
* Architecture tuning

## Experimental Design

More than ten experiments were run to compare performance of models with different configurations.

For example:

      | Experiment | Model                        | Purpose                        |
      | ---------- | ---------------------------- | ------------------------------ |
      | 1          | Logistic Regression Baseline | Baseline performance           |
      | 2          | Logistic Regression Tuned    | Hyperparameter optimization    |
      | 3          | Random Forest 100 Trees      | Ensemble benchmark             |
      | 4          | Random Forest 300 Trees      | Complexity analysis            |
      | 5          | Tuned Random Forest          | Performance optimization       |
      | 6          | SVM Baseline                 | Nonlinear classification       |
      | 7          | Tuned SVM                    | Hyperparameter analysis        |
      | 8          | Sequential Neural Network    | Deep learning baseline         |
      | 9          | Sequential + Dropout         | Regularization analysis        |
      | 10         | Sequential + BatchNorm       | Stability improvement          |
      | 11         | Functional API Model         | Architecture comparison        |
      | 12         | Tuned Functional API Model   | Final deep learning experiment |

      ---

      ## Evaluation Metrics

      Model performance was evaluated using:

      * Accuracy
      * Precision
      * Recall
      * F1-Score
      * ROC-AUC
      * Confusion Matrix Analysis

      These metrics provide a comprehensive assessment of predictive performance across all classes.

      ---

      ## Visualizations

      The project includes extensive visual analysis, including:

      * Class Distribution Charts
      * Correlation Heatmaps
      * Feature Importance Plots
      * Confusion Matrices
      * ROC Curves
      * Precision-Recall Curves
      * Learning Curves
      * Validation Curves
      * Error Analysis Visualizations

      ---

      ## Repository Structure

      ```text
      student-success-ml-dl-project/
      │
      ├── data/
      │   └── student_dropout.csv
      │
      ├── notebooks/
      │   └── student_success_final.ipynb
      │
      ├── figures/
      │   ├── class_distribution.png
      │   ├── correlation_heatmap.png
      │   ├── feature_importance.png
      │   ├── roc_curve.png
      │   ├── confusion_matrix.png
      │   └── learning_curve.png
      │
      ├── models/
      │   └── saved_model.keras
      │
      ├── report/
      │   └── final_report.pdf
      │
      ├── README.md
      ├── requirements.txt
      └── .gitignore
      ```

      ---

      ## Technologies Used

      ### Programming Language

      * Python

      ### Data Analysis

      * Pandas
      * NumPy

      ### Visualization

      * Matplotlib
      * Seaborn

      ### Machine Learning

      * Scikit-Learn

      ### Deep Learning

      * TensorFlow
      * Keras

      ### Development Environment

      * Visual Studio Code
      * Jupyter Notebook
      * Git
      * GitHub

      ---

      ## Key Findings

      The project compares the effectiveness of traditional machine learning algorithms and deep learning architectures for predicting student academic outcomes.

      The results demonstrate how model complexity, feature engineering, and optimization strategies influence predictive performance. The study also highlights the trade-offs between interpretability, computational efficiency, and predictive accuracy.

      ---

      ## Limitations

      Several limitations should be considered:

      * Dataset collected from a specific educational context.
      * Potential class imbalance.
      * Some features may not generalize across institutions.
      * Deep learning performance may be constrained by available data volume and feature representation.

      Future work may explore larger datasets, advanced neural architectures, transfer learning techniques, and explainable AI approaches.

      ---

      ## Author

      **Hikma Hamza**

      Machine Learning Final Project

      African Leadership University

      ---

      ## License

      This repository is intended for academic and educational purposes.
      Machine Learning Final Project


## Author
Hikma Hamza

This repository is intended for academic and educational purposes.

