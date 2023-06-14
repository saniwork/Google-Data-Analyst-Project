# Google-Data-Analyst-Project
 Cyclistic bike-share analysis case study

## About Company 
Cyclistic is a bike-share program in Chicago with over 5,800 bicycles and 692 stations. They offer flexible pricing plans for casual riders and annual members. The company aims to convert casual riders into annual members to maximize profitability and drive growth. 

## Objective 
Understand the differences in the usage patterns of annual members and casual riders of Cyclistic bikes.

##  About Data 
The data has been made available by Motivate International Inc. under this [license](https://ride.divvybikes.com/data-license-agreement).
Data-privacy issues prohibit using riders’ personally identifiable information.
It's a collected by primary source so shows high integrity
It contains data from march 2022 to feb 2023 

## Data Cleaning and Manipulation 
To facilitate analysis, the large dataset containing monthly data for Cyclistic bike trips was processed using MySQL. The data was cleaned and transformed to ensure its accuracy and usefulness for analysis purposes. Personal customer information was removed from the dataset to prioritize data privacy and security.
The date and time data in the dataset were converted into a more standardized and organized format to enable comprehensive analysis. This involved extracting relevant information and creating additional columns for improved data segmentation. For instance, the "started_at" and "ended_at" columns were divided into distinct columns, such as "Season," "Start Month," and "Start Day," allowing for more granular analysis based on  factors.
Additionally, a "Ride_Length" column was added to the dataset using appropriate calculations. This new column provides valuable insights into the duration of each bike ride, which can be helpful in understanding usage patterns and trends.
Duplicates and Nulls were checked using mysql.
By employing these data cleaning and transformation techniques, the dataset was refined for further analysis.

## Analyzing the Data
The analysis of Cyclistic bike trip data revealed that casual riders are more likely to use bikes on weekends. Annual members, on the other hand, predominantly use bikes for commuting during rush hours, particularly at 8 am and 5 pm. Casual riders also tend to have longer ride durations and show a preference for electric bikes over classic ones. The summer season sees the highest number of transactions, while winter has the least. These insights can inform targeted marketing strategies to attract more casual riders and promote annual memberships.

## Top 3 recommendations 
### Extend the time limit for bike usage from 45 minutes to 2 hours for all days, and increase it to 4 hours specifically for weekdays. 

### Introduce enhanced discounts and benefits during the summer season, or create special membership plans tailored for summer usage. This could include discounted rates, bonus ride credits, or exclusive perks.

### Introduce a separate membership plan specifically for bike usage between 6 am and 6 pm, offering a reduced membership price compared to the standard rate.


