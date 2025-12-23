# Aluminum Offcut Durability Prediction (Ensemble ML)

## Overview
This project builds a stacked ensemble machine learning model to predict whether an aluminum offcut will pass an extreme durability test. These materials are used in high-stress manufacturing applications, where early identification of low-durability material can reduce waste and improve quality control.

The final model combines CatBoost, LightGBM, XGBoost, and Random Forest using cross-validation, out-of-fold stacking, and probability calibration in a Kaggle-style evaluation setting.

## Problem Motivation
Durability testing is expensive and time-consuming.  
This project explores whether process and material measurements can be used to accurately predict durability outcomes earlier in the production pipeline.

## Modeling Approach
- Tree-based ensemble models:
  - CatBoost  
  - LightGBM  
  - XGBoost  
  - Random Forest  
- 10-fold cross-validation  
- Out-of-fold predictions for stacking  
- Probability calibration for improved interpretability  

## Results
- Stacked ensemble outperformed all individual base models  
- Achieved a top-15 leaderboard ranking (~12th place) in a Kaggle-style evaluation  
- Demonstrated strong performance on nonlinear and high-dimensional manufacturing data  

## Tech Stack
- Python  
- scikit-learn  
- CatBoost, LightGBM, XGBoost  
- pandas, numpy  
- matplotlib  

## Repository Contents
- Final_Submission.ipynb — Full modeling pipeline and analysis  
- README.md — Project overview and documentation  

## Key Takeaways
- Ensemble learning significantly improves predictive performance in manufacturing contexts  
- Probability calibration is important when predictions inform operational decisions  
- Tree-based methods handle complex process interactions effectively  

## Notes
The dataset was provided through a Kaggle competition and is not included due to licensing restrictions.
