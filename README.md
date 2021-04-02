# ITCS-3160-Database

## Description

In this project, I took an existing database (credit to ...) and added an additional feature which is the rating system. For the Resturants and Drivers. By utilizing MySQL.

## Use Case
   The customer must have recived their order before reviewing. Customer is given the option to rate the resturant and/or driver. The customer selects the number of stars (min of 1 and max of 5) they want to give the driver and/or resturant. The customer also can optional add a comment. Customer can search for reviews for both the resturant and driver. The resturant and driver can view the reviews at any given time. The resturant is the only one allowed to give feedback on the reviews.
   ![project](https://user-images.githubusercontent.com/54326315/113447729-70ca9900-93c8-11eb-8fc6-69ac5c58b886.png)

   

## Businees Rules (only for rating system)
- Customer can rate after receiving order
- Customer can rate driver and/or restaurant (like in doordash)
- Driver,Restaurant, and Customers can view ratings (min, max and average ratings)
- Driver and Restaurant cannot delete ratings
- Each Rating will have an optional detail
- A minimum of 1 star and a maximum of 5 stars is allowed
