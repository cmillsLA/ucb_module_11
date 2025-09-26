# Module 11 - Practical Application 2

## Overview
In an effort to help used car dealerships optimize their inventory the task is to perform regression analysis to model the relationship between various features of used cars and their prices. I'll use the provided dataset to train a model that can predict a car's price based on its characteristics, such as year, manufacturer, model, mileage, and type. The goal is to identify which of these variables have the most significant impact on the vehicle price to help identify the key drivers of used car prices.

## Analysis
Before running predictions on the sample data, the data was cleaned to remove unusable values and to focus on passanger vehicles under 25 years old.  In addition, a max price of $60,000 was set to avoid luxury or exotic cars from manipulating the results.  This data could also be used to find specific models or features by manufacturer or in a specific price point to fine tune results.

After running predictions on models created from the sample used car data, I have come up with a list of features that yield the highest used car sale price.  Sports cars and trucks, specifically diesel trucks will get the highest price.  These are also some of the most expensive new cars and having additional data such as trade in value or original sale price to depreciation and margin could be factored in to the model would yield more accurate results.

Based on these findings one data model suggests sports cars: Chevy Corvette or Porsche and trucks: Dodge Ram series, Toyota Tacoma & Tundra as well as the Chevy Silverado had the highest values.  While the other model predicts Mercedes-Benz specifically the G series and SL to have the highest price point.

The full data analysis can be reviewed here: https://github.com/cmillsLA/ucb_module_11/blob/main/prompt.ipynb
