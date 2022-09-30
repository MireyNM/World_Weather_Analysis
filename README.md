# World_Weather_Analysis
Module 6 in CU BootCamp

## Project Overview 
PLANMYTRIP is a top travel technology company that specializes in internet-related services in the hotel and lodging industry. In this project we will collect and present data for customers via the search page, which they will then filter based on their preferred travel criteria in order to find their ideal hotel, anywhere in the world.

### Purpose 
The aim of this project is to identify potential travel destinations and nearby hotels. To help create a travel itinerary for the customers, based on their weather preferences. 


## Resources 
- Data Source: new_full_student_data.csv
- Software: Python 3.7.13, Conda 4.14.0, Jupyter Notebook, CitiPy
- APIs: Google Maps - Open Weather 

## Analysis of Data and Results

### Retrieve Weather Data 
To perform this task, we used a Jupyter Notebook and the CitiPy module to get the cities for more than 2000 random latitudes and longitudes. Then, we have saved the data in a .csv file.  <br/>
To check the full code, go to ```Weather_Database.ipynb ``` <br/>
 https://github.com/MireyNM/World_Weather_Analysis/blob/main/Weather_Database/Weather_Database.ipynb

### Create a customer Travel Destinations Map

After retrieving weather data and storing it in a csv file, we imported these data as Pandas DataFrame. Then we employed input statements to find customer weather preferences and we used those preferences to identify potential travel destinations and nearby hotels. Finally, we  showed those destinations on a marker layer map with pop-up markers showing hotel name, city, country, the weather description and the temperature. (See Fig.1)

<p align = "center">
<img width="499" alt="Outcomes_vs_Goals" src="https://user-images.githubusercontent.com/109363759/193340906-486a0a43-2804-429e-bff0-f3405b47d2fa.png">
</p>
<p align = "center">
Fig.1 - Potentiel travel destination based on customer weather preferences. 
</p>
 <br/>
 
To check the full code, go to: ```Vacation_Search.ipynb``` <br/>
https://github.com/MireyNM/World_Weather_Analysis/blob/main/Vacation_Search/Vacation_Search.ipynb

### Create a travel Itinerary Map
Using the Google Maps Directions API, we have created a travel route between four cities, chosen based on customer's weather preferences. (See Fig.2).

<p align = "center">
<img width="499" alt="Outcomes_vs_Goals" src="https://user-images.githubusercontent.com/109363759/193341177-6da7a2b5-4b74-4b31-a049-d609ef914147.png">
</p>
<p align = "center">
Fig.2 - Travel route between four cities chosen based on customer weather preferences. 
</p>

Finally, we have created a marker layer map with a pop-up marker for each city on the itinerary (See Fig.3)

<p align = "center">
<img width="499" alt="Outcomes_vs_Goals" src="https://user-images.githubusercontent.com/109363759/193341370-3ee40153-ec63-481d-8182-fda23b4b3dea.png">
</p>
<p align = "center">
Fig.3 - Pop-marker map showing weather informations for itinerary cities. 
</p>
To check the full code, go to: 
```Vacation_Itinerary.ipynb```  <br/>
https://github.com/MireyNM/World_Weather_Analysis/blob/main/Vacation_Itinerary/Vacation_Itinerary.ipynb

## Summary
The aim of this project was successful met. I believe we can narrow our potential hotels choice by adding more questions to the customers like if they prefer to have snow or rain. Or maybe we can ask if they have preferred continent. ![image](https://user-images.githubusercontent.com/109363759/193342462-c2a50150-7817-4b39-b8df-81574d622c48.png)
