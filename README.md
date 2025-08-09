# UCI Online Shoppers Purchasing Intention Dataset Analysis

This project provides a comprehensive analysis of the UCI Online Shoppers Purchasing Intention Dataset, focusing on understanding customer behavior and predicting purchase intentions using machine learning techniques.

## 📊 Dataset Overview

The UCI Online Shoppers Purchasing Intention Dataset contains browsing behavior data from e-commerce sessions. The dataset includes various features about user sessions such as:

- **Administrative/Informational/ProductRelated Pages**: Number of pages visited in each category
- **Duration Features**: Time spent on different page types
- **Bounce/Exit Rates**: User engagement metrics
- **Page Values**: Average value of pages visited
- **Special Day**: Closeness to special days (holidays)
- **Month**: Month of the session
- **Operating Systems/Browser/Region/Traffic Type**: Technical and geographical information
- **Visitor Type**: New vs Returning visitors
- **Weekend**: Whether the session occurred on weekend
- **Revenue**: Target variable indicating whether the session resulted in a transaction

## 📁 Project Structure

```
.
├── EDA.ipynb          # Exploratory Data Analysis
├── ML.ipynb           # Machine Learning Models
└── README.md          # Project documentation
```

## 🔍 Analysis Components

### 1. Exploratory Data Analysis (EDA.ipynb)

The EDA notebook includes:

- **Data Loading and Overview**: Fetching data from UCI repository and basic information
- **Data Quality Assessment**: Missing values analysis and data types examination
- **Target Variable Distribution**: Analysis of revenue/purchase patterns
- **Feature Distributions**: Histograms and statistical summaries
- **Correlation Analysis**: Feature relationships using correlation matrices and heatmaps
- **Customer Segmentation**: Analysis by visitor types (New, Returning, Other)
- **Temporal Analysis**: Revenue patterns by months and special days
- **Geographic Analysis**: Regional patterns and operating system preferences
- **Behavioral Analysis**: Page values, bounce rates, and session duration patterns
- **Visual Analytics**: Various plots including pair plots, box plots, and pie charts

### 2. Machine Learning (ML.ipynb)

The ML notebook includes:

- **Data Preprocessing**: 
  - Feature encoding (Label encoding for binary features, One-hot encoding for categorical features)
  - Data type conversions
  - Train-test split with stratification
- **Model Training**: XGBoost classifier implementation
- **Model Evaluation**: 
  - Accuracy, Precision, Recall, F1-score
  - ROC-AUC analysis
  - Confusion matrix
- **Prediction Pipeline**: Complete workflow from raw data to predictions

## 🚀 Getting Started

### Prerequisites

```bash
pip install ucimlrepo pandas seaborn matplotlib scikit-learn xgboost numpy
```

### Running the Analysis

1. **Exploratory Data Analysis**: Open and run `EDA.ipynb` to understand the dataset and visualize patterns
2. **Machine Learning**: Open and run `ML.ipynb` to train models and evaluate performance

### Key Libraries Used

- **Data Manipulation**: pandas, numpy
- **Visualization**: matplotlib, seaborn
- **Machine Learning**: scikit-learn, xgboost
- **Data Source**: ucimlrepo

## 📈 Key Insights

The analysis reveals important patterns in online shopping behavior:

- Customer segmentation by visitor types shows different purchasing patterns
- Temporal patterns indicate seasonal variations in purchasing behavior
- Geographic and technical factors influence conversion rates
- Page engagement metrics are strong predictors of purchase intention

## 🎯 Model Performance

The XGBoost classifier demonstrates strong performance in predicting purchase intentions, with detailed metrics available in the ML notebook including accuracy, precision, recall, and AUC scores.

## 🤝 Contributing

Feel free to fork this repository and submit pull requests for improvements or additional analysis.

## 📄 Dataset Citation

C. Sakar and Yomi Kastro. Online Shoppers Purchasing Intention Dataset. [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/468/online+shoppers+purchasing+intention+dataset).



