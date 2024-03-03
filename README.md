# **Overview**
Coffee Rating Prediction Project (Regression models)
This project focuses on predicting the ratings of different coffee blends using data scraped from Coffee Review. The goal is to build models that can accurately predict the quality or rating of a coffee based on various features.

# **Business Value - Purpose**

### **1. Quality Assurance for Coffee Producers:**
Coffee producers can use the predictive models to assess the potential rating of their coffee blends before they are officially reviewed. This allows them to refine their blends and improve quality based on predicted feedback.

### **2. Inventory Management for Retailers:**
Retailers and distributors can leverage the predictive models to estimate the potential popularity and demand for different coffee blends. This assists in optimizing inventory, ensuring that popular blends are adequately stocked.

### **3. Consumer Recommendations:**
The models can be integrated into platforms or apps to provide personalized coffee recommendations to consumers based on their preferences. This enhances the user experience and may lead to increased customer satisfaction and loyalty.

### **4. Market Positioning and Pricing:**
Coffee brands can strategically position and price their products based on predicted ratings. This insight can help them set competitive prices and market their products effectively.

### **5. Resource Allocation:**
The project can assist in allocating resources efficiently, focusing on the development of coffee blends that are likely to receive higher ratings. This can optimize time and investment in research and development.

### **6. Competitive Advantage:**
Having a predictive model for coffee ratings can provide a competitive advantage in the industry. Proactively using data to enhance product quality and customer satisfaction sets a brand apart from competitors.

### **7. Customer Engagement:**
Engage customers by incorporating the predictive model into interactive tools or apps that allow them to explore and discover new coffee blends based on their predicted ratings.

### **8. Data Monetization:**
Consider the possibility of monetizing the predictive models by offering insights or predictions as a service to other businesses in the coffee industry.


**Methods Used**
1. Python

2. Data Cleaning and transformation

3. Visualization and correlation matrix
Used to see correlation betweens features and extract usefull insights for building my models.

4. Normalization with LabelEncoder
Used for encoding categorical labels into numerical values. It's commonly used when dealing with categorical variables in machine learning models.

5. Train_test_split 
Splits your dataset into training and testing sets. This is essential for assessing the model's performance on unseen data.

6. Additional preprocessing functionalities such as scaling and centering the data. It includes methods like StandardScaler and MinMaxScaler.

7. Cross_val_score from sklearn.model_selection:
Performs cross-validation on my models. It helps to estimate the performance of a machine learning model by splitting the data into multiple subsets (folds) and training/evaluating the model on each fold.

8. Ridge, Lasso, LinearRegression 
These are linear regression models with different regularization techniques. Ridge and Lasso are used for adding regularization terms to prevent overfitting in linear regression models.

9. ElasticNet  
Combines L1 (Lasso) and L2 (Ridge) regularization terms in linear regression. Useful when dealing with a dataset with many features.

10. Built more complex models and compare with previous simpler models
GradientBoostingRegressor 
XGBRegressor

11. Using metrics to compare models:
r^2_score 
Calculates the R-squared coefficient of determination. It measures the proportion of the variance in the dependent variable that is predictable from the independent variables.

mean_squared_error 
Computes the mean squared error, a commonly used metric to evaluate the performance of regression models.