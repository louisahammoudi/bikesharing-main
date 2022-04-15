# Citibike
NYC Citibike with Tableau

## Purpose: 
1. Import data into Tableau.
2. Create and style worksheets, dashboards, and stories in Tableau.
3. Use Tableau worksheets to display data in a professional way.
4. Portray data accurately using Tableau dashboards.

## Overview of the statistical analysis:
Des Moines requested data for a business proposal.  August 2019 Citibike data from NYC was reviewed by looking at geographical data as well as data disaggregated by user types and genders to determine if it would be a good investment for Des Moines.  Other data points include usage durations, peak usage times, and the key target market. 

## Link to Tableau Story: 
[Tableau Story](https://public.tableau.com/profile/julie.pyle2236#!/vizhome/Mod_14_Challenge/Story1?publish=yes)

## Cleaning the Data:
Jupyter Notebook was used to change the trip duration data to a datetime field.
![Pic](https://github.com/Baylex/Citibike/blob/main/Challenge/images/before_transformation.PNG)

![Pic0](https://github.com/Baylex/Citibike/blob/main/Challenge/images/after_transformation.PNG)

## Results of the NYC Citibikes Analysis:
For NYC, there were some interesting geographical areas of interest.  Some trips were outside the main city center.  Other areas followed the along the river. Future analysis would need to include a geographical review.

### 1. Checkout Times for All Users
[Checkout Times for All Users](https://public.tableau.com/profile/julie.pyle2236#!/vizhome/Mod_14_Challenge/Users)
The Citibikes usage reaches a top of 3000 minutes per user.
![Pic1](https://github.com/Baylex/Citibike/blob/main/Challenge/images/0_User.PNG)

### 2. Checkout Times by Gender
[Checkout Times by Gender](https://public.tableau.com/profile/julie.pyle2236#!/vizhome/Mod_14_Challenge/Gender)
Males are significantly higher users than others. 
![Pic2](https://github.com/Baylex/Citibike/blob/main/Challenge/images/1_Gender.PNG)

### 3. Trips (Weekday per Hour)
[Trips (Weekday per Hour)](https://public.tableau.com/profile/julie.pyle2236#!/vizhome/Mod_14_Challenge/Trips)
6-10 am and 5-8 PM are peak riding hours during the weekday and 5 am to 10 pm on the weekends.
![Pic3](https://github.com/Baylex/Citibike/blob/main/Challenge/images/2_Trips.PNG)

### 4. Trips by Gender (Weekday per Hour)
[Trips by Gender (Weekday per Hour)](https://public.tableau.com/profile/julie.pyle2236#!/vizhome/Mod_14_Challenge/TripGender)
Males are high users during the peak hours. 
![Pic4](https://github.com/Baylex/Citibike/blob/main/Challenge/images/3_TripGender.PNG)

### 5. Trips by Gender and User Type (Weekday per Hour)
[Trips by Gender and User Type (Weekday per Hour)](https://public.tableau.com/profile/julie.pyle2236#!/vizhome/Mod_14_Challenge/UserType)
Males subscribers are the highest users followed by female subscribers. 
![Pic5](https://github.com/Baylex/Citibike/blob/main/Challenge/images/4_UserType.PNG)

### 6. Number of Rides per Hour
[Number of Rides per Hour](https://public.tableau.com/profile/julie.pyle2236#!/vizhome/Mod_14_Challenge/Rides)
Non-peak hours are 1-5 am.  
![Pic6](https://github.com/Baylex/Citibike/blob/main/Challenge/images/5_Rides.PNG)

### 7. Number of Rides with Bike ID
[Number of Rides with Bike ID](https://public.tableau.com/profile/julie.pyle2236#!/vizhome/Mod_14_Challenge/Repair)
The divergence line shows that there are high use on 1/3 of the bikes.
![Pic7](https://github.com/Baylex/Citibike/blob/main/Challenge/images/6_Repairs.PNG)

## Summary:

1. Bike Repairs for 1/3 of the Citibikes need to be done during non-peak hours around 1-5 am. 
2. Male subscribers are the highest users and follow the traditional high use times of travel to and from work.  
3. Target market should be males needing transportation to work and weekend activities and push for subscribing to the services. 

## Additional Analysis: 

For NYC, there were some interesting geographical areas of interest.  Some trips were outside the main city center.  Other areas followed the along the river. Future analysis would need to include a geographical review.

### 1. Ride Starting Locations by Gender
[Ride Starting Locations by Gender](https://public.tableau.com/profile/julie.pyle2236#!/vizhome/Mod_14_Challenge/Start)
Males are more likely to start a trip farther than the main city center of NYC than others. 
![Pic8](https://github.com/Baylex/Citibike/blob/main/Challenge/images/extra1.PNG)

### 2. Ride Ending Locations by Gender
[Ride Ending Locations by Gender](https://public.tableau.com/profile/julie.pyle2236#!/vizhome/Mod_14_Challenge/End)
Males are more likely end a trip across the river in the southwest area of NYC than others. 
![Pic9](https://github.com/Baylex/Citibike/blob/main/Challenge/images/extra2.PNG)

### 3. User Type Starting Location
[User Type Starting Location](https://public.tableau.com/profile/julie.pyle2236#!/vizhome/Mod_14_Challenge/UserTypeMap)
Subscribers are more likely to start trip farther than the main city center of NYC than others. 
![Pic10](https://github.com/Baylex/Citibike/blob/main/Challenge/images/extra3.PNG)
