### Customer Spending Prediction Project

## About Dataset

### 1. Data Source

This dataset contains customer-related information designed to analyze customer purchasing behavior and predict their spending patterns. It includes demographic details, annual income, website visits, previous purchases, membership types, preferred product categories, city tiers, and discount usage.

The dataset is used to understand the factors influencing customer spending and develop a machine learning regression model to predict the spending amount of individual customers.

### 2. Metadata

The dataset contains customer information with both categorical and numerical variables. Each variable is described below:

| Column | Description | Type |
| :--- | :--- | :--- |
| `Age` | Age of the customer | Integer |
| `Annual_Income` | Annual income of the customer | Float |
| `Website_Visits` | Number of times the customer visits the website | Integer |
| `Previous_Purchases` | Number of purchases previously made by the customer | Integer |
| `Membership_Type` | Membership category of the customer (e.g., Gold, Silver, Platinum) | Categorical |
| `Preferred_Category` | Product category preferred by the customer | Categorical |
| `City_Tier` | Tier classification of the customer's city | Categorical |
| `Discount_Used` | Indicates whether the customer used a discount | Categorical |
| `Spending` | Total spending amount of the customer (target variable) | Float |

### 3. Data Usage

The dataset can be used for multiple purposes:

**Exploratory Data Analysis (EDA):** Analyze customer demographics, income distributions, purchasing patterns, and relationships between customer attributes and spending behavior.

**Regression:** Develop machine learning regression models to predict customer spending based on demographic, financial, and behavioral characteristics.

**Customer Behavior Analysis:** Identify factors such as membership type, previous purchases, website visits, and discount usage that influence customer spending.

**Business Insights:** Help businesses understand customer spending patterns, identify valuable customer segments, and improve marketing strategies.

### 4. Machine Learning Application

A machine learning pipeline is developed to predict customer spending using the available customer attributes. The trained model is saved as `best_model_pipeline.pkl` and integrated into a Streamlit web application.

The application allows users to enter customer details and obtain an estimated spending amount through the trained machine learning model.

This project provides a practical approach to customer spending prediction and demonstrates how machine learning can support data-driven business decisions.