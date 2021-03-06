# PyBer_Analysis
## Background

An exploratory analysis of rideshare data using Pandas libraries, and Matplotlib to visualize data.

## Overview of the Analysis

The purpose of this project is to perform an exploratory analysis of some very large csv files and create several types of visualization to construct a compelling story about the data. The objective is to produce an analysis and visualizations that will help our client to improve access to ride-sharing services and determine affordability for underserved neighborhoods.

### Customer's guidance:
- Using your Python skills and knowledge of Pandas, you’ll create a summary DataFrame of the ride-sharing data by city type. 
- Then, using Pandas and Matplotlib, you’ll create a multiple-line graph that shows the total weekly fares for each city type.
- Create a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

 
 <br/>

## Analysis
### Exploratory analysis
As part of our exploratory analysis, we created some basic charts to visualize and obtain a better understanding of our dataset. First, we created a pie chart Fig 1.1. By analyzing this image we can see that there were 3 city types: **Urban, Suburban, Rural**

<br/>

![pie_city_type](./Images/pie_city_type.png)

<sub>Figure 1.1 Pie chart by city type.

<br/>

Then we used .describe() method to obtain some descriptive statistics about the fares distribution. (Figure 1.2)

<br/>

![describe_ride_data_df](./Images/describe_ride_data_df.png)

<sub> Figure 1.3 Statistical data

Additionally, we created a histogram (Figure 1.2) of total fares distribution to better understand the fares per type and used 

![hist_fares](./Images/hist_fare.png)

<sub>Figure 1.2 Histogram fares.

<br/>

The above used charts and methods are an easy way of using Pandas and Matplotlib libraries to have a quick overview of the dataset in a short period of time. Knowing what is in our dataset will allow us to clean it, expand our exploratory analysis if needed, extract data, and produce a more robust analysis at the end.

### Results

<br/>

After our analysis, we were able to created a PyBer summary DataFrame that summarized: the total number of rides for each city type, the total number of drivers for each city type, the sum of the fares for each city type is retrieved, the average fare per ride for each city type is calculated, the average fare per driver for each city type is calculated as shown in (Figure 1.4).

![pyber_summary](./Images/pyber_ride_summary_df.png)

<sub>Figure 1.4 Total Rides summary table

and with this data we created a pie chart of the total rides per type. (Figure 1.5)

<br/>

![pie_total_rides](./Images/pie_total_rides.png)

<sub> Fiure 1.5 Pie chart -Total rides per type

<br/>

#### Observations of Summary Table
- Urban cities have a higher total rate of rides per driver than suburban and rural areas. Total rides in the Urban areas represent **68.4%** of all the rides vs **26.3%** in Suburban and **5.3%** in Rural areas.
- There are many more drivers in Urban areas with a total of **2,405** vs **490** in Suburban and **78** in Rural areas, **96.76%** more drivers in Urban areas.
- Total fares for urban areas was **$39,854.38** vs **$4,327.93** for rural areas. This is **89.14%** more than Rural areas.
- Average fares per ride are more expensive in Rural areas with **$34.62** per ride vs **$24.53**  in Urban areas, **29.15%** more expensive in Rural areas.
- Average fare per driver is more expensive in Rural areas with **$55.49** vs **$39.50** in Suburban areas and **$16.50** in Urban areas,  **70.26%** more expensive in Rural areas.


<br/>


Finally, we created a visualization of the "Total Fare by City Type" using a multiple-line plot as shown in Figure 1.6.

<br/>

![multiple-line _chart](./analysis/PyBer_fare_summary.png)
<sub>Figure 1.6 Multiline chart

<br/>


## Summary

As we can observe in our analysis, the Urban market is more profitable for the company as the market is bigger in Urban areas. This can be seen in Figure 1.5, the Urban market represents 68.4% of the total rides. There are also many more drivers in Urban cities vs suburban and rural areas, this allows them to offer better rates and be more profitable per volume. 
If we look at Fig. 1.5, we notice that there is a disparity in the market among the city types. In an effort to reduce the disparity in the market the client could do the following:

- Improve marketing in rural areas to increase the demand for the service.
- Increase the number of drivers in rural and suburban areas, to increase competitiveness.
- Offer better average fare price per driver - making the "fare" more appealing to customers might translate into higher demand for the service in Rural areas.

These changes will allow the client to offer more competitive and appealing prices in suburban and rural areas; increasing the demand for the service and improving the accessibility in those areas resulting in a better distributed market.

<br/>

## References

[Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

[Matplotlib gallery](https://matplotlib.org/stable/gallery/index.html)
