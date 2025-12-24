Smart Crop Yield Prediction System
Description

A machine learning system to predict crop yield based on weather, soil, fertilizer, and crop type. Built using Random Forest Regressor with 84% prediction accuracy. Safe user input handling ensures reliable predictions for unseen data.

Features

Predicts crop yield (tons/ha) from user inputs

Handles categorical data: Season, Crop Type

Feature importance visualization for better insights

Safe encoding for user input not present in training data

Cross-validation for reliable accuracy

Model saving/loading using joblib

Dataset

Input features: Avg_Temp_c, Soil_Moisture_pct, Soil_pH, Fertilizer_kg_per_hectare, Soil_Quality_Index, Season, Rainfall_mm, Crop_Type

Output: Crop_Yield_ton_per_ha
