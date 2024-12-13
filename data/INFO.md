# Zomato Delivery Operations Analytics Dataset

Zomato is a food delivery company in India. Similar to DoorDash or Uber Eats, they employ local drivers with personal vehicles to pick up restaurant orders and deliver them to the customer. [Saurabh Badole](https://www.kaggle.com/saurabhbadole) has graciously published an extensive [dataset](https://www.kaggle.com/datasets/saurabhbadole/zomato-delivery-operations-analytics-dataset/data) on Kaggle, providing insight into several of these deliveries. **45,584 deliveries** to be exact!

With **19 features** (excluding the primary key), we can utilize geographic, time, and weather data, as well as driver, vehicle, and traffic data. We even get a `festival` feature to warn us of anomalous delivery circumstances.

Saurabh has already done a wonderful job describing the features, so I've copied them below:

* `ID`: Unique identifier for each delivery.
* `Delivery_person_ID`: Unique identifier for each delivery person.
* `Delivery_person_Age`: Age of the delivery person.
* `Delivery_person_Ratings`: Ratings assigned to the delivery person.
* `Restaurant_latitude`: Latitude of the restaurant.
* `Restaurant_longitude`: Longitude of the restaurant.
* `Delivery_location_latitude`: Latitude of the delivery location.
* `Delivery_location_longitude`: Longitude of the delivery location.
* `Order_Date`: Date of the order.
* `Time_Ordered`: Time the order was placed.
* `Time_Order_picked`: Time the order was picked up for delivery.
* `Weather_conditions`: Weather conditions at the time of delivery.
* `Road_traffic_density`: Density of road traffic during delivery.
* `Vehicle_condition`: Condition of the delivery vehicle.
* `Type_of_order`: Type of order (e.g., dine-in, takeaway, delivery).
* `Type_of_vehicle`: Type of vehicle used for delivery.
* `Multiple_deliveries`: Indicator of whether multiple deliveries were made in the same trip.
* `Festival`: Indicator of whether the delivery coincided with a festival.
* `City`: City where the delivery took place.
* `Time_taken` (min): Time taken for delivery in minutes.