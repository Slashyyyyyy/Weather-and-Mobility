# Weather-and-Mobility
This is the code to my Bachelors Thesis

The different parts of my analysis can be accessed via the different branches:  
First Branch: Train  
Second Branch: Weather  
Third Branch: Train_Weather  
Fourth Branch: Maps  
Fifth Branch: Unused Code  
Sixth Branch: Data  

If all the data is unziped an kept in the same order, the code should run without any problems. 

Order of loading the code for understanding my analysis:
0. Train_Scrapper -> Not needed, as scrapped data is in Datafile
1. Train_preprocessing -> Make Data workable
2. Train_GTFS -> Enrich Data with GTFS
3. Train_Analysis -> First dive into the data
4. Weather_Preprocessing -> Concat different years
5. Weather_Analysis -> Getting a feeling of the weather data
6. Gemeinde-RR -> Creates Dictionary for Rain and Municipalities
7. Train_Weather_Preprocessing -> Connects Rain dictionary with train data
8. Train_Weather_Analysis -> Statistical Analysis of Correlation
9. Unused Code: Weather_warning (API for downloading weather warnings), ERA_Analysis (Early Analysis of the ERA dataset)
