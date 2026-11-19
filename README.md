# Machine Learning Lab

This repository contains practical implementations of seven Machine Learning experiments using Python and Jupyter Notebook. It is designed to understand fundamental machine learning algorithms, their working principles, implementation, and real-world applications.

## About the Project

The Machine Learning Lab project focuses on exploring different machine learning techniques, including regression, classification, decision trees, K-Nearest Neighbors, and Support Vector Machines.

Each experiment demonstrates the implementation of machine learning concepts using Python libraries, datasets, data preprocessing, model training, visualization, and evaluation techniques.

## Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn

## Experiments Included

| No. | Experiment | Description |
|---|---|---|
| 1 | Exploratory Data Analysis (EDA) | Exploring datasets, handling missing values, understanding data distributions, and creating visualizations. |
| 2 | Linear Regression | Implementing Linear Regression to predict continuous numerical values and understand relationships between variables. |
| 3 | Decision Tree Regression and Cross Validation | Building Decision Tree Regression models, evaluating performance, and applying cross-validation and hyperparameter tuning. |
| 4 | K-Nearest Neighbors (KNN) | Implementing the KNN algorithm for classification and understanding distance-based predictions. |
| 5 | Support Vector Machine (SVM) | Implementing SVM for classification and exploring kernel techniques for handling non-linear data. |
| 6 | Multiple Linear Regression | Predicting a continuous dependent variable using two or more independent variables. |
| 7 | Logistic Regression | Applying Logistic Regression for classification and predicting the probability of observations belonging to different classes. |

## Detailed Overview of Experiments

### 1. Exploratory Data Analysis (EDA)

Exploratory Data Analysis is the process of analyzing and understanding datasets before applying machine learning algorithms.

**Key Concepts:**
- Understanding dataset structure.
- Identifying missing and duplicate values.
- Statistical summary of data.
- Data cleaning and preprocessing.
- Data visualization using graphs and charts.
- Identifying patterns and relationships between variables.

### 2. Linear Regression

Linear Regression is a supervised machine learning algorithm used to predict continuous numerical values by identifying a linear relationship between independent and dependent variables.

**Key Concepts:**
- Simple Linear Regression.
- Independent and dependent variables.
- Regression line.
- Model training and prediction.
- Mean Squared Error (MSE).
- R-squared evaluation.

**Mathematical Equation:**

Y = mX + c

Where:
- Y = Predicted output.
- X = Input variable.
- m = Slope of the regression line.
- c = Intercept.

### 3. Decision Tree Regression and Cross Validation

Decision Tree Regression is a supervised learning algorithm that predicts continuous values by dividing data into smaller groups using decision rules.

Cross-validation is a model evaluation technique used to check how well a machine learning model performs on different subsets of data.

**Key Concepts:**
- Decision Tree structure.
- Root nodes, decision nodes, and leaf nodes.
- Splitting criteria.
- Overfitting and model complexity.
- Cross-validation.
- Hyperparameter tuning.
- Grid Search.

### 4. K-Nearest Neighbors (KNN)

K-Nearest Neighbors is a supervised machine learning algorithm used for classification and regression. It predicts the output based on the nearest data points.

**Key Concepts:**
- Distance-based classification.
- Selection of K value.
- Euclidean distance.
- Training and testing datasets.
- Model prediction.
- Classification accuracy.

**Euclidean Distance Formula:**

d = √[(x2 - x1)² + (y2 - y1)²]

### 5. Support Vector Machine (SVM)

Support Vector Machine is a supervised machine learning algorithm mainly used for classification. It finds an optimal hyperplane that separates data points belonging to different classes.

**Key Concepts:**
- Hyperplane.
- Support vectors.
- Maximum margin.
- Linear and non-linear classification.
- Kernel functions.
- Model training and evaluation.

**Common Kernel Functions:**
- Linear Kernel.
- Polynomial Kernel.
- Radial Basis Function (RBF) Kernel.

### 6. Multiple Linear Regression

Multiple Linear Regression is a supervised machine learning algorithm used to predict a continuous dependent variable using two or more independent variables.

It extends simple Linear Regression by considering multiple input features to make predictions.

**Key Concepts:**
- Multiple independent variables.
- One dependent variable.
- Regression coefficients.
- Model training and prediction.
- Relationship between input and output variables.
- Model evaluation using MSE and R-squared.

**Mathematical Equation:**

Y = b0 + b1X1 + b2X2 + ... + bnXn

Where:
- Y = Predicted output.
- b0 = Intercept.
- b1, b2, ..., bn = Regression coefficients.
- X1, X2, ..., Xn = Independent variables.

**Applications:**
- House price prediction.
- Sales forecasting.
- Business analysis.
- Demand prediction.

### 7. Logistic Regression

Logistic Regression is a supervised machine learning algorithm primarily used for classification problems. It predicts the probability that an observation belongs to a particular class.

It uses the sigmoid function to convert a linear combination of input features into a probability between 0 and 1.

**Key Concepts:**
- Supervised classification.
- Binary classification.
- Sigmoid function.
- Probability prediction.
- Decision boundary.
- Classification accuracy.
- Confusion matrix.

**Sigmoid Function:**

P = 1 / (1 + e^(-z))

Where:
- P = Predicted probability.
- e = Euler's number.
- z = Linear combination of input features and coefficients.

**Applications:**
- Email spam detection.
- Disease classification.
- Customer churn prediction.
- Fraud detection.

## Project Structure

```text
Machine_Learning_Lab/
│
├── ml_lab_1(EDA).ipynb
├── ml_lab_2_linear_regression.ipynb
├── Deicsion_Tree_Regression_And_Cross_Validation.ipynb
├── ml_labK_Nearest_Neighbors_with_Python.ipynb
├── SVM_ML_LAB.ipynb
├── Multiple_Linear_Regression.ipynb
├── Logistic_Regression.ipynb
│
└── README.md
```

## Installation and Setup

Follow these steps to run the project on your local machine.

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/Machine-Learning-Lab.git
```

### Step 2: Navigate to the Project Directory

```bash
cd Machine-Learning-Lab
```

### Step 3: Install Required Libraries

```bash
pip install numpy pandas matplotlib seaborn plotly scikit-learn jupyter openpyxl
```

### Step 4: Launch Jupyter Notebook

```bash
jupyter notebook
```

### Step 5: Run the Experiments

Open the required `.ipynb` notebook and execute the cells sequentially.

## Learning Outcomes

After completing these experiments, you will be able to:

- Understand fundamental machine learning concepts.
- Perform exploratory data analysis and data preprocessing.
- Implement Simple and Multiple Linear Regression.
- Understand and apply Logistic Regression.
- Build Decision Tree Regression models.
- Implement K-Nearest Neighbors.
- Understand Support Vector Machines and kernel functions.
- Evaluate machine learning model performance.
- Apply cross-validation and hyperparameter tuning.
- Work with Python machine learning libraries.

## Future Improvements

- Add more machine learning algorithms.
- Include practical implementations of advanced classification techniques.
- Compare the performance of different algorithms.
- Work with additional real-world datasets.
- Improve model evaluation and visualization.

## Author

**Sahil**

## License

This project is created for educational and learning purposes.
