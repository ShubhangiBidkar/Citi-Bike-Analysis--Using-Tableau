# Citi Bike Analysis Using Tableau

In this project, envision yourself as the new lead analyst for the New York Citi Bike program. You are now responsible for overseeing the largest bike-sharing program in the United States. In your new role, you will be expected to generate regular reports for city officials looking to publicize and improve the city program.

Since 2013, the Citi Bike program has implemented a robust infrastructure for collecting data on the program's utilization. Each month, bike data is collected, organized, and made public on the Citi Bike Data webpage.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have questions about the program, so your first task on the job is to build a set of data reports to provide the answers.

## Deployment

Please find below the link to the Tableau dashboard, showcasing the results of the analysis:
https://public.tableau.com/app/profile/shubhangi.bidkar/viz/CitiBikeAnalysis_17057044436740/Story1?publish=yes

## Data Source

The data was collected from [Citi Bike Data](https://www.citibikenyc.com/system-data)

1.The initial stage of the project involved acquiring all the monthly CSV files, covering the period from January 2023 to December 20203 from the [Citi Bike Data](https://www.citibikenyc.com/system-data) webpage and organizing them in a designated folder named "data". The data used in this analysis specifically pertains to the Jersey City region.

2. Subsequently, I established a Jupyter Notebook file, named ["citibikeanalysis.ipynb"](https://github.com/ShubhangiBidkar/Citi-Bike-Analysis--Using-Tableau/blob/main/citibikeanalysis.ipynb), to systematically clean and combine all the monthly CSV files into a single CSV file, in preparation for importing into Tableau.

## Dashboards

From the Citi Bike data, a homepage and four corresponding dashboards were created to provide a comprehensive analysis and visualization of the data.

### Homepage

The homepage serves as an introduction to the project, providing a concise overview of its purpose and contents. It clearly summarizes the key insights and findings of each dashboard, allowing for quick and easy navigation.

![Alt text](image.png)

### Station Analysis

The dashboard presents a comprehensive analysis of trips in relation to stations.It gives us popular start and End Stations,total number of stations,total number of bikes and total trip duration.

![Alt text](image-3.png)

### Geographical Analysis

The dashboard features two maps showcasing the geographical locations of the start and end stations.The size represents the the total numbers of bikes for that station and color is used to represnet the station name.

![Alt text](image-1.png)

### Bike Usage Analysis

Bike usage Analysis

The dashboard focuses on analysis of the usage of bikes on weekdays throught thw year.Also analyzes during which months the bikes are used the most and also which types of bikes are used the most.

![Alt text](image-2.png)

### User and Rush hour Analysis

This section focuses to analyze on the type of users using the bike and also analyzes on which hours during the day are the bikes used the most.

![Alt text](image-5.png)

### Summary of Anlysis

- More bike rides were taken with classic bikes in comparison to the rest. Electric bikes might require periodic charging, and docked bikes might be limited by the total time of use available.

  ![Alt text](image-6.png)

* It can be seen that bike usage increases mostly for all months on Wednesdays and Thrusdays. This may be attributed to the proximity of biking stations to one's office or home and the ease of using it. Perhaps more people prefer to get away from the city on weekends and hence relativly less bikes are used from Citibike's program.

![Alt text](image-7.png)

- The statistical analysis also showed the precent of increase in bike usage during summer where August and July are the months people prefer using bike.During the months of Winter (Deceember,Januray and February) the usage of bikes drops to almost half the usage in summers.
  ![Alt text](image-8.png)

* Statistical Anlysis of stations shows the total number of start and end stations,total bikes used and total trip duratin in hours.

  ![Alt text](image-9.png)

* Grove St path station is the most popular start and end station.And it has the most number of classic bikes and also members using the bike
  ![Alt text](image-10.png)

* There are more people who are members of the Citi bike program then the casual riders throughout the year.

  ![Alt text](image-12.png)

* It is noteworthy that the peak utilization of citibikes in Jersey City occurs during the weekday, specifically during the hours of 7 a.m. to 8 a.m. in mornings and 5 p.m. to 7 p.m. in evenings, as a significant number of commuters utilize bicycles for their daily commute.
  Where as on weekends the peak hours are after 11 a.m. to 4 p.m.

  ![Alt text](image-13.png)
