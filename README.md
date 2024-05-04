# What drives the price of a car?

## Overview
What drives the price of a used car?  The goal is to analyze a dataset with information on almost half a million used cars to understand what factors make a car more or less expensive. The analysis provides clear recommendations to a used car dealership as to what consumers value in a used car.

## Business Understanding:
The objective of the problem is to identify the key features that impact the prices of the used car. We would want to gain useful insights on how they negatively or positively drive the price of the car by looking for the top features that are positively and negatively correlated with the car price. The goal is to train and evaluate different regression models, fine tuning them using hyperparameters to idenitfy the relationship between the different variables in the data and predict the car price. 

We will need to use the test and validation datasets to determine the best regression models and identify the key features with accuracy.

By understanding accurately what features the customer value more, the used car dealer can gain more leverage and adjust the car prices to increase sales revenues and be more profitable.

Our results should demonstrate the potential of algorithms to improve the sales of used car dealership and help with their inventory management. In our analysis, we focus on the price as our primary measure of quality. Our goal is to maximize the sales of used cares selected in the process.

## Data:

In this application, you will explore a dataset from kaggle. The original dataset contained information on 3 million used cars. The provided dataset contains information on 426K cars to ensure speed of processing.  Your goal is to understand what factors make a car more or less expensive.  As a result of your analysis, you should provide clear recommendations to your client -- a used car dealership -- as to what consumers value in a used car. 

## Findings and Conclusion: 

To maximize the price at which a vehicle is sold, dealerships should focus in order of importance on the below:

1. Year of the vehicle: Generally, newer vehicles command higher prices in the used car market due to factors like updated features and technology, as well as potentially lower mileage.
2. Condition of the vehicle: Vehicles in excellent or good condition typically fetch higher prices compared to those in fair or poor condition.
3. Type of vehicle: Sedans are popular and often come with a higher price tag in the used car market, followed by pickups and wagons.
4. Odometer: Lower mileage typically translates to a higher price, with each mile increase leading to a decrease in value.
5. Drive type: Rear-wheel drive cars tend to have higher value compared to front-wheel drive cars.
6. Cylinders: Vehicles with larger engines, particularly with 8 or 6 cylinders, are preferred and can command higher prices.
7. Fuel type: Diesel cars generally fetch higher prices, but gas cars are also popular, though typically not as expensive as diesel.
8. Car title: A clean title is essential for maximizing the value of a used car.
9. Manufacturer: Toyota and Honda are popular choices in the used car market, while luxury cars may not sell as easily.


Considering these factors, if you're buying a used car, you'd ideally look for a newer vehicle in excellent condition, with low mileage, rear-wheel drive, a larger engine size (8 or 6 cylinders), and a clean title. Additionally, models from manufacturers like Toyota and Honda would likely be in demand. If selling, highlighting these features could help maximize the price you can ask for your used car.

## Future considerations and Next Steps:

Future improvements for this project would involve  hyperparameter tuning to further improve the results. 
Additionally we could perform some more feature engineering to the input dataset and verify if it enables reduction in the error. I would like to incorporate polynomial degrees and see how it performs relative to the other models.
A sizable amount of data was dropped since it proved difficult to impute missing values without the possibility of introducing bias. It would be good to gathermore data on these columns to determine if it affects the coefficients and results can be further finetuned.
