# House Price Prediction using Machine Learning

## Overview
This project is about building a machine learning model to predict house prices based on factors like living area, number of bedrooms, bathrooms, and other important features.

The main idea was to understand how different attributes affect house pricing and to create a model that can give a reasonable estimate for new data.

---

## Features
- Predicts house prices based on user input  
- Uses a real-world housing dataset  
- Implements and compares multiple machine learning models  
- Evaluates performance using R² score  
- Displays output in INR (Crores and Lakhs format) for better understanding  

---

## Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  

---

## Models Implemented
- Linear Regression  
- Random Forest Regressor  

---

## Model Performance
- Linear Regression R² Score: 0.52  
- Random Forest R² Score: 0.56  

After experimenting with both models, Random Forest performed slightly better. This improvement came from adding better features and tuning the model parameters.

---

## Workflow
1. Loaded and explored the dataset to understand the features  
2. Cleaned and prepared the data for training  
3. Selected important features affecting house prices  
4. Trained a Linear Regression model as a baseline  
5. Improved the model using Random Forest  
6. Evaluated performance using R² score  
7. Tested the model with new input data  

---

## Sample Prediction
Input:
- Living Area: 3000 sq ft  
- Bedrooms: 4  
- Bathrooms: 3  

Output:
- Predicted Price: ₹X Crore Y Lakh  

---

## Conclusion
This project helped in understanding how machine learning models can be applied to real-world problems like price prediction. It also showed the importance of feature selection and model choice in improving performance.

---

## Future Improvements
- Include more location-based features for better accuracy  
- Apply advanced hyperparameter tuning techniques  
- Add visualizations to better understand predictions  
- Build a simple web interface using Streamlit  

---

## Author
Karanam Shasank
