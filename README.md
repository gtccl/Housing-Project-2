## Project 2: Multiple Regression Model for Predicting King County House Prices
Author: Christine Li

*Business Problem*: <br>
The objective of this project is to create a regression model to predict home sale pricing in King County. 
Using this tool, homeowners can then make informed decisions about targeted renovations to increase the estimated value of their homes.


*Data:* <br>
This project will use the King County House Sales dataset.
This datset contains information on historic home sales and property features within the target real estate of King County. This dataset contains features such as square footage, number of bedrooms, bathrooms etc.  

*Methods:* <br>
1. Scrub the data
2. Explore and preprocess the data
3. Build multiple linear regression models using OLS statsmodels, with price as the dependent variable.
4. Interpret the results

*Results:* <br>
Square footage and grade are the best predictors of a house's price in King County. These features were included in the final multiple regression model:
* The model satisfied all multiple regression assumptions
* Positive coefficients
* p-values for each predictor variable were below 0.05
* The R^2 value of the model was 0.553

 
*Conclusion:* <br>
Homeowners should target their renovations into increasing the square footage and consider increasing number of bathrooms/bedrooms as well as and improving the overall quality of the house. 

*Limitations: <br>
Some of the variables had to be log-transformed to satisfy the multiple regression assumptions and therefore any new data would have to go through the same process. 
Looking at the original distribution of the variables, there was some outliers that were not removed from the model. In the future when applying new data, further consideration would need to be made on whether it is worth removing the outliers or not as outliers inherently can skew and influence the results.


# Deliverables:
See the full data analysis in the Housing Project 2.ipynb (Jupyter Notebook; https://github.com/gtccl/Housing-Project-2/blob/main/Housing%20Project%202.ipynb) 

See the non-technical presentation in this PDF (https://github.com/gtccl/Housing-Project-2/blob/main/Housing%20in%20King%20County.pdf)
