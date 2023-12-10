# Taxi Ride Data for Zuber's Launch in Chicago

This project is an individual undertaking, meaning that it is being carried out by a single person working independently, without collaboration or group involvement.

## Project Description 

The forthcoming ride-sharing enterprise poised for introduction in Chicago and the primary objective is to extract actionable insights from a comprehensive dataset encompassing details regarding taxi transportation within the urban landscape. This dataset encompasses several distinct tables, incorporating essential data concerning neighborhoods, taxi vehicles, trip particulars, and comprehensive weather records. The mission is to harness this data to inform strategic decisions and optimize Zuber's market entry and operational efficacy within the city of Chicago.

Explore taxi company performance and the top neighborhoods in terms of drop-offs, and taxi companies and number of rides. Create visualizations to help interpret and communicate the findings.

In the final step, there will be separate hypothesis test to determine whether the average ride duration from the Loop to O'Hare International Airport changes on rainy Saturdays.

-`/datasets/project_sql_result_01.csv` : It contains the following data:

-`company_name`: taxi company name

-`trips_amount`: the number of rides for each taxi company on November 15-16, 2017. 

-`/datasets/project_sql_result_04.csv` : It contains the following data:

-`dropoff_location_name` : Chicago neighborhoods where rides ended

-`average_trips`: the average number of rides that ended in each neighborhood in November 2017. 


-`/datasets/project_sql_result_07.csv` : the result of the last query. It contains data on rides from the Loop to O'Hare International Airport. The following are the table's field values:

-`start_ts` :pickup date and time

-`weather_conditions` : weather conditions at the moment the ride started

-`duration_seconds` :ride duration in seconds


##Test the hypothesis:

"The average duration of rides from the Loop to O'Hare International Airport changes on rainy Saturdays." 

Decide where to set the significance level (alpha) on your own.


## Result



