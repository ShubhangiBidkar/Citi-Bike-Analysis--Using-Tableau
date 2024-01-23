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

  ![image](https://github.com/ShubhangiBidkar/Citi-Bike-Analysis--Using-Tableau/assets/38162670/fb9fa8d9-f9ef-4e96-9e0c-86aea51f411f)


### Station Analysis

The dashboard presents a comprehensive analysis of trips in relation to stations.It gives us popular start and End Stations,total number of stations,total number of bikes and total trip duration.

  ![image](https://github.com/ShubhangiBidkar/Citi-Bike-Analysis--Using-Tableau/assets/38162670/81cf9588-c4fd-4ff2-8461-0af33a5e5dea)

### Geographical Analysis

The dashboard features two maps showcasing the geographical locations of the start and end stations.The size represents the the total numbers of bikes for that station and color is used to represnet the station name.

  ![image](https://github.com/ShubhangiBidkar/Citi-Bike-Analysis--Using-Tableau/assets/38162670/f53a587e-428a-4e4b-a877-f718165096e1)


### Bike Usage Analysis

Bike usage Analysis

The dashboard focuses on analysis of the usage of bikes on weekdays throught thw year.Also analyzes during which months the bikes are used the most and also which types of bikes are used the most.

  ![image](https://github.com/ShubhangiBidkar/Citi-Bike-Analysis--Using-Tableau/assets/38162670/0c48833b-60f8-4662-8363-bc0b098fa0d5)



### User and Rush hour Analysis

This section focuses to analyze on the type of users using the bike and also analyzes on which hours during the day are the bikes used the most.

  ![image](https://github.com/ShubhangiBidkar/Citi-Bike-Analysis--Using-Tableau/assets/38162670/e62eb793-21ef-4db7-acff-c787d964062b)



## Summary of Anlysis

- More bike rides were taken with classic bikes in comparison to the rest. Electric bikes might require periodic charging, and docked bikes might be limited by the total time of use available.

    ![image](https://github.com/ShubhangiBidkar/Citi-Bike-Analysis--Using-Tableau/assets/38162670/30c989b4-477b-4ef3-8c79-15f51e808247)


* It can be seen that bike usage increases mostly for all months on Wednesdays and Thrusdays. This may be attributed to the proximity of biking stations to one's office or home and the ease of using it. Perhaps more people prefer to get away from the city on weekends and hence relativly less bikes are used from Citibike's program.

    ![image](https://github.com/ShubhangiBidkar/Citi-Bike-Analysis--Using-Tableau/assets/38162670/130b976d-1b53-4871-b0cd-d802bf9bf5fb)


- The statistical analysis also showed the precent of increase in bike usage during summer where August and July are the months people prefer using bike.During the months of Winter (Deceember,Januray and February) the usage of bikes drops to almost half the usage in summers.
 
    ![image](https://github.com/ShubhangiBidkar/Citi-Bike-Analysis--Using-Tableau/assets/38162670/12776d40-0dc3-4cf0-948b-7bbf0c7f31ad)

* Statistical Anlysis of stations shows the total number of start and end stations,total bikes used and total trip duratin in hours.

   ![image](https://github.com/ShubhangiBidkar/Citi-Bike-Analysis--Using-Tableau/assets/38162670/2ac2c423-f133-464d-b599-ff71cba68150)


* Grove St path station is the most popular start and end station.And it has the most number of classic bikes and also members using the bike

    ![image](https://github.com/ShubhangiBidkar/Citi-Bike-Analysis--Using-Tableau/assets/38162670/7b2570d6-da55-4803-8a61-5bce3e998653)



* There are more people who are members of the Citi bike program then the casual riders throughout the year.

    ![image](https://github.com/ShubhangiBidkar/Citi-Bike-Analysis--Using-Tableau/assets/38162670/312bce95-da5a-4f9f-88d9-f42fd050ed0b)


* It is noteworthy that the peak utilization of citibikes in Jersey City occurs during the weekday, specifically during the hours of 7 a.m. to 8 a.m. in mornings and 5 p.m. to 7 p.m. in evenings, as a significant number of commuters utilize bicycles for their daily commute.
  Where as on weekends the peak hours are after 11 a.m. to 4 p.m.

    ![image](https://github.com/ShubhangiBidkar/Citi-Bike-Analysis--Using-Tableau/assets/38162670/4fb79f9b-931c-4fe5-a44d-fdfb51760c30)


