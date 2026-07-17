# My Machine Learning Journey

> *A comprehensive roadmap of my machine learning learning process, starting from January 2025*

---

## Journey Timeline & Roadmap

```
┌───────────────────────────────────────────────────────────────────────────────┐
│                                                                               │
│  JAN-APR 2025        APR-SEPT 2025      OCT-DEC 2025          JAN+ 2026       │
│  ┌────────────┐     ┌─────────────┐   ┌──────────────┐    ┌──────────────┐    │
│  │ Foundation │──▶ │ Data Tools  │──▶│  Mathematics │──▶│ Algorithms   │    │
│  │ & Basics   │     │ & Gathering │   │   & Theory   │    │ & ML Models  │    │
│  └────────────┘     └─────────────┘   └──────────────┘    └──────────────┘    │
│       │                   │                   │                   │           │
│   Fundamentals      Tools & Pipelines   Theory & Math          Practice       │
│                                                                               │
└───────────────────────────────────────────────────────────────────────────────┘
```

---

## Phase 1: Foundation & Basics (January-April 2025)

### Python Fundamentals
- **Python Basics**: Data types, control flow, functions, loops
- **Object-Oriented Programming (OOP)**: Classes, inheritance, polymorphism, encapsulation
- **Location**: [python-basics/](Phase-1-Foundation/python-basics/)

> *Master the foundation before building the house!*

---

## Phase 2: Data Tools & Gathering (April-September 2025)

Essential libraries for data manipulation and visualization:

### NumPy
- Array operations and numerical computing
- Matrix manipulations and linear algebra basics
- **Location**: [numpy/](Phase-2-Data-Tools/numpy/)

### Pandas
- Data frames and series manipulation
- Data reading/writing (CSV, JSON, etc.)
- Data cleaning and transformation
- **Location**: [Pandas/](Phase-2-Data-Tools/Pandas/)

### Matplotlib
- Static visualization and plotting
- Customization and styling
- **Location**: [Matplotlib/](Phase-2-Data-Tools/Matplotlib/)

### Plotly
- Interactive visualizations
- Advanced charting and dashboards
- **Location**: [plotly/](Phase-2-Data-Tools/plotly/)

---

### Web Scraping Techniques
- **BeautifulSoup**: Parse and extract data from HTML/XML
- **Selenium**: Automate browser interactions and dynamic scraping

### Data Gathering Concepts
- Web scraping best practices
- API interaction
- Data collection strategies
- **Location**: [Data Gatheriing/](Phase-2-Data-Tools/Data%20Gatheriing/)

---

### Data Cleaning & Preparation

Transforming raw data into usable datasets:

### Data Cleaning Tasks
- Handling missing values
- Outlier detection and treatment
- Data validation and consistency checks
- Duplicate removal
- Type conversions and standardization
- **Location**: [Data cleaning/](Phase-2-Data-Tools/Data%20cleaning/)

---

### Feature Engineering

Creating powerful features for better model performance:

### Feature Construction
- Creating new features from existing data
- Domain-specific feature creation

### Feature Selection
- Filter Methods
- Wrapper Methods
- Embedded Methods

### Feature Transformation

**Encoding**
- One Hot Encoding
- Ordinal Encoding
- Label Encoding

**Scaling/Normalization**
- MinMax Normalization
- Standardization (Standard Scaler)
- Robust Scaling

**Mathematical Transformations**
- Log Transformation
- Square Root Transformation
- Squared Transformation
- Reciprocal Transformation
- Power Transformation

**Distribution Transformations**
- Box-Cox Transformation
- Yeo-Johnson Transformation

**Other Transformations**
- Binarization
- Discretization

### Feature Extraction
- **Principal Component Analysis (PCA)** 
  - Understanding covariance matrices
  - Eigenvalues and eigenvectors in PCA
  - Dimensionality reduction concepts
  - Variance explained
  - Principal component selection
  - Implementation and applications
- **Location**: [Feature Engineering/](Phase-2-Data-Tools/Feature%20Engineering/)

---

## Phase 3: Mathematics for ML (October-December 2025)

The mathematical backbone of machine learning:

### Linear Algebra
- Vectors and Matrices
- Matrix operations and transformations
- Eigenvalues and Eigenvectors
- Matrix decomposition
- **Location**: [linalg/](Phase-3-Mathematics/linalg/)

### Probability & Statistics
- Probability fundamentals
- Probability distributions (Normal, Binomial, Poisson, etc.)
- Descriptive statistics (mean, median, variance, etc.)
- Hypothesis testing
- **Location**: [probability distribution/](Phase-3-Mathematics/probability%20distribution/) & [descriptive stats/](Phase-3-Mathematics/descriptive%20stats/) & [hypo test/](Phase-3-Mathematics/hypo%20test/)
- **Learning Resource**: https://www.video-tutor.net/statistic.html

### Calculus
- Derivatives and gradients
- Optimization fundamentals
- Integration basics

---

## Phase 4: Machine Learning Algorithms & Models (January+ 2026)

### Optimization Techniques

#### Gradient Descent
- From scratch implementation
- Batch Gradient Descent
- Stochastic Gradient Descent (SGD)
- Mini-Batch Gradient Descent
- **Location**: [Gradient Descent/](Phase-4-ML-Algorithms/Gradient%20Descent/)

---

### Linear Regression Models

#### Simple Linear Regression
- Ordinary Least Squares (OLS)
- Single variable prediction

#### Multiple Linear Regression
- OLS with multiple features
- Feature relationships

