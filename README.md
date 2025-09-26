# Hotel Booking Cancellation Prediction
## Project Overview

This project develops a machine learning model to predict the likelihood of hotel booking cancellations using historical reservation data. Last-minute cancellations can affect hotel revenue and operational planning. The system uses data preprocessing, feature engineering, and a Random Forest classifier to identify bookings with a high probability of cancellation.

## Key Achievements:

- Achieved high prediction performance using accuracy, precision, and recall metrics.
- Helps hotels proactively manage bookings and reduce revenue loss.
- Implements a complete data-driven workflow from raw data to actionable insights.

## Features

- Data Preprocessing: Handles missing values, categorical encoding, and normalization.
- Feature Engineering: Creates meaningful features to improve prediction performance.
- Predictive Modeling: Uses Random Forest classifier for robust classification.
- Evaluation Metrics: Measures model performance using accuracy, precision, and recall.
- Decision Support: Identifies high-risk bookings to support hotel planning and strategy.

## Technologies & Tools

- Programming Language: Python 3.x
- Libraries: Pandas, NumPy, scikit-learn, Matplotlib, Seaborn
- Machine Learning: Random Forest, Classification Metrics
- Notebook: Colab/VS Code

## Dataset

- Historical hotel booking records (can include features like booking date, lead time, customer type, etc.).
- Dataset split into Training and Testing sets.
- Preprocessing includes: missing value handling, feature encoding, and scaling.

## Model Pipeline

- Data Loading & Cleaning: Import dataset, remove duplicates, handle missing values.
- Feature Engineering: Transform categorical variables, create new features for cancellation patterns.
- Model Training: Random Forest classifier trained on training data.
- Evaluation: Performance evaluated using accuracy, precision, recall, and F1-score.

## Training Details:

- Metrics: Accuracy, Precision, Recall
- Cross-validation applied to improve model generalization
