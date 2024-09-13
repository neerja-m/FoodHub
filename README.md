
# Food Hub

## Business Context 
A food aggregator company FoodHub offers access to multiple restaurants through a single smartphone app.

The app allows the restaurants to receive a direct online order from a customer. The app assigns a delivery person from the company to pick up the order after it is confirmed by the restaurant. The delivery person then uses the map to reach the restaurant and waits for the food package. Once the food package is handed over to the delivery person, he/she confirms the pick-up in the app and travels to the customer's location to deliver the food. The delivery person confirms the drop-off in the app after delivering the food package to the customer. The customer can rate the order in the app. The food aggregator earns money by collecting a fixed margin of the delivery order from the restaurants.

## Problem Statement
The food aggregator company has stored the data of the different orders made by the registered customers in their online portal. They want to analyze the data to get a fair idea about the demand of different restaurants which will help them in enhancing their customer experience. Perform the data analysis to find solutions that will help the company to improve the business. 

## Data Description
The detailed data dictionary is given below.

Data Dictionary

order_id: Unique ID of the order 
customer_id: ID of the customer who ordered the food
restaurant_name: Name of the restaurant
cuisine_type: Cuisine ordered by the customer
cost: Cost of the order
day_of_the_week: Indicates whether the order is placed on a weekday or weekend (The weekday is from Monday to Friday and the weekend is Saturday and Sunday)
rating: Rating given by the customer out of 5
food_preparation_time: Time (in minutes) taken by the restaurant to prepare the food. This is calculated by taking the difference between the timestamps of the restaurant's order confirmation and the delivery person's pick-up confirmation.
delivery_time: Time (in minutes) taken by the delivery person to deliver the food package. This is calculated by taking the difference between the timestamps of the delivery person's pick-up confirmation and drop-off information

## Solution Approach
Performed exploratory data analysis (univariate and multivariate) using Python NumPys and Pandas and plotted visualizations. Explored all the variables and provided observations on the distributions of them. Performed bivariate and multivariate analysis to explore different relationships between these variables. Used visualizations for the analysis and provided observations on the plots. Concluded with key insights and observations. 



## Samples from the report
![plotEx1](https://github.com/user-attachments/assets/ea05b163-c9ab-4eb6-a1ac-5faf0efb131e)

![plotEx2](https://github.com/user-attachments/assets/16cbf7fd-82b4-4478-aa3d-b124001c8ba5)

![plotEx3](https://github.com/user-attachments/assets/91e19092-6385-4aae-a7ee-4a4911169ec5)

![plotEx4](https://github.com/user-attachments/assets/19be6870-990c-4980-ac11-91c7f1916449)

![plotEx5](https://github.com/user-attachments/assets/568d72e0-732f-476e-970c-ea9d7c9f966d)

![plotEx6](https://github.com/user-attachments/assets/2f40d421-0d5a-4694-a3b0-d117dde595d9)

![plotEx7](https://github.com/user-attachments/assets/eb1f1de3-91eb-4cf4-9f43-4469f651d143)


