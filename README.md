# PyBer_Analysis

# Overview
This project is to create line charts with Matplotlib using both the MATLAB method and the object-oriented interface method. A summary DataFrame of the ride-sharing data by city type was prepared to present the total number of riders, drivers and total fares as well as the average fare per ride or driver. The analysis has also prepared some visualizations including plotting data from the DataFrame using Pandas and reshaping data to produce a multiple-line graph showing the total fares for each week by city type.

# Results
There are 125, 625 and 1,625 rides in total in rural, suburban and urban cities, respectively, which was calculated via groupby() function. Similarly, the total driver, total fares and average fares per ride and driver were also processed in the same way. The results are listed as in the table below. The total fare of urban cities is $39,854.38, much higher than that in suburban and urban cities, $19,356.33 and $4,327.93, respectively. In the same trend, the number of rides and drivers in urban cities is significantly higher than that in rural and suburban cities. Meanwhile, the average fare per ride and per driver is $24.53 and $16.57 in urban cities, which is significantly higher than that in suburban, $30.97 and $39.50, and rural cities, $34.62 and $55.49, respectively.
![deliver1_df_table](https://github.com/hankai26/PyBer_Analysis/blob/main/Resources/deliver1_df_table.png)

The total fares for each week in rural, suburban and urban cities have been summarized and plotted in the figure below. 
![sum_weekly_fares](https://github.com/hankai26/PyBer_Analysis/blob/main/Resources/sum_weekly_fares.png)

The weekly fare in urban cities is in the range of $1,700 to $2,500, which is approximately double of the fare in suburban cities, and three times higher than that in rural cities.
![line_chart_weekly](https://github.com/hankai26/PyBer_Analysis/blob/main/Resources/line_chart_weekly.png)


# Summary
The total numbers of drivers and rides in rural cities are significantly lower than that in urban cities and suburban cities. That led to a much higher average fare per driver and per ride in rural cities, compared to that in suburban and urban cities. By reviewing the driver data and fare calculation, we could derive the factor that both the drivers and ride-sharing data are adequate in urban cities. While we may need to focus more on the rural and suburban areas. Considering the significant high average fares per driver, it could be a good idea to develop the ride-sharing market and to potentially increase the driver numbers. Based on the ride data, the analysis further indicates that the revenue and consumption are much higher in urban cities than that in rural and suburban cities. 
