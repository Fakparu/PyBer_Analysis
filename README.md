# PyBer_Analysis
PyBer Visualization Project
1.	Overview of the analysis:
o	The task was to work with Omar to identify differences in the total weekly fares for each city type. We used MATLAB approach and sometimes used Object-Oriented approaches for the project.

2.	Results:
o	The unique identifier for each ride, ‘ride_id’ makes it easier to get the overview of data such as the total number of rides for each city 'type' by grouping each city 'type' and counting the 'ride_id'.
total_rides = pyber_data_df.groupby('type')['ride_id'].count()
![image](https://user-images.githubusercontent.com/105121697/173293930-a0a0284b-0f08-44a1-8c92-402ee73425ee.png) 
Pyber Summary DataFrame

Based on the analysis of the information gathered, we found out that the Urban city type had more than 80% of the total drivers and had less than 70% of the total rides.
Urban City total fare was 50% more than the Suburban city type but then the average fare per driver for the Suburban city type was 138% more than the average fare per driver for the Urban city
Pyber Weekly Summary by City Type Table
![image](https://user-images.githubusercontent.com/105121697/173294111-0de94a8d-8d61-42d5-b3ea-353b275340ec.png)
![image](https://user-images.githubusercontent.com/105121697/173294154-85149502-fdcb-42bf-9e52-0b5ea376676b.png)
 
3.	Summary:
o	If there is an increase in fare for only Suburban city type by the end of April. It might help to have Rural and Urban drivers available to control the increase in the next year.
o	When comparing the ratio of total Urban drivers to the total Urban rides, it implies that competition is more in the Urban city type. If incentives are offered to Urban drivers to expand their range to cover the Suburban and Rural areas, it can reduce competition and increase per driver average fare.
o	A decrease in the average fare in the Rural city type may increase volume and also have minimal effect to the average fare per driver.
