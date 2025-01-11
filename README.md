# TechStax_Assignment

# ML Engineer Task

For the [ML Engineer task](https://www.notion.so/ML-Engineer-Task-09beba3065934e8485db8ce418e18710?pvs=21), we will be using the dataset from [Road Accidents](https://drive.google.com/file/d/1edKrdWNOcgbAo2JtckX-PEyM0FdEq4EG/view?usp=drive_link). This dataset provides information about traffic accidents that occurred in the United States.

This project demonstrates the end-to-end process of a Machine Learning (ML) pipeline, from data preprocessing to model evaluation. The pipeline includes feature engineering, data transformation, model training, and testing. The project highlights efficient handling of numerical and categorical features using scikit-learn's ColumnTransformer.


# Features
1. Data Preprocessing:

Handled missing values and inconsistent data.
Scaled numerical features using StandardScaler.
Encoded categorical features using OneHotEncoder.

2. Model Training:

Support for multiple ML models (e.g., Logistic Regression, Random Forest).
Cross-validation for hyperparameter tuning.

3. Evaluation:

Model performance metrics such as accuracy, precision, recall, and F1 score.

# CHANGES TO DATASET-
The Dataset was too large , in order to , for the ease of computation , the original dataset (mltask.csv) is reduced to 5k attributes and named as mltask_sampled.csv
mltask_sampled_cleaned.csv is the data obtained after the cleaning and preprocessing


.
├── data/
│   └── mltask.csv                    # original dataset
│   └── mltask_sampled                # Reduced dataset
│   └── mltask_sampled.csv            # cleaned and preprocessed dataset
├── Computation.ipynb                 # Main script for ML pipeline
├── Code_to_reduce_data.ipynb         # Main script for ML pipeline
├── requirements.txt                  # List of dependencies
└── README.md                         # Project documentation
