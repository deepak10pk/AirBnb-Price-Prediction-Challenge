# AirBnb-Price-Prediction-Challenge


#Introduction and Motivation
*Airbnb is a marketplace for short term rentals, allowing you to list part or all your living space for others to rent. The company itself has grown rapidly from its founding in 2008 to a 30-billion-dollar valuation in 2016 and is currently worth more than any hotel chain in the world. One challenge that Airbnb hosts face is determining the optimal nightly rent price. In many areas, renters are presented with a good selection of listings and can filter on criteria like price, number of bedrooms, room type, and more. Since Airbnb is a marketplace, the amount a host can charge on a nightly basis is closely linked to the dynamics of the marketplace.
If the host charges above the market price, then renters will select other affordable alternatives. If the nightly rent price is set too low, the hosts will miss out on potential revenue. So, we use machine learning models to predict the optimal prices that the hosts can set for their properties. This is done by comparing the property with other listings on a variety of parameters like location, property size and other demographics. Also, based on the listing specifications and prices, the hosts would like to know what review rating they can expect or weigh how their listing compares to other similar ones and if they have a price premium with respect to other similar listings or are losing out on rating because of their pricing.

#Dataset Description
* The main dataset for the listing price and the rating prediction of the host property is obtained from Kaggle. The features describing the properties of a listing in the dataset include number of bathrooms & bedrooms, number of reviews, review score, neighborhood, GPS coordinates, description of the listing etc. Table 4 shows a list of columns that belong to the two groups, which can be found in the appendix.
* The dataset has a mix of Continuous, categorical, Nominal, ordinal and Boolean features. log_price, number of reviews, review score rating are continuous variables; Property_type, Room_type, Amenities, Description, Bed_type, Name of the rental, Neighborhood are all categorical variables; Accommodates, Bathrooms, Bedrooms fall under the group of Nominal variables; ID is an Ordinal variable; while the Cleaning fee, Host_has_profile_pic, Host_identity_verified, Instant bookable are all Boolean category variables, while the remaining are either the Time (first review, host since) or geographical variables (latitude and longitude). 

*  Given a dataset with 28 variables such as  number of bedrooms and a log-price indicator (greater than 0) for each observation in the training data, the objective is to suggest the log-price of a particular listing using the 28 features provided for the test observations.
* There are 49999 observations and 29 variables in the training dataset.
*  There are 24111 observations and 28 features provided in the test dataset.
*  Variable named ‘log_price’ is the dependent/Response variable


# Modeling Approaches

*  Linear and Ridge Regression model
* Random Forest
* XgBoost
* Neural Network

# Eavluation Metrics
 ❑ RMSE

