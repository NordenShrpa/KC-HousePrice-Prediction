# King County, USA House Price Prediction

This project analyzes housing prices in **King County, USA**, with the aim of understanding the key factors influencing house prices and predicting house values using a **Linear Regression Model**. The study leverages exploratory data analysis, data cleaning techniques, and regression modeling to provide insights into the housing market.

---

## Abstract

The project focuses on identifying the key drivers of house prices, such as **square footage**, **number of bedrooms**, and **construction quality**. After cleaning the dataset and removing outliers, a **linear regression model** was developed that explains **64% of the variation in house prices**. While the model is effective, potential improvements are discussed, such as incorporating additional features and using more advanced predictive techniques.

---

## Dataset Overview

- **Source**: [Kaggle - House Sales in King County, USA](https://www.kaggle.com/datasets/harlfoxem/housesalesprediction/data)
- **Description**:  
  The dataset consists of **21,613 records** with **21 variables**, providing detailed information on houses sold in King County between May 2014 and May 2015.  
  **Key Features**:  
  - `price`: Sale price of the house.  
  - `bedrooms`: Number of bedrooms.  
  - `bathrooms`: Number of bathrooms.  
  - `sqft_living`: Square footage of the living space.  
  - `sqft_lot`: Square footage of the lot.  
  - `grade`: Quality of the house based on construction and design.  
  - `condition`: Condition of the house at the time of sale.  
  - `yr_built`: Year the house was built.  
  - `yr_renovated`: Year the house was last renovated.  
  - `lat` & `long`: Latitude and longitude, indicating the location of the house.  
  Non-contributing columns like `id` were removed during data preprocessing.

---

## Project Workflow

### 1. Data Cleaning
- Handled irrelevant data and missing values.  
- Removed outliers to avoid skewing analysis results.

### 2. Exploratory Data Analysis (EDA)
- Investigated relationships between features (e.g., square footage, grade, and price).  
- Visualized key patterns using histograms, scatter plots, and correlation matrices.

### 3. Linear Regression Modeling
- Built a **linear regression model** to predict house prices based on selected features.  
- Evaluated model performance using metrics like **R-squared** (0.64).

### 4. Insights and Recommendations
- Identified key predictors:  
  - Square footage (`sqft_living`)  
  - House quality (`grade`)  
- Discussed limitations and suggestions for future improvements, including advanced modeling techniques like decision trees or neural networks.

---

## Key Findings

- The **square footage of living space** and the **grade of construction** were the most influential factors in predicting house prices.  
- The linear regression model performed reasonably well, explaining **64% of the price variation** in the dataset.  
- Improvements such as adding more features (e.g., proximity to amenities) and using non-linear models could further enhance prediction accuracy.

---

## Technologies Used

- **Programming Language**: Python (with pandas, NumPy, sklearn, and Matplotlib/Seaborn for EDA and modeling).  
- **Tools and Libraries**:  
  - **scikit-learn**: For building and evaluating the regression model.  
  - **Matplotlib & Seaborn**: For data visualization.  
  - **pandas**: For data preprocessing and analysis.

---



