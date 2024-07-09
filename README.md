# Sales Data Analysis Project

## Project Overview
This project involves analyzing a sales dataset to understand various trends, relationships, and patterns within the data. The goal is to preprocess and clean the data, perform exploratory data analysis (EDA), visualize key insights, and implement machine learning models to predict customer purchases.

## Dataset
The dataset used in this project is named `sales_data (1).csv` and contains various features such as education, marriage, house owner status, age, gender, online status, children, house value, occupation, region, mortgage, family income, and a flag indicating product purchase.

## Project Structure
### Data Loading and Initial Analysis

1. **Import necessary libraries**
2. **Load the dataset into a Pandas DataFrame**
3. **Perform initial data exploration**
   - `head()`, `tail()`, `describe()`, `info()`

### Handling Missing Values

1. **Identify missing values in the columns**
2. **Fill missing values appropriately**

### Data Transformation

1. **Transform categorical variables into numerical values**
2. **Handle special cases and outliers in the data**

### Exploratory Data Analysis (EDA)

1. **Visualize distributions of key variables**
2. **Investigate relationships between variables using crosstabs and plots**
3. **Create pivot tables and heatmaps**

### Feature Scaling

1. **Scale numerical features for better performance in machine learning models**

### Machine Learning Models

1. **Implement Decision Tree, Random Forest, and Logistic Regression models**
2. **Train-test split for model evaluation**
3. **Evaluate model performance using accuracy, classification report, and confusion matrix**

### Cross-Validation

1. **Perform cross-validation to ensure model robustness**

## Detailed Steps
### 1. Data Loading and Initial Analysis
- Import libraries: Pandas, Matplotlib, Seaborn, Sklearn, etc.
- Load the dataset into a DataFrame
- Perform initial exploration using `head()`, `tail()`, `describe()`, and `info()`

### 2. Handling Missing Values
- Identify missing values in education, marriage, and house_owner columns
- Fill missing values with appropriate placeholders or statistical values

### 3. Data Transformation
- Convert categorical variables to numerical values
- Encode ordinal variables such as family income
- Replace missing values in specific columns with predefined values

### 4. Exploratory Data Analysis (EDA)
- Visualize distributions and relationships using bar plots, box plots, crosstabs, and heatmaps
- Gain insights into customer purchase behavior and its relationship with other features

### 5. Feature Scaling
- Apply MinMaxScaler to numerical features like house value for normalization

### 6. Machine Learning Models
- Define dependent (y) and independent (x) variables
- Implement models: Decision Tree, Random Forest, Logistic Regression
- Train and evaluate models using train-test split
- Print accuracy, classification report, and confusion matrix for each model

### 7. Cross-Validation
- Perform cross-validation to validate model performance
- Calculate and print cross-validation scores

## Visualizations
- Distribution plots for variables
- Crosstabs and bar plots for relationships between categorical variables
- Box plots for numerical vs. categorical variable relationships
- Heatmaps for pivot tables to show the impact of multiple variables on customer purchase

## Conclusion
This project provides a comprehensive analysis of the sales data, including data cleaning, transformation, EDA, and machine learning modeling. The insights gained from this analysis can help in understanding customer behavior and predicting future purchases.

## Files
- `sales_data (1).csv`: The dataset used for analysis
- `Predicting Customer Purchase of Life Insurance using Python.py`: Jupyter notebook containing all the code and analysis steps
- `Sentiment Analysis of Donald Trumps Tweets.py`: Jupyter notebook containing all the code and analysis steps

## Requirements
- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn, sklearn

## How to Run
1. Clone the repository or download the project files
2. Open `.py` files in Jupyter Notebook or Google Colab
3. Ensure all necessary libraries are installed
4. Run the notebook cells sequentially to reproduce the analysis and results
