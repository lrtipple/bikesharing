# bikesharing

## Purpose
For this analysis, you’ll use Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, you’ll create a set of visualizations to:

Show the length of time that bikes are checked out for all riders and genders
Show the number of bike trips for all riders and genders for each hour of each day of the week
Show the number of bike trips for each type of user and gender for each day of the week.
Finally, you’ll add these new visualizations to the two you created in this module for your final presentation and analysis to pitch to investors.

## Deliverables
1. Deliverable 1: Change Trip Duration to a Datetime Format
2. Deliverable 2: Create Visualizations for the Trip Analysis
3. Deliverable 3: Create a Story and Report for the Final Presentation
    * Link to Story: ["NYC Citibikes-Tableau Story"](https://public.tableau.com/app/profile/lauren.tipple/viz/NYC_CitiBike_Challenge_16532275357730/Story1)

## Resources
NYC_CitiBike_Deliverable_1.csv , NYC_CitiBike_Challenge.IPYNB, jupyter notebook, Pandas, Python, Tableau


## Deliverable 1 - convert 'tripduration' column to datetime datatype
![datetime_code](https://user-images.githubusercontent.com/99093289/169702369-6a521fea-a4db-4ff7-9e40-8de47b980cd2.PNG)
![datatime_dtypes](https://user-images.githubusercontent.com/99093289/169702374-43f83463-0be4-4288-9317-5449e7cf4c9e.PNG)
![df_datetime](https://user-images.githubusercontent.com/99093289/169702392-6c0ee61a-3de2-453c-a01d-66fdb776d9ab.PNG)

## Deliverable 2 - Create Visualizations for the Trip Analysis (additional visulizations in story)
I created high level stat visualizations to drive home the need for analytical minds to see the actual data.
![counts](https://user-images.githubusercontent.com/99093289/169702461-38e31ade-b855-4424-87c0-3fc95aca3ac8.PNG)
###### This image shows the total number of customers by user and gender.

![locationcounts](https://user-images.githubusercontent.com/99093289/169702502-0b24064f-1056-48a0-b6c5-54ff11ca5d76.PNG)
###### This image shows the total number of starting and ending locations on the maps of the locations.

## Deliverable 3 - Create a Story and Report for the Final Presentation
![storycaptions](https://user-images.githubusercontent.com/99093289/169702920-0f282fff-27b5-4f03-9036-1178bd835304.PNG)
My NYC Citibike Story consists of 14 worksheets and 5 dashboards. 
The story is compiled of 6 pages. I have listed the 6 pages individually with the summary analysis for each image in the corresponding section. 
The data and analysis is only comprised of one month (August) in the year 2019. There is a possibility of increased ride sharing during the covid-19 pandemic and the need the need for people to participate in outdoor activities. I would recommend doing an analysis of at least the same month for 2020 and 2021, but ideally the analysis should include data for the full year as weather elements would impact the number of rides based on the season.

Overall, this analysis does show that ride sharing in a major city is a popular activity and many people who ride-share are part of a subsciption. 

In addition to the visualizations below, i would recommend a visulaization of miles per bike ID, as this would help identify the amount of miles a bike should have in correlation to the number of hours for when repairs are needed. Another helpful visualizaton would be to see the number of rides by age. This could help determine the size of bikes needed for ride sharing. 

### Page 1 - Starting and Ending location points:
There are 794 starting points and 807 ending points. The majority of the busiest locations are in the heart of New York City. I added a map with a hyperlink that opens a new webpage of the NYC area so the user can see what is around the area.
![nycMap_db](https://user-images.githubusercontent.com/99093289/169703679-c080335c-463d-48f6-bfd9-dff8a64c9c98.PNG)


### Page 2 - Trips by User:
Subscribers make up 81% of the customer base for ride-sharing in NYC. This means that while NYC is a touristy area, most riders are not short-term customers. 65% of riders are male. The most rides by weekday, in descending order, occur on Thursday, Friday, Tuesday, Monday, Saturday, Wednesday, and then Sunday.   

![tripsbyuser_page](https://user-images.githubusercontent.com/99093289/169703746-798a9aa3-0279-4705-bbd5-7160f46e52cd.PNG)


### Page 3 - Checkout Times:
The Checkout Times page shows two charts, one that shows the times for all users, and then one that shows the checkout times by gender.  I think this helps show detail into the gender while maintaining the functionality of being able to filter the hours for each metric. 
![checkout times page](https://user-images.githubusercontent.com/99093289/169704444-a1498ce9-4e46-49fb-a09f-e325f79775b5.PNG)

I prefer the view of the hour instead of minute break down, so I am including those images below. These show that the most bike trips are 5 hours long.
![checkouttime_user](https://user-images.githubusercontent.com/99093289/169704547-c07b5621-b6f3-4003-bcba-6695d97f1f37.PNG)
![checkouttime_gender](https://user-images.githubusercontent.com/99093289/169704553-bf136bf4-c7b0-40ac-bbe1-2cc5a57a6dc6.PNG)

### Page 4 - All trips by Weekday:
This page shows the breakout of trips by day of week and hour. Most rides are between the hours of 7am and 7pm. This would mean most bike repairs would need to be completed between the hours 8pm-5am.
![trips by hour](https://user-images.githubusercontent.com/99093289/169705327-de78af60-2507-4b3b-9ee1-358c85df7847.PNG)


### Page 5 - Trips by Weekday by Gender:
This page shows the breakout of trip times by Gender. It confirms that gender does not alter the popular times for rides.
![tripsbyGender](https://user-images.githubusercontent.com/99093289/169705193-8bb8a988-814a-47ac-970c-62ee33dfc20a.PNG)

### Page 6 - Bike ID Utilization:
This page shows the duration of rides per each bike ID and also the number of individual rides per bike id. This can give an idea of which bikes are in need of repair. 
![Utilization](https://user-images.githubusercontent.com/99093289/169705257-4f85d9d1-0323-49ca-9d35-f5732fe5b9db.PNG)

