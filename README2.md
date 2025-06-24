Task 2 : Exploratory Data Analysis (EDA)

# Objective:

To perform on the Titanic dataset to understand the Titanic dataset structure using statistics and visualizations to identify patterns, trends, anomalies,feautures and key insights that can help in building machine learning models.

# Tools Used

 Python  
 Pandas for data manipulation  
 Matplotlib
 seaborn for visualizations  
 Plotly for interactive charts  

# Dataset Used:

-[Titanic Dataset on Kaggle](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
-File Used: 'Titanic-Dataset.csv'

# Steps Performed:

1. Loaded the dataset and viewed basic structure using `.info()` and `.describe()`
2. Checked for missing values using `.isnull().sum()`
3. Visualized distributions of numerical features (`Age`, `Fare`) using histograms and KDE plots
4. Created boxplots to detect outliers in `Age` and `Fare`
5. Generated a correlation matrix heatmap using numeric columns
6. Plotted Pair plots to observe relationships between key features (`Survived`, `Pclass`, `Age`, `Fare`)
7. Analyzed survival counts using bar plots for `Survived`, `Pclass`, and `Sex`
8. Plotted interactive histogram using Plotly to show `Age` vs `Survival`

# Key Visualizations & Insights:

Histograms & Boxplots: Analyzed distribution of Age and Fare
Correlation Heatmap: Checked relationships between numerical features
Pair Plot: Visualized feature clusters and survival separation
Categorical Analysis: Higher survival rate among females and passengers in Pclass 1
Missing Data: Detected missing values in Age, Cabin, and Embarked

# Summary:

Females and 1st class or young passengers had significantly higher survival rates.
Age and Fare were skewed and had outliers.
Cabin had a large number of missing values and may need to be dropped or engineered.

# Submission:

Submitting this GitHub repository using the internship form link.

# Output:

Visualizations for insights on survival rates, distributions, and correlations
Python Notebook: Task2.ipynb
Readme.md: Explained what I did in detail

