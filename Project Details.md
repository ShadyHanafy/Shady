# Seattle Airbnb Bookings — Data Analysis
![This is an image](https://github.com/ShadyHanafy/Shady/blob/main/airbnb-giftcard.jpg)

This blog purpose is analysing Airbnb bookings in Seattle to understand more how bookings are done, I will use CRISP-DM to answer the following questions in this blog:

1. The most booked Seattle neighborhoods using listing descriptions
2. What factors affect the above behavior?
3. What factors affect the price of the neighborhood booking?
4. What might influence reviewer rating?
5. What are the busiest times of the year to visit Seattle? and its reflection on prices?

## **DATA**

In this project I used the datasets from Kaggle Seattle Airbnb Page https://www.kaggle.com/airbnb/seattle/data:

## **Data Understanding**

First, let us have a look at the listings dataset to understand more about bookings in seattle through Airbnb

## **Overview of listings dataset**

Sample view for the dataset content

![This is an image](https://github.com/ShadyHanafy/Shady/blob/main/data.png)

## **Observations about the dataset**

1. There are 3813 records in this dataset with around 92 attributes
2. There are 4 attributes with missing data more than 50 % of the records of the attribute

After data preparation and cleansing, now let's try to answer the above questions

## **Looking for Answers**
### **Q1: What are the most booked Seattle neighborhoods?**

![This is an image](https://github.com/ShadyHanafy/Shady/blob/main/bookedneighb.png)

Using the attribute of the "neighbourhood_group_cleansed" which groups the neighborhoods and by excluding the "other Neighborhoods" we can see that "Capitol Hill" , "Down Towm" and "Central Area" are the top 3 booked neighborhoods in the dataset


### **Q2: What factors affect the above behavior?**

![This is an image](https://github.com/ShadyHanafy/Shady/blob/main/prop_typ.png)
![This is an image](https://github.com/ShadyHanafy/Shady/blob/main/hosp.png)

If we explore the dataset more, we can see that the above top neighborhoods provide the highest option in term of Entire home/apt property. Added to that Central Area has advantage with the highest hospitality ratio


### **Q3: What factors affect the price of the neighborhood booking?**

![This is an image](https://github.com/ShadyHanafy/Shady/blob/main/price.png)
![This is an image](https://github.com/ShadyHanafy/Shady/blob/main/capc.png)
![This is an image](https://github.com/ShadyHanafy/Shady/blob/main/bed.png)
![This is an image](https://github.com/ShadyHanafy/Shady/blob/main/bath.png)

If we check the above list, we can see that "Magnolia", "Queen Ann",  "Down Town" and "West Seattle" are the top expensive neighborhoods. If we explore the data deeper we will find that "Magnolia", "Queen Ann" and "West Seattle" neighborhoods are among the most spacious properties in terms of property type, number of rooms, number of bedrooms and even the number of guests it can hold


### **Q4: What might influence review rating for a booking?**

![This is an image](https://github.com/ShadyHanafy/Shady/blob/main/rev.png)

Analysing the reviewers ratings, we can see that "Central Area", "Delridge" and "West Seattle" are the highest rated neighborhoods. If we search for the reason, we can find that for example "Central Area" and "Delridge" are among the highest super hospitality index, while for example "Central Area" and "West Seattle" are among the most spacious properties which explains why "Central Area" is the highest rated neighborhood


### **Q5:What are the busiest times of the year to visit Seattle? and its reflection on prices?**
![This is an image](https://github.com/ShadyHanafy/Shady/blob/main/busiest_time.png)
![This is an image](https://github.com/ShadyHanafy/Shady/blob/main/busiest_price.png)

Based on the above chart, we can see that July,August and June are the busiset month among the year in seattle and as a result we can see these 3 months are the most expensive along the year
