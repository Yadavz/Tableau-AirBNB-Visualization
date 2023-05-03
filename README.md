## Airbnb Data Analysis Dashboard using Tableau

This project analyzes Airbnb data to identify trends and insights that can help stakeholders make better business decisions. The data is collected from two sheets of an Excel file - a calendar sheet and a listing sheet containing around 3000 data for Airbnb rooms. The project is completed using Tableau, a powerful data visualization tool.

## Dataset

The dataset consists of two sheets in an Excel file. 

### Calendar Sheet
The first sheet is the calendar sheet, which contains the following columns:
- listing_id: The unique ID of the Airbnb room
- date: The date on which the room is available
- available: A binary column indicating whether the room is available on the given date or not
- price: The price of the room on the given date

### Listings Sheet
The second sheet is the listings sheet, which contains around 3000 rows of data for Airbnb rooms. Each row represents a unique Airbnb listing and contains the following columns:
- listing_id: The unique ID of the Airbnb room
- name: The name of the Airbnb listing
- host_id: The unique ID of the Airbnb host
- host_name: The name of the Airbnb host
- neighbourhood_group: The neighbourhood group in which the Airbnb room is located
- neighbourhood: The neighbourhood in which the Airbnb room is located
- latitude: The latitude of the Airbnb room
- longitude: The longitude of the Airbnb room
- room_type: The type of the Airbnb room (e.g., Entire home/apt, Private room, Shared room)
- price: The price of the Airbnb room
- minimum_nights: The minimum number of nights required to book the Airbnb room
- number_of_reviews: The number of reviews received by the Airbnb room
- last_review: The date on which the last review was received by the Airbnb room
- reviews_per_month: The average number of reviews received per month by the Airbnb room
- calculated_host_listings_count: The number of Airbnb rooms listed by the host
- availability_365: The number of days in a year for which the Airbnb room is available for booking

## Dashboard

The dashboard was created using Tableau and includes the following visualizations:

1. Bar Graph - Average price for different rooms having different number of rooms

This graph shows the average price of Airbnb rooms with different numbers of rooms. The x-axis represents the number of rooms, and the y-axis represents the average price.

2. Line Graph - Revenue generated month-wise in 2016

This graph shows the revenue generated by Airbnb rooms month-wise in 2016. The x-axis represents the month, and the y-axis represents the revenue.

3. Map - Region average price using different colors

This map shows the average price of Airbnb rooms in different regions. The regions are colored differently based on the average price.

4. Table - Distinct count of bedrooms presently listed

This table shows the distinct count of bedrooms presently listed on Airbnb.

5. Bar Graph - Average price on the basis of zipcode

This graph shows the average price of Airbnb rooms based on the zipcode. The x-axis represents the zipcode, and the y-axis represents the average price.

The dashboard provides a comprehensive overview of the Airbnb data, highlighting important trends and insights that can be used to make better business decisions.



## Conclusion

In conclusion, this project involved analyzing Airbnb data using Tableau to create a dashboard that highlights important trends and insights. The dashboard includes a range of visualizations that help stakeholders understand the data and make informed decisions. The project showcases the power of Tableau in visualizing complex data and presenting it in a user-friendly manner.

## Requirements

- Tableau Desktop or Tableau Reader version 2020.4 or later.
