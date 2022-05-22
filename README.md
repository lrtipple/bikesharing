# bikesharing

## Purpose
For this analysis, you’ll use Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, you’ll create a set of visualizations to:

Show the length of time that bikes are checked out for all riders and genders
Show the number of bike trips for all riders and genders for each hour of each day of the week
Show the number of bike trips for each type of user and gender for each day of the week.
Finally, you’ll add these new visualizations to the two you created in this module for your final presentation and analysis to pitch to investors.

## Deliverables
Deliverable 1: Change Trip Duration to a Datetime Format
Deliverable 2: Create Visualizations for the Trip Analysis
Deliverable 3: Create a Story and Report for the Final Presentation


## Resources
NYC_CitiBike_Deliverable_1.csv , NYC_CitiBike_Challenge.IPYNB, jupyter notebook, Pandas, Python, Tableau

## Deliverable 1 - convert 'tripduration' column to datetime datatype
![datetime_code](https://user-images.githubusercontent.com/99093289/169702369-6a521fea-a4db-4ff7-9e40-8de47b980cd2.PNG)
![datatime_dtypes](https://user-images.githubusercontent.com/99093289/169702374-43f83463-0be4-4288-9317-5449e7cf4c9e.PNG)
![df_datetime](https://user-images.githubusercontent.com/99093289/169702392-6c0ee61a-3de2-453c-a01d-66fdb776d9ab.PNG)

## Deliverable 2 - Create Visualizations for the Trip Analysis
I created high level stat visualizations to drive home the need for analytical minds to see the actual data.
![counts](https://user-images.githubusercontent.com/99093289/169702461-38e31ade-b855-4424-87c0-3fc95aca3ac8.PNG)
###### This image shows the total number of customers by user and gender.

![locationcounts](https://user-images.githubusercontent.com/99093289/169702502-0b24064f-1056-48a0-b6c5-54ff11ca5d76.PNG)
###### This image shows the total number of starting and ending locations on the maps of the locations.

## Deliverable 3 - Create a Story and Report for the Final Presentation
![storycaptions](https://user-images.githubusercontent.com/99093289/169702920-0f282fff-27b5-4f03-9036-1178bd835304.PNG)
My NYC Citibike Story consists of 14 worksheets and 5 dashboards. 
The story is compiled of 6 pages.

### Page 1 - Starting and Ending location points:
![nycMap_db](https://user-images.githubusercontent.com/99093289/169703679-c080335c-463d-48f6-bfd9-dff8a64c9c98.PNG)
There are 794 starting points and 807 ending points. The majority of the busiest locations are in the heart of New York City. I added a map with a hyperlink that opens a new webpage of the NYC area so the user can see what is around the area.

### Page 2 - Trips by User:
![tripsbyuser_page](https://user-images.githubusercontent.com/99093289/169703746-798a9aa3-0279-4705-bbd5-7160f46e52cd.PNG)
Subscribers make up 81% of the customer base for ride-sharing in NYC. This means that while NYC is a touristy area, most riders are not short-term customers. 65% of riders are male. The most rides by weekday, in descending order, occur on Thursday, Friday, Tuesday, Monday, Saturday, Wednesday, and then Sunday.   

### Page 3 - Checkout Times:
![checkout times page](https://user-images.githubusercontent.com/99093289/169704444-a1498ce9-4e46-49fb-a09f-e325f79775b5.PNG)
The Checkout Times page shows two charts, one that shows the times for all users, and then one that shows the checkout times by gender.  I think this helps show detail into the gender while maintaining the functionality of being able to filter the hours for each metric. I prefer the view of the hour instead of minute break down, so I am including those images below. These show that the most bikes are checked out in the 5am hour.
![checkouttime_user](https://user-images.githubusercontent.com/99093289/169704547-c07b5621-b6f3-4003-bcba-6695d97f1f37.PNG)
![checkouttime_gender](https://user-images.githubusercontent.com/99093289/169704553-bf136bf4-c7b0-40ac-bbe1-2cc5a57a6dc6.PNG)


