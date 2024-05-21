# Tips Dataset Classification

This project demonstrates a machine learning pipeline using the Tips dataset from seaborn. The pipeline includes data preprocessing, feature engineering, model training, and evaluation.

## Dataset

The dataset used is the 'tips' dataset from seaborn, which includes information about tips received in a restaurant.

## Steps

### Data Loading and Exploration

- Load the dataset using `sns.load_dataset('tips')`.
- Explore the dataset using `df.head()`, `df.describe()`, and checking for missing values.

### Data Preprocessing

- Encode categorical variables using `LabelEncoder`.
- Split the data into training and testing sets using `train_test_split`.

### Feature Engineering

- Create pipelines for numerical and categorical features using `Pipeline` and `ColumnTransformer`.

### Model Training and Evaluation

- Train and evaluate multiple models (`RandomForestClassifier`, `DecisionTreeClassifier`, and `LogisticRegression`) using a custom `evaluate_model` function.
- Perform hyperparameter tuning using `RandomizedSearchCV`.

## Results

The models achieved the following accuracy scores:

- **Random Forest**: 95.92%
- **Decision Tree**: 93.88%
- **Logistic Regression**: 100%



