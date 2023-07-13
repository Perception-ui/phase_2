# Feature Importance Analysis: Identifying Key Factors Affecting House Prices in King County

## Business Understanding
A real estate agency aims to enhance their advisory services by identifying and prioritizing the most influential features that significantly impact house prices. The goal is to provide personalized recommendations to clients and navigate the real estate market effectively.

## Data Understanding
The dataset, King County House Sales, contains various predictor variables that may influence house prices. Some of the key variables include:
- **bedrooms**: Number of bedrooms in a house.
- **bathrooms**: Number of bathrooms in a house.
- **sqft_living**: Square footage of the living space.
- **sqft_lot**: Size of the lot.
- **floors**: Number of floors in a house.
- **waterfront**: Whether the house is located on a waterfront.
- **view**: Quality of the view from the house.
- **condition**: Overall condition of the house.
- **grade**: Grade assigned to the house based on construction and design.
- **yr_built**: Year when the house was built.
- **yr_renovated**: Year of the most recent renovation.

## Experimental Design
1. Data Exploration and Preprocessing:
   - Explored the dataset to understand variables and their relationships.
   - Handled missing values, if any.
   - Dropped irrelevant or redundant columns.
   - Handled categorical variables, if needed.

2. Model Building and Evaluation:
   - Started with a basic linear regression model using 'sqft_living' as the predictor and 'price' as the target.
   - Iteratively refined the model by adding more relevant predictor variables and evaluating the model's performance.
   - Assessed the significance of feature coefficients and interpreted their implications.
   - Selected the final model based on its performance, interpretability, and alignment with the business problem.

3. Final Model Selection and Interpretation:
   - Final model included variables such as 'sqft_living', 'bedrooms', 'yr_built', 'renovated', 'condition', 'grade', and 'waterfront'.
   - Interpreted the coefficients, assessed statistical significance, and evaluated the model's goodness of fit.
   - Provided insights into the key factors influencing house prices and actionable recommendations for the real estate agency.

4. Visualizing Average Price Over Time:
   - Plotted the average price by year built to understand trends in house prices over time.
   - Identified any notable patterns or relationships between year built and average price.

Link to notebook: https://docs.google.com/presentation/d/1IM9OzdktjdRRV8AWDLt5qgPczElkO2MeE69hP6r-9q8/edit?usp=sharing