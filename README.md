# tableau-challenge
# University of Oregon - Data Analytics Bootcamp

## The Challenge
In this challenge we were asked to use Citi Bike data to create a dashboard in Tableau Public.

## The Data
The most recent data (Jan-Mar 2024) didn't require much cleaning for the purpose of this challenge.
I did, however, use Jupyter to combine the csv files for Jersey City's Citi Bike data.
You could normalize the latitude and longitudes as the coordinates for any given station varied slightly.
However, Tableau was able to map the stations when using the average of latitude and longitude.
Trip duration used to be part of the data Citi Bike collected but the most recent data required you to calculate that yourself.
Which I did in Tableau.

##  The Analysis
One question that city officials might be asking themselves is, who uses Citi Bike more? Commuters or tourists?

During the first quarter of 2024, Citi Bike saw a total of 171,276 rides in Jersey City with a steady increase each month (Jan: 50,493 / Feb: 55,478 / Mar: 65,305).
I did not look at past data to see if there are more rides in the summer, but this would be one reason for the sharp increase between February and March.
The average time per ride over the quarter was just over 8 minutes. The average ride was about 10 minutes on a classic bike and 7 minutes on an ebike. 

As shown in the 'Stations' dashboard, maps of the start and end stations showed that the top 3 Citi Bike stations are Hoboken Terminal at River St & Hudson Pl, Grove St PATH,
and Hoboken Terminal at Hudson St & Hudson Pl.
The reason for this may be because these stations are practically on top of major Port Authority Trans-Hudson (PATH) terminals - Hoboken terminal, Grove St PATH and Newport PATH.
This makes sence since these are the main connections between Jersey City and NYC and are close to popular tourist attractions such as Grove Street, Hamilton Park, and Carlo's Bake Shop.

Next, I created a heatmap to see what the top times and days of the week were the most popular. I discovered that peak ride times are the hours of 8 to 9 AM and 5 to 7 PM Monday through Friday.
Although weekends also see fairly high use, this seems to drive the theory that Citi Bikes are heavily used by commuters.

I also coompared the number of rides by members and casual riders and found that there are more members using the Citi Bike program than casual riders (as shown in the 'Riders' dashboard).
This further supports the theory that Citi Bikes are used more by daily commuters than tourists.
