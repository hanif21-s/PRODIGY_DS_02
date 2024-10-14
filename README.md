Titanic Survival Prediction: EDA

This project focuses on performing data cleaning and exploratory data analysis (EDA) on the Titanic dataset from Kaggle. The goal is to explore relationships between different variables and identify factors affecting passenger survival.
Dataset

The dataset consists of three CSV files:

    train.csv: Training data with survival labels.
    test.csv: Test data (no labels).
    gender_submission.csv: Sample submission file.

Dataset source: [Kaggle Titanic Dataset.](https://www.kaggle.com/c/titanic/data)
Key Steps
1. Data Cleaning

    Missing Data: Age and Embarked columns were imputed with median and mode, respectively.
    Categorical Variables: Sex and Embarked columns were converted to numerical values.

2. Exploratory Data Analysis (EDA)

    Correlation Heatmap: Showed strong negative correlation of Pclass (-0.34) and Sex (-0.54) with survival.
    Visualizations:
        Survival by Pclass (1st class had higher survival).
        Survival by Gender (females had higher survival).
        Age distribution (minimal impact on survival).

Technologies Used

    Python (Pandas, Seaborn, Matplotlib)
    Google Colab
