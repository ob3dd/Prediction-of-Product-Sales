![nrd-D6Tu_L3chLE-unsplash](https://github.com/ob3dd/Prediction-of-Product-Sales/assets/133266342/c527e7c2-784c-4508-b3c7-3639cbeb4d9d)
# Sales Prediction
## Predicting the sales of products and goods for food items sold at various stores
Obed Okoro
## Improving sales for retailers by helping them understand the properties of products and outlets that have a significant impact on increasing sales. Helping retailers understand the properties of products and outlets that are critical in increasing sales, enabling them to make informed decisions and implement effective strategies to drive business growth.
## Data Source: 
Big Mart Sales Prediction https://datahack.analyticsvidhya.com/contest/practice-problem-big-mart-sales-iii/
For this dataset, there are 8523 rows and 12 columns.

## Data Dictionary
## To prepare this data, the data was cleaned, and the following processes were performed:
## Exploratory Data Analysis
- During the exploratory data analysis, a boxplot and histogram was visualized for each numeric datatype column. 
- Also, a barplot was visualized for each categorical column. 
- This gave a good baseline for all of the numeric and categorical columns for univariate EDA.
![download](https://github.com/ob3dd/Prediction-of-Product-Sales/assets/133266342/66ceba7a-33b6-4c17-ad85-cef0c2b702ee)

  This histogram shows the highest number of sales were over 3,000
  
## Expanatory Data Analysis
- To visualize the data for explantory purposes, countplots were chosen.
- The countplots were chosen to show how many categories (good & products) were sold the most compared to others.
  ![download (2)](https://github.com/ob3dd/Prediction-of-Product-Sales/assets/133266342/81945752-a760-46e6-bf8f-92dc5fc4f13f)
  
  **The top five were the most bought goods by consumers(This shows what goods or products were boughts and the approximated amount):**

- Fruits and Vegetables: 1232
- Snack Foods: 1200
- Household: 900+
- Frozen Foods: A little below 900
- Dairy: 600+
  
  **The bottom five were the most bought goods by consumers(This shows what goods or products were boughts and the approximated amount):**

- Canned: 600+
- Baking Goods: 600+
- Health and Hygiene: 500
- Soft Drinks: Below 500
- Meat: Below 500

**NB: These results weren't tested and proven by a computer, they were predicted based on the look of the graph above.**

![download (3)](https://github.com/ob3dd/Prediction-of-Product-Sales/assets/133266342/2e1a5b7d-82f9-49e0-8583-796257da3767)

This grapgh shows the outlet with the most distribution of good was 'OUT027' due to it occuring the most time (935). 
(i.e: if this was walmart, our out027 would be a brach of walmart that just made the highest distribution of goods).

## Maching Learning Using the Following Models:
- Linear Regression Model
- Random Forest Regressor Model
- Tuned Random Forest Regressor Model

## Models Evaluated & Results
**Linear Regression Model (Testing Set):**

- MAE = 1,003.675
- MSE = 1,845,588.354
- RMSE = 1,358.524
- R^2 = 0.331

**Random Forest Regressor Model (Testing Set):**

- MAE = 1,044.834
- MSE = 2,022,824.635
- RMSE = 1,422.260
- R^2 = 0.267

**Tuned Random Forest Regressor Model (Testing Set):**

- MAE = 972.625
- MSE = 1,787,474.378
- RMSE = 1,336.965
- R^2 = 0.352

## Summary:

- The Final Model Chosen was a Random Forest Regressor Model with the params tuned to 10.

- For the testing set on the model 35.2% of the variance in y was explained by x.

- The Mean Absolute Error was off by about $972.625.

- The Mean Squared Error was $1,787,474.378.

- The Root Mean Squared Error had a calculation of $1,336.965

*Using this model to make predictions on products sold by outlets would not be a very reliable. Considering the previous regression metrics from how the model performed, there is a disparity between the R^2 score which uses 35.2% of variance and also the Root Mean Squared Error that cannot be ignored.*

## Recommendations
- Model Performance

    -Overall, ,I would recommend most outlet stores sell goods that are moving fast, like our fruits and vegetables, our snacks, household goods, frozen foods and dairy.

## Limitations & Next Steps
- From this insights retailers and producers can know which of their goods sell best and the ones that sell less like I listed above. This could boost the outlet sales over 3000 like we saw in the graph above. In order for this to work it'll be needed for these outlet stores to sell more of the five goods listed above.
  
## For Further Information
For any additional questions, please contact:

Obed Okoro

obedokoroobi@gmail.com
