# Machine-Failure-Predictive-Maintenance-Project

## Project Overview
This project develops a machine learning solution for predicting machine failures using various classification algorithms. The goal is to create a predictive maintenance model that can anticipate potential equipment breakdowns.

## Key Features
- Comprehensive machine failure prediction
- Multiple machine learning models implemented
- Detailed data preprocessing and analysis
- Performance evaluation using various metrics

## Dependencies
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- category_encoders

## Installation

1. Install required dependencies:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Data Preprocessing
- Dropped unnecessary columns (UDI, Product ID)
- Encoded categorical variables
- Performed feature scaling
- Split data into training and testing sets

## Models Implemented
1. Logistic Regression
2. Support Vector Machine (SVM)
   - Standard SVM
   - Linear SVM
3. Random Forest Classifier

## Model Performance
Random Forest Classifier showed the best performance, with key metrics available in the classification report.

## Visualization
- Correlation matrix heatmap
- Target distribution pie chart
- Failure type frequency bar chart

## Model Valuation 
With the above machine learning model, on evaluating obtains an accuracy score of 99.8%  
