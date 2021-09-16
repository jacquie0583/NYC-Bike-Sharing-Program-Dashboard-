# Bikesharing
##  Project Overview
<p align="center">
 <img width="400" height="300" src="https://github.com/jacquie0583/bikesharing/blob/main/image%2012.jpg">
</p
  
  
   The project presents an analysis of New York Citi Bike data, using data visualization tools to present to the investors for exploration of the viability of a bike-sharing         business in Des Moines.  For this analysis, I utilized Pandas to change the "tripduration" column from an integer to a datetime datatype. Using the converted datatype to           create a set of visualizations to demonstrate the following:
 
   •	Illustrate the length of time that bikes are checked out for all riders and genders
 
   •	Illustrate the number of bike trips for all riders and genders for each hour of each day of the week
 
   •	Illustrate the number of bike trips for each type of user and gender for each day of the week.
 
   • Finally, you’ll add these new visualizations to the two you created in this module for your final presentation and analysis to pitch to investors.
 
<p align="center">
  <img width="400" height="300" src="https://github.com/jacquie0583/bikesharing/blob/main/image%209.png">
</p>
 
 
  
[NY City Bikeshare dashboard]( https://public.tableau.com/views/NewYorkCitiBankStory/Story1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)
  
##  Resources
   1.	Data Source: Citi Bike Data, 201908-citibike-tripdata.csv.zip
   2.	Software: Python 3.7.7, Anaconda Navigator 1.9.12, Conda 4.8.4, Jupyter Notebook 6.0.3, Tableau Public 2020.3.2, Visual Studio Code 1.50.0, CSV
   
  
##  Results  Deployed Tableau Analysis
###  New York Citi Bike data visualizations for August 2019
   1.	Change Trip Duration to a Datetime Format
      Using Python and Pandas functions, the "tripduration" column was converted from an integer to a datetime datatype to get the time in hours, minutes, and seconds                   (00:00:00). After the convertion of the "tripduration" column to a datetime dataytpe, the DataFrame was exported as a CSV file to use for the trip analysis.
  
<p align="center">
<img width="600" height="300" src="https://github.com/jacquie0583/bikesharing/blob/main/Image%201.png">
</p>


  2.	Length of time that bikes are checked out for all riders

<p align="center">
<img width="600" height="400" src="https://github.com/jacquie0583/bikesharing/blob/main/image%202.png.Length%20of%20time%20that%20bikes%20are%20checked%20out%20for%20all%20riders.png">

  3.	Create the Checkout Times for Users   
     •Bikes are checked out for ~ 4 to 6 hours.
 

</p>
<p align="center">
<img width="800" height="400" src="https://github.com/jacquie0583/bikesharing/blob/main/image%203.png">
</p>


   4.	Create the Checkout Times by Gender  
      •	Male users take approximately 3 times more rides than the female users.

<p align="center">
<img width="800" height="400" src="https://github.com/jacquie0583/bikesharing/blob/main/image%204.png">
</p>


5.	Trips by Weekday for Each Hour

<p align="center">
<img width="400" height="400" src="https://github.com/jacquie0583/bikesharing/blob/main/image%205.png">
</p>


6.	Trips by Gender (Weekday per Hour)

    •	Most weekday rides are around 7:00 AM to 9 AM and 5:00 PM to 7:00 PM.
    
    •	Weekend rides are highest from 10:00 AM to 7:00 PM.
    
    •	Those rides are mostly taken by male users.

<p align="center">
<img width="800" height="500" src="https://github.com/jacquie0583/bikesharing/blob/main/image%206.png">
</p>


7.	User Trips by Gender by Weekday 

<p align="center">
<img width="400" height="400" src="https://github.com/jacquie0583/bikesharing/blob/main/image%207.png">
</p>


8. Top Starting Locations

   •	There were over 2.3 million rides for the month of August 2019.

   •	81% of the users were subscribers. 65% of the users were confirmed males and 25% were confirmed females.

   •	There is a wide range of the age of the users. Younger users tend to use the service for longer rides.

   •	Top ride starting locations are in the most touristic and busy areas, as we see here in Manhattan.

<p align="center">
<img width="800" height="400" src="https://github.com/jacquie0583/bikesharing/blob/main/image%208.png.jpg">
</p>

   9.	 August Peak Hours
   
   •	Highest activity hours are from 5:00 PM to 7:00 PM and require the most resources mobilized.
      
   •	The activity from 2:00 AM to 5:00 AM is low so this would be the window for bike maintenance.


<p align="center">
<img width="800" height="400" src="https://github.com/jacquie0583/bikesharing/blob/main/image%2011.png">
</p>




10.	Bike Utilization

<p align="center">
<img width="400" height="400" src="https://github.com/jacquie0583/bikesharing/blob/main/image%2010.png">
</p>


##  Summary
   • The data shows high activity of the bike sharing service in New York during the month of August 2019.
    
   •   The far majority of the rides were in the very busy Manhattan Island, taken by male users during morning and evening rush hours. This implies that Citi Bike services are           used as an alternative to public transportation by commuting workers.

   Additional analysis would be beneficial by :
      
   • comparing data for different months to determine trends across the year,
    
   • including weather data to find the correlation between the weather and the rides.
