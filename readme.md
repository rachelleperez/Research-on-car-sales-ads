# Research on car sales ads

### Background

This project is part of the Data Scientist training program from Practicum by Yandex. More info in link below:

https://practicum.yandex.com/data-scientist 

### Project Setup

You're an analyst at Crankshaft List. Hundreds of free advertisements for vehicles are published on your site every day. You need to study data collected over the last few years and determine which factors influence the price of a vehicle.

Skills Used: Exploratory Data Analysis

### Data Description

The dataset contains the following fields:
* price
* model_year
* model
* condition
* cylinders
* fuel — gas, diesel, etc.
* odometer — the vehicle's mileage when the ad was published
* transmission
* paint_color
* is_4wd — whether the vehicle has 4-wheel drive (Boolean type)
* date_posted — the date the ad was published
* days_listed — from publication to removal


### Conclusion

The main objective of this project was to discover what factors affect a vehicle's price. During the process we uncovered additional insights related to activity of the site and inventory. Below are the findings: 

**Activity on the Site**
- Activity is consistent, with the number of ads and the days a car is listed remaining around the same month after month. 

**Inventory**
- Although we have 13 different types of vehicles in our site. 84% of the inventory is of 4 types (SUV, sedan, truck, and pickup). Is this what the business intended? Do we want to focus on these or diversify our inventory?
- Buses are a particular weak area for us making up less than 1% of our inventory, with a high price, and listed the longsest. 
- Convertible seem to be an emerging type for us thanks to being listed for the shortest amount of type (assumingly a sign of demand) while making less than 1% of our inventory. 

**Price**
- After a closer look at our two most popular vehicle types, we have found factors that impact price:
- Vehicle Age: Newer vehicles are more expensive than older ones
- Condition - As condition improves so does price. 
- Transmission Type: Depending on the vehicle type we can see that certain transmission types are more expensive. For example, SUVs with a manual transmission are more expensive thatn automatic (perhaps related to supply). 


*Of notice is that the average miles per year did not have the effect of price that was expected and paint color did not affect price either.*

### Technologies Used

* Python (Pandas, Numpy, Seaborn)

