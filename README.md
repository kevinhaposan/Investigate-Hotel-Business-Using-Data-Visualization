# **Investigate-Hotel-Business-Using-Data-Visualization**

It's crucial for a company to continuously analyze its business performance. This time around, we will delve deeper into the hospitality industry. Our focus is to understand our customers' behavior when booking hotels and its relation to the cancellation rate of hotel bookings. The insights we gather will be presented in the form of data visualization to make them easier to understand and more persuasive.

## **Data Preprocessing**
1. Importing dataset

2. Filling the null value<br>
The null columns in this dataset are children, city, agent, and company. The null value in the 'children' and 'city' columns will be filled with mode. The null values in the 'agent' and 'company' columns exceed 10% of the total data. The data-filling method used would render these columns not accurately representing the actual data; therefore, both columns will be dropped.

3. Changing the value<br>
The replacement of 'undefined' values in the 'food', 'market_segment', and 'distribution_channel' columns will be done by replacing these values with the mode since they are the most frequently chosen values by people.

4. Dropping the columns<br>
The 'agent' and 'company' columns will be deleted based on the previous reasons.

## **Monthly Hotel Booking Analysis Based on Hotel Type**
![image](https://github.com/kevinhaposan/Investigate-Hotel-Business-Using-Data-Visualization/assets/156397084/1236533f-e517-4808-b9bd-e25e159325c8)<br>
1. In June, July, November, and December, there is an increase in reservations at both types of hotels. This could be due to the holiday season occurring in those months, prompting many people to travel for vacation.
2. In March and September, there is a decrease because those times are not holiday seasons.
3. Overall, city hotels have higher reservations compared to resort hotels. This could be due to each customer's preference regarding their chosen vacation destination (within the city or at tourist spots like beaches) and their needs.
4. The location of city hotels is more easily accessible with various modes of transportation compared to resort hotels, making city hotels a more popular choice.
5. City hotels may offer more affordable prices through discounts and special packages to attract guests, especially for business travelers where companies often have budget policies for accommodation.
6. By understanding the consistent reservation patterns from year to year, hotels can plan their capacity and services during those periods effectively.


## **Analysis of Stay Duration on Hotel Bookings Cancellation Rates**
![image](https://github.com/kevinhaposan/Investigate-Hotel-Business-Using-Data-Visualization/assets/156397084/27e34ad1-dc08-4532-9170-bd4cc2ca4dae) <br>
1. Overall, it's apparent that the cancellation percentage tends to rise with an increase in the total number of nights stayed in both hotel types.
2. City Hotel exhibits higher cancellation percentages compared to Resort Hotel across most ranges of total nights stayed, suggesting that City Hotel experiences more reservation cancellations.
3. The cancellation percentage at resort hotels on total nights 10, 11, 13, and 14 tends to decrease. This can be further analyzed regarding the factors contributing to this decrease.

## **Impact Analysis of Lead Time on Hotel Bookings Cancellation Rate**
![image](https://github.com/kevinhaposan/Investigate-Hotel-Business-Using-Data-Visualization/assets/156397084/329de374-c743-4649-b42c-1bb83a10bec8) <br>
1. The cancellation percentage at both hotels increases with lead time. This may be due to tentative planning.
2. City Hotel exhibits higher cancellation percentages compared to Resort Hotel across most ranges of lead time, suggesting that City Hotel experiences more reservation cancellations.
3. There is a significant increase in cancellation percentage at Resort Hotel during lead time 390-419 and 450-479. This can be analyzed further regarding the factors contributing to this high increase in reservation cancellations.
4. To prevent customers from cancelling reservations far in advance, hotels can send promotions such as monthly or specific interval service offers.