#### Polynomial Regression
- Non-linear relationships
- Higher-degree polynomial fitting

- **Location**: [Linear Regression/](Phase-4-ML-Algorithms/Linear%20Regression/)

---

### Regularization Techniques

Preventing overfitting and improving generalization:

#### Ridge Regression (L2 Regularization)
- Penalty on coefficient magnitude
- Shrinkage method

#### Lasso Regression (L1 Regularization)
- Feature selection through shrinkage
- Sparse models

#### ElasticNet Regression
- Combination of L1 and L2
- Best of both worlds

- **Location**: [Regularization/](Phase-4-ML-Algorithms/Regularization/)

---

### Classification Models

#### Logistic Regression
- **Binary Classification**: Two-class problems
- **Multinomial Classification (Softmax)**: Multi-class with probability distributions
- **One-vs-Rest (OvR)**: Multi-class strategy
- **Maximum Likelihood Estimation (MLE)**: Optimization method for logistic regression
- **Regularization in Logistic Regression**: L1 and L2 regularization for preventing overfitting

- **Location**: [Logistic Regression/](Phase-4-ML-Algorithms/Logistic%20Regression/)

#### K-Nearest Neighbors (KNN)
- Instance-based learning
- K-selection strategies
- Cross-validation for optimal K
- **Location**: [K-Nearest Neighbors/](Phase-4-ML-Algorithms/K-Nearest%20Neighbors/)

#### Naive Bayes
- Probabilistic classifier
- Bayes' theorem application
- Assumptions and limitations
- **Location**: [Naive Bayes/](Phase-4-ML-Algorithms/Naive%20Bayes/)

#### Support Vector Machines (SVM)
- Hard margin and soft margin classification
- Linear classification
- Margin maximization and hinge loss
- Constrained optimization problem formulation (primal form)
- Dual form optimization
- Kernel trick and kernelized SVM (non-linear classification)
- Session on Constraint optimization problem
- SVM dual formulation and optimization
- Mathematical intuition behind SVM kernels
- **Location**: [SVM/](Phase-4-ML-Algorithms/Support%20Vector%20Machine%20(SVM)/)

#### Decision Tree
- CART algorithm (Classification and Regression Trees)
- Split criteria and greedy recursive partitioning
- Tree growth, stopping criteria, and pruning basics
- **Location**: [Decision Tree/](Phase-4-ML-Algorithms/Decision%20Tree/)

---

### Ensemble Learning

Combining multiple models to improve prediction stability and performance:

- **Location**: [Ensemble Learning/](Phase-4-ML-Algorithms/Ensemble%20Learning/)

#### Ensemble Learning Basics
- What ensemble learning is and why it works
- Wisdom of the crowd and consensus-based learning
- Basic types of ensemble learning:
  - Voting
  - Bagging
  - Boosting
  - Stacking

#### Voting
- Completed voting ensemble concepts
- Checked related code implementations

#### Stacking
- Completed stacking ensemble concepts
- Checked related code implementations

#### Bagging
- Completed basic bagging concepts
- Bootstrap Aggregation: training multiple models on sampled datasets
- Sampling styles:
  - Bootstrap sampling
  - Sampling with replacement
  - Sampling without replacement
  - Row sampling
  - Column sampling
  - Random subspace sampling
  - Balanced bootstrap sampling
  - Random patches
- Out-of-Bag (OOB) score
- GridSearchCV for hyperparameter tuning
- Bagging classifier
- Bagging regressor

#### Random Forest
- Completed Random Forest topic
- Covered Random Forest basics and intuition
- Completed Random Forest coding implementation
- Studied Extremely Randomized Trees concept inside Random Forest
- **Location**: [Random Forest/](Phase-4-ML-Algorithms/Ensemble%20Learning/Bagging/Random%20Forest/)

#### Boosting
- Completed Boosting algorithms topic
- Covered sequential ensemble learning and error-correction intuition
- Completed Gradient Boosting concepts and implementation
- Completed AdaBoost learning notebook
- Completed XGBoost learning notebook and reviewed the XGBoost paper
- Completed LightGBM learning notebook
- Completed CatBoost learning notebook
- **Location**: [Boosting/](Phase-4-ML-Algorithms/Ensemble%20Learning/Boosting/)

---

### Machine Learning Fundamentals & Workflow

#### Core Concepts
- Bias-Variance Tradeoff: Understanding model complexity
- Multicollinearity: Feature relationships and remedies
- Regression Analysis: Model evaluation and interpretation
- **Location**: [Model Workflow/](Phase-4-ML-Algorithms/Model%20Workflow/)

---

### Dimensionality Reduction

#### Principal Component Analysis (PCA)
- Covariance matrix computation
- Eigenvalue decomposition
- Feature reduction and variance preservation
- Interpreting principal components
- When to use PCA
- **Location**: [Feature Engineering/](Phase-2-Data-Tools/Feature%20Engineering/)

---

## Repository Philosophy

This repository serves as:
- **A Learning Logbook**: Tracking my journey through ML
- **A Reference Guide**: Implementations and explanations of key concepts
- **An Experiment Ground**: Testing new ideas and techniques
- **A Roadmap**: For others starting their ML journey

> *Machine Learning is not just about algorithms—it's about understanding data, mathematics, and building intuition through practice.*

---

## Acknowledgments

This journey reflects dedication to:
- Understanding fundamentals before advanced topics
- Theory and practical implementation together
- Continuous learning and experimentation
- Building projects with real-world applications

---

**Last Updated**: 17th July 2026 | *Continuously Learning & Growing*
