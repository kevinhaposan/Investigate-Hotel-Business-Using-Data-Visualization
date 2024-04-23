# **Investigate-Hotel-Business-Using-Data-Visualization**

It's crucial for a company to continuously analyze its business performance. This time around, we will delve deeper into the hospitality industry. Our focus is to understand our customers' behavior when booking hotels and its relation to the cancellation rate of hotel bookings. The insights we gather will be presented in the form of data visualization to make them easier to understand and more persuasive.

## **Data Preprocessing**
1. Importing dataset

2. Filling the null value
The null columns in this dataset are children, city, agent, and company. The null value in the 'children' and 'city' columns will be filled with mode. The null values in the 'agent' and 'company' columns exceed 10% of the total data. The data-filling method used would render these columns not accurately representing the actual data; therefore, both columns will be dropped.

3. Changing the value
The replacement of 'undefined' values in the 'food', 'market_segment', and 'distribution_channel' columns will be done by replacing these values with the mode since they are the most frequently chosen values by people.

4. Dropping the columns
The 'agent' and 'company' columns will be deleted based on the previous reasons.

## **Monthly Hotel Booking Analysis Based on Hotel Type**
![image](https://github.com/kevinhaposan/Investigate-Hotel-Business-Using-Data-Visualization/assets/156397084/1236533f-e517-4808-b9bd-e25e159325c8)<br>
- In June, July, November, and December, there is an increase in reservations at both types of hotels. This could be due to the holiday season occurring in those months, prompting many people to travel for vacation.
- In March and September, there is a decrease because those times are not holiday seasons.
- Overall, city hotels have higher reservations compared to resort hotels. This could be due to each customer's preference regarding their chosen vacation destination (within the city or at tourist spots like beaches) and their needs.
- The location of city hotels is more easily accessible with various modes of transportation compared to resort hotels, making city hotels a more popular choice.
- City hotels may offer more affordable prices through discounts and special packages to attract guests, especially for business travelers where companies often have budget policies for accommodation.
- By understanding the consistent reservation patterns from year to year, hotels can plan their capacity and services during those periods effectively.


## ****

## ****
