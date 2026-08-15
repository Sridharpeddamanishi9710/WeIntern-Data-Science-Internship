# WeIntern Data Science Internship

This repository contains the projects and tasks completed as part of the **WeIntern Data Science Internship**.

## Domain

**Data Science & Analytics**

---

# Task 1 – Titanic Dataset Exploratory Data Analysis

## Project Overview

This project performs Exploratory Data Analysis (EDA) on the Titanic dataset to understand passenger characteristics and identify patterns associated with passenger survival.

The analysis includes data cleaning, feature analysis, statistical analysis, visualization, and correlation analysis.

## Dataset

The Titanic dataset was obtained from Kaggle.

Dataset: https://www.kaggle.com/competitions/titanic/data

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Analysis Performed

- Dataset structure and data types
- Missing value analysis
- Duplicate record checking
- Missing value handling
- Age analysis
- Gender vs survival
- Passenger class vs survival
- Fare vs survival
- Family size vs survival
- Embarkation port vs survival
- Gender and passenger class analysis
- Correlation analysis
- Data visualization

## Key Findings

- Female passengers had a much higher survival rate than male passengers.
- First-class passengers had a higher survival rate than second- and third-class passengers.
- Children had the highest survival rate among the defined age groups.
- Surviving passengers paid a higher average fare than non-surviving passengers.
- Small family groups generally showed higher survival rates.
- Cherbourg had the highest observed survival rate among the three embarkation ports.
- Gender and passenger class together showed strong differences in survival.

## Conclusion

The analysis identified several important patterns associated with Titanic passenger survival, particularly gender and passenger class. The project demonstrates the use of Python-based data cleaning, exploratory analysis, visualization, and statistical techniques.

---

# Task 2 – Movie Recommendation System

## Project Overview

This project develops a **content-based movie recommendation system** using the TMDB 5000 Movies and Credits datasets.

The system recommends movies based on similarities between movie characteristics such as genres, keywords, cast, director, and overview.

## Datasets

The project uses two datasets:

- TMDB 5000 Movies Dataset
- TMDB 5000 Credits Dataset

Both datasets contain information about approximately 4,803 movies.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook
- TF-IDF Vectorization
- Cosine Similarity

## Data Processing

The following steps were performed:

- Loaded the movies and credits datasets
- Inspected dataset structure and columns
- Checked missing values
- Merged the two datasets using movie ID
- Extracted relevant movie information
- Extracted genres
- Extracted keywords
- Extracted top cast members
- Extracted movie directors
- Combined relevant information into a `tags` feature
- Applied text vectorization
- Calculated cosine similarity between movies

## Recommendation System

A content-based recommendation approach was implemented using **TF-IDF Vectorization** and **Cosine Similarity**.

The system takes a movie title as input and returns the five most similar movies.

### Example

For **Avatar**, the system generated the following recommendations:

1. Aliens
2. Alien³
3. Mission to Mars
4. Moonraker
5. Alien

The system also handles invalid movie titles by displaying:

`Movie not found. Please enter a valid movie title.`

## Conclusion

The project demonstrates how text-based movie attributes can be combined and transformed into numerical representations to build a content-based recommendation system. Cosine similarity was then used to identify movies with similar characteristics.

---

# Task 3 – House Price Prediction Using Machine Learning

## Project Overview

This project develops a machine learning regression model to predict house prices using property-related features.

The project covers data preprocessing, categorical encoding, feature scaling, model training, prediction, evaluation, and visualization.

## Dataset

The Housing Prices dataset contains:

- **545 rows**
- **13 columns**

The target variable is `price`.

### Features

- area
- bedrooms
- bathrooms
- stories
- mainroad
- guestroom
- basement
- hotwaterheating
- airconditioning
- parking
- prefarea
- furnishingstatus

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## Data Preprocessing

The following preprocessing steps were performed:

- Dataset structure inspection
- Missing value analysis
- Duplicate checking
- Separation of features and target
- One-hot encoding of categorical variables
- Train/test split
- Feature scaling using StandardScaler

### Dataset Split

- Training samples: **436**
- Testing samples: **109**

After one-hot encoding:

- Features before encoding: **12**
- Features after encoding: **13**

## Machine Learning Model

A **Linear Regression** model was trained to predict house prices.

## Model Evaluation

| Metric | Result |
|---|---:|
| RMSE | 1,324,506.96 |
| R² Score | 0.6529 |

The R² score of **0.6529** indicates that the model explains approximately **65.29% of the variation** in house prices in the test dataset.

## Visualization

The project includes:

- Actual vs Predicted House Prices visualization
- Feature importance visualization using Linear Regression coefficients

## Key Findings

The strongest positive coefficients in the trained model were observed for:

- Bathrooms
- Area
- Air conditioning
- Stories
- Preferred area
- Parking
- Basement

Bathrooms and area had the largest coefficient magnitudes among the model features.

## Sample Prediction

For one test sample:

| Measure | Value |
|---|---:|
| Actual Price | 4,060,000 |
| Predicted Price | 5,164,653.90 |
| Prediction Error | 1,104,653.90 |

## Conclusion

A complete machine learning pipeline was developed for house price prediction. The Linear Regression model achieved an RMSE of **1,324,506.96** and an R² score of **0.6529** on the test set.

The project demonstrates practical application of data preprocessing, categorical encoding, feature scaling, regression modeling, model evaluation, and visualization.

---

# Repository Structure
```text
WeIntern-Data-Science-Internship/
│
├── Task_1_EDA/
│   ├── Task-1_EDA_On_PublicDataset.ipynb
│   ├── Tak-1_EDA_Titanic_Dataset_Report.docx
│   └── train.csv
│
├── Task_2_Movie_Recommendation/
│   ├── Task_2_Movie_Recommendation.ipynb
│   ├── Task_2_Movie_Recommendation_Report.docx
│   ├── tmdb_5000_movies.csv
│   └── tmdb_5000_credits.csv
│
├── Task_3_House_Price_Prediction/
│   ├── House_Price_Prediction.ipynb
│   ├── Task_3_House_Price_Prediction_Report.docx
│   └── Housing.csv
│
└── README.md
```

# Overall Internship Skills Demonstrated:

Through these tasks, the following skills were applied:

Exploratory Data Analysis
Data Cleaning
Data Preprocessing
Data Visualization
Statistical Analysis
Feature Engineering
One-Hot Encoding
Feature Scaling
Machine Learning
Linear Regression
Model Evaluation
RMSE and R²
Content-Based Recommendation Systems
TF-IDF Vectorization
Cosine Similarity
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
Jupyter Notebook
Git and GitHub

# Internship Progress
| Task   | Project                                     | Status       |
| ------ | ------------------------------------------- | -----------  |
| Task 1 | Titanic Dataset – Exploratory Data Analysis | ✅ Completed |
| Task 2 | Movie Recommendation System                 | ✅ Completed |
| Task 3 | House Price Prediction                      | ✅ Completed |

**Author**

Sridhar Pedhamanishi

B.Tech – Information Technology

MVSR Engineering College
