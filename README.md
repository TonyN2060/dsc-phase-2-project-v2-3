# dsc-phase-2-project-v2-3
BUSINESS OVERVIEW.



This project aims to provide valuable insights for a real estate agency operating in King County, Washington, USA. Specifically, the agency seeks to provide accurate advice to homeowners on how home renovations can potentially increase the estimated value of their properties and homes, and by how much. This information will help the agency guide their clients towards making informed decisions on home renovations, which can maximize their return on investment when selling their properties.


Introduction
The goal of this project is to conduct extensive research on the real estate market in King County and determine the optimal price range for houses in different neighborhoods on behalf of a real estate agency.
To achieve this objective, we will employ multiple linear regression modelling to analyze house sales data in the King County area. By using statistical techniques, we aim to identify key factors that impact property sales in the region and provide valuable insights to guide our recommendations.
Additionally, we will explore the potential of remodeling specific areas of a property to increase its value and make it more attractive to potential buyers. This approach can help homeowners to add functionality and beauty to their property while simultaneously boosting its resale value.


Problem statement


The problem at hand is to provide homeowners with accurate advice on how specific home renovations can impact the estimated value of their properties and homes, and the amount by which it can increase. This information is crucial for the real estate agency to guide their clients towards making informed decisions on home renovations, which, in turn, can help homeowners to maximize their return on investment when selling their properties. Therefore, the primary objective of this project is to analyze the impact of home renovations on the estimated value of properties and provide recommendations that can help the real estate agency and their clients to make sound investment decisions.

Data Understanding
The King County House Sales dataset, available in "kc_house_data.csv," is the primary data source for this project. However, one of the main challenges we may encounter is the ambiguity or incompleteness of the column names in the dataset. Nonetheless, with thorough research and careful judgement, we can extract the necessary insights to make informed decisions about which variables to use in our analysis. 

Another challenge we face is the numeric analysis of categorical variables – which is solved by converting them to numeric in a manner that its initial meaning is retained.

The dataset contains information on house sales in King County, including the price, design, square footage, location, and more.

We will also explore the general areas in which renovations are typically undertaken in properties to identify the potential impact on the estimated value of a property.


Objectives
· To determine the relation between the price and the other parameters
· To define a clear stakeholder and business problem that relates to the King County House Sales dataset, and to use this problem to guide the analysis and modelling process.
· To build and evaluate multiple linear regression models using various combinations of the available features in the dataset, with the aim of identifying the most relevant and impactful features for predicting house sale prices.
· To use appropriate statistical techniques to refine and optimize the regression models, and to clearly explain the rationale behind each technique used
· To demonstrate an iterative approach to modelling, documenting each stage of the process and providing justification for each model modification.
· To provide a final documentation that includes a detailed analysis of the chosen model, including relevant metrics describing overall model performance and the coefficients of the most impactful features, and a clear explanation of how the model adds value to the stakeholder and the appropriate recommendations.


  Findings/Results

1.Our baseline model is statistically significant, shown by P value of 0. The model explains 49% of the variance in price. zero square foot of living has a reduction in price by about $44,000.
For a unit increase in square foot of living there is a $280,000 increase in price.
2.The multiple linear regression model built has an R-squared value of 0.759, which indicates that the model can explain 76% of the variance of the market house sale prices which is a good sign that the model is effective in predicting the prices
The multiple linear regression model is observed to have a greater value of R squared, indicating it is a better model than the simple linear regression one.
It is also an indicator that the categorical variables have a significant effect on the housing price-we were able to include the categorical variables in the analysis by changing them to numeric
Overall, the model suggests that the number of bedrooms, bathrooms, square footage of living space, year built, latitude, view rating, condition and grade are important predictors of housing prices.

Recommendations
Focus on property condition and grade.Emphasize the significance of property condition and grade in determining house prices. Encourage renovations to improve the overall condition and raise the property’s grade as this has a great impact on the value of a house.

Highlight the significant impact of square footage of living space on house prices and use this information to justify higher listing prices for properties with more extensive square footage.

Increase the number of bedrooms and bathrooms during renovation due to the highly positive correlation of both of the parameters with the value of the house.

 






Conclusion
The model suggests that several variables significantly influence house prices, these include number of bedrooms, bathrooms, square footage of living space, year built, location, view rating, condition and grade.
Among the predictor variables, factors like the size of the property, condition and grade appear to have a strong influence on the house prices.


Next Steps.
While the model provides insights to specific variables, remember to consider broader market trends and factors influencing real estate prices. Keep track of market conditions, economic indicators and buyer preferences to provide clients with up to date and accurate advice.

Continuously refine and validate the model. Understand the limitations and assumptions of the model and its applicability to specific markets. Continuously update and refine the new model based on new data and incorporate local market knowledge to improve its accuracy and relevance.



