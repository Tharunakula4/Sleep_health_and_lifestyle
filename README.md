# Sleep_health_and_lifestyle
Sleep Health and Lifestyle Analysis:

This project aims to analyze health and lifestyle factors that affect sleep quality using a dataset that includes attributes such as age, occupation, physical activity, stress levels, heart rate, and more. By building predictive models, the objective is to estimate and understand what contributes to good or poor sleep quality and potentially identify patterns linked to sleep disorders.

Overview

The notebook Sleep_health_analysis.ipynb contains the full workflow for this project. It includes data loading, cleaning, transformation, exploratory data analysis (EDA), model training, and result evaluation using several regression models. The goal is to predict Quality of Sleep and understand the most influential health and lifestyle factors.

Getting Started

1.Open the Notebook:

    https://colab.research.google.com/drive/14LfZKFx-yJalBBIrUMsxnBYC8gjVnaXU

2.Install Necessary Libraries:

  Run the following commands in a Colab cell to install required libraries:

         
         pip install pandas numpy matplotlib seaborn scikit-learn xgboost
          

3.Upload the Dataset:

Upload the Sleep_health_and_lifestyle_dataset.csv to your working directory or Colab environment. Ensure the file has columns like sleep duration, stress level, physical activity, blood pressure, heart rate, etc.

4.Run the Notebook:

Execute the notebook cells in order to load the data, preprocess it, perform analysis, and evaluate model performance.

Usage

The notebook covers the following areas:
* Data Exploration: Understanding the structure and distribution of the dataset.
* Data Cleaning and Preprocessing: Dropping irrelevant columns, converting categorical variables, and handling missing values.
* Feature Engineering: Creating new features from raw data (e.g., splitting blood pressure into systolic and diastolic).
* Model Training: Applying multiple machine learning regression models including: Linear Regression, Decision Tree, Random Forest, Gradient Boosting, Support Vector Regression (SVR), XGBoost
* Evaluation: Comparing model performance using Mean Squared Error and R² Score.
* Visualization: Histograms, scatter plots, heatmaps, and pairplots to visualize insights from the data.

Project Structure

- `Sleep_health_analysis.ipynb` :   Main notebook with all analysis and modeling steps
- `requirements.txt` : List of Python dependencies
- data/
  `Sleep_health_and_lifestyle_dataset.csv`  Main dataset used

Acknowledgements

* Dataset Source: [Kaggle or source name]
* Libraries Used: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost

Contact

For questions or feedback, please contact [tharunakula4@gmail.com]
