# usedcarprice
In this application, I will explore a dataset from Kaggle about used car prices. My goal is to understand what factors make a car more or less expensive. As a result of analysis, I provide clear recommendations to a used car dealership as to what consumers value in a used car and inventory suggestions.

Here are some very high level extract of findings.  More details are found in the attached .docx file.

Summary of findings:
1.	I find the car price is a function of many things, including cylinder count, drive type, manufacturer, size, odometer, and age (current year – manufactured year).  I focus on these six features.
2.	I did data cleaning to remove NaN, wrong inputs, and apparent outliers (in price, odometer, and age)
3.	I used one hot encoding of cylinder, drive, and size, since the count is not too high.
4.	I split data sets and build multi-variate linear regression model to predict the car price.
5.	Overall prediction and correlation for all the data is poor, since there are too many car models and conditions.
6.	At the end I did a mini dataset with only used Toyota cars, and build a second order parabolic regression fit of price vs. odometer.

A list of business suggestions to the car dealer:
1.	Stock on 3 best volume cars – Ford, Chevy, and Toyota.
2.	Used car price drops monotonically over age – except for exotic cars.
3.	Second hand cars of four years command a higher price than “younger” used cars.
4.	Tesla cars have good price but the history of retail is not proven.
5.	Toyota is a better second hand car to have in inventory than Honda, Hyundai, and Volvo.  It has longer retail cycle and higher price.
