# car price prediction
A used-car price predictor created using Machine-Learning and Web Development.

Problem Statement:

The auto industry is changing rapidly and car prices are only going up. So to speak, new cars are getting costlier each year, making them a very high value purchase for the common man. And quite ironically, the average life span of a car is going down despite the steady rise in prices, which brings in good news for potential used car buyers! Thanks to manufacturers launching newer versions of their models sooner now as compared to a few years ago, more and more modern cars are now entering the used car market, which makes it easy for you to make a good buy without having to bust your wallet.
And as the market for used-cars is increasing, the number of sellers is also increasing. Keeping this in mind, I have created a web application for sellers, to know what will be the price of their car, in the market.

Dataset used:

For solving this problem, I have used the CarDekho dataset, which was avaliable on Kaggle. This is the link: https://www.kaggle.com/shindenikhil/car-dekho-data

Algorithms used:

After experimenting with a lot of Regression-based algorithms, Random Forest has worked out the best for me in terms of accuracy. If you want an in-depth explaination on random Forest and how do they work, feel free to checkout this article.

Features used:
Since this is a very basic used-car price predictor, I have only used a handful of features. Some of the features are:

Year: The total life-span of the car(currentYear - yearOfPurchasing)
Showroom Price: The price of the car when the seller first bought it.
Kilometers Driven: The total number of kilometers the car has driven.
Previous Owners: The number of owners the car has had.
Fuel Type: Specifies if the car runs on Petrol, Diesel or CNG.
Dealer/Individual: Specifies if the seller is a dealer or an individual.
Transmission Type: Specifies whether the car is a manual one or automatic.

NOTE:
"Success is the project that's always under construction": Keeping this quote in mind, I'd like to add many features into this project in the future. So stay updated!

To run this on your machine:

Make sure you have Python3, Flask installed.
In you terminal, cd to the folder you got this project in, and type python run app.py
And voila!!

