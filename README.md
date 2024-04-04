Credit Risk Modeling with  Information Value (IV) and Weight of Evidence (WOE)
## Loan Approval Prediction
This repository contains code for predicting loan approval status using logistic regression. Additionally, the analysis includes Information Value (IV) and Weight of Evidence (WOE) Analysis, which are used to assess the predictive power of features and their impact on the loan approval prediction model. IV helps in evaluating the strength of relationship between each feature and the target variable, while WOE provides a transformed representation of the features, making them more suitable for logistic regression modeling. Below are the main components of the code:

### 1. Importing Necessary Modules
- Libraries such as Pandas, Seaborn, NumPy, Matplotlib, and Scikit-learn are imported for data manipulation, visualization, and model training.

### 2. Loading and Exploring Data
- The CSV file containing loan approval data is loaded into a Pandas DataFrame.
- Basic data exploration tasks like checking missing values, data types, and displaying the first few rows are performed.

### 3. Data Preprocessing
- The 'loan_status' column is preprocessed for binary classification, replacing 'Approved' with 1 and 'Rejected' with 0.
- Categorical features like 'education' and 'self_employed' are encoded for logistic regression.

### 4. Exploratory Data Analysis (EDA)
- Data distribution is visualized using boxplots and a pie chart to understand feature distributions and loan status proportions.

### 5. Information Value (IV) Calculation
- IV is calculated for each feature to assess its predictive power regarding loan status.
- A function is defined to categorize IV values into different levels of predictive power.

### 6. Model Training and Evaluation
- The dataset is split into training and testing sets.
- Logistic regression models are trained using both Scikit-learn and Statsmodels.
- Model performance is evaluated using metrics like accuracy and Area Under the Curve (AUC) score.

### 7. Results
- The results of IV calculation and model evaluation are printed to assess feature importance and model performance.
