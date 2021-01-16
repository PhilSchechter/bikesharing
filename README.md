# bikesharing

### Purpose of this Analysis
The Iowa Civic Cycling Commission (ICCC) is looking to raise capital to support a bike share program, and is looking at New York's CityBike implementation as a possible model.

The ICCC has commissioned us to take a look at the voluminous data produced by NYC citibike program, and see if we can tease out lessons that would be both
- useful to the ICCC in setting up the program and
- helpful in telling the story to potential backers.

### Some results
We have used Tableau to help provide some data visualizations; Tableau was chosed as an ideal tool as
- it is quick to implement relative to the data provided
- it can handle large volumes of data
- built in map features assisted in some of the visualizations

The Tableau worksheet is available at
[Tableau Workeet](https://public.tableau.com/profile/phillip.schechter#!/vizhome/Module14_Challenge_16106868148830/BikeStory?publish=yes)

A couple of major themes from the data:
- usage seems to be more driven by commuters than tourists, based on usage patterms by time
- usage seems tightly bound to office density

Going through  the slides in order:
- Ride Duration: this matches the target slide we were given at the outset of the project, but is not correct: it aims to show ride duration, but intereperets the raw data duration as minutes instead of seconds. We are including to show that we are aware of the initial work done, but will correct this later in the deck.
- Ride Duration/Gender: this has the same problem as the prior slide, but the relationships by gender are correct: male riders take longer rides (by time) than female riders, bu a considerable margin.
- Ridership by Hour/Day: this shows the heaviest ridership on weekdays around rush hour. There is a decent amount of ridership mid-day on weekends, so could have some tourists there or could be New Yorkers enjoying the city.
- Ridership by Hours/Day/Gender: Same as above, but see that ridership is consistently more male
- Ridership by Day/Gender/Usertype (subscriber vs. pay-per-use customer) We see that weekday usage is dominated by subscribers - seems reasonable to posit that subscribers are commuters from NY or nearby using bikes to get to work or school on a regular basis, and Customers are more likely to be tourist or occasional recreation users. Weekends still favor subscribers, but not by the same margin.
- Ride Origins: The intensity of the usage in dense areas, high in office buildings, reinforces the idea that these bikes are largely used for commuting.
- Ride Duration, Data Corrected: this is a correction of the first slide, showing that the most common rides are around 5 minutes, with very few over 0 minutes or so.

## Summary
A program in Des Moines would need to follow a different model than New York; with a lower population density, we should expect longer rides. We should still try and cluster bike availability around transit hubs, large parking garages, and major office complexes, but may want to encourage off-peak ridership - for example, work restaurants to offer discounts for people who come by bike, and have cheaper rentals on weekends and midday to encourage recreational use.

### Areas for further research
We have plotted trip origins and destinations; we could further chart individual trips; e.g. do trips from one origin tend to mostly go to a similar destination? Are there major differences in origins and destinations by time of day, which would necessitate moving bikes during the day? (e.g. restocking at transit stations in the morning, and office buildings in the evening)

We have taken an intital stab at this in the slide "Start Location w/Hour Filter" - choosing morning hours will show a different concentration of starting points than choosing afternoon hours.



