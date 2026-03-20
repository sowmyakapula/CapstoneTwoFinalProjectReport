# Capstone Two: Shipment Delivery Prediction

## Project Overview
This project aims to predict whether a shipment will arrive on time using machine learning techniques. Accurate predictions can help improve logistics planning, reduce delays, and enhance customer satisfaction.

---

## Problem Statement
The goal of this project is to predict whether a shipment will arrive on time. Late deliveries increase operational costs and negatively impact customer experience.

---

## Dataset Overview
The dataset contains shipment and customer information, including product cost, shipping details, and customer characteristics.

- Target Variable: `Reached.on.Time_Y.N`
- Includes both numerical and categorical features

---

## Data Preparation
- Removed duplicates and handled missing values  
- Converted categorical variables using one-hot encoding  
- Split data into training and testing sets  
- Applied feature scaling where necessary  

---

## Models Evaluated
- Logistic Regression  
- Decision Tree  
- Random Forest  

Models were evaluated using:
- Accuracy  
- Precision  
- Recall  
- F1 Score  

---

## Model Performance

| Model               | F1 Score |
|--------------------|---------|
| Random Forest      | 0.68    |
| Logistic Regression| 0.65    |
| Decision Tree      | 0.63    |

---

## Final Model
The **Random Forest model** was selected as the final model due to its superior performance.

**Performance Metrics:**
- Accuracy: 0.68  
- Precision: 0.67  
- Recall: 0.68  
- F1 Score: 0.68  
- ROC AUC: 0.75  

---

## Key Insights
- The dataset shows a slight imbalance between on-time and delayed shipments  
- Some features influence delivery outcomes more than others  
- Random Forest provides better predictive performance than simpler models  

---

## Recommendations
- Focus on key factors that influence delivery performance  
- Use predictive modeling to improve logistics planning  
- Collect additional data (e.g., traffic, weather) to improve accuracy  

---

## Future Work
- Perform hyperparameter tuning for better performance  
- Test additional machine learning models  
- Incorporate more detailed operational data  

---

## Files in This Repository
- `CapstoneTwoFinalModelingProject.ipynb` → Full analysis and modeling  
- `Capstone_Two_Final_Report.pdf` → Final report  
- `Capstone_Two_Model_Metrics.txt` → Model details and metrics  
- `Capstone_Two_Presentation.pptx` → Project slides  

---

## Author
Sowmya Sree Kapula
