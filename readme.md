# FordGoBy Dataset
## by Hiten Naran


## Dataset

> The FordGoBy dataset was one of the options provided by Udacity. The dataset was spread across multiple CSVs with a cumulative total of rows exceeding 6M!
> The dataset required some cleaning and additional columns to be created in order to explore the data to the level I would like. The most challenging aspect of the cleaning was caluclating the distance from set of longitude and latitude points. I managed to source a function from the website (#Found code for converting longitude and latitude data into km from (https://www.geeksforgeeks.org/program-distance-two-points-earth/) which I referenced in the exploration sheet.


## Summary of Findings

> Usage levels are lower on the weekends vs weekdays. This observation has remained consistently true throughout the years (2017 - 2020). We can explore this further to see if this behaviour is true depending on user types.
> Nothing useful observed when looking at usage levels by monthly cuts. It appears that the warmer months from March - October are the months where demand is higher. For the colder months (November - February), demand is lower.
> When looking at usage levels by hour of day; it is really interesting to see that duration the weekdays the hourly usage follows a biomodal distribution. With 8am and 5pm being the peak hours, which seems to suggest that people are more likely to high during commutable hours. Usage levels are flatter during the day when people are mostly likely in work. During the weekends the hourly usage very much follows a unimodal distribution with peak usage from 12pm through to 4pm. The usage figures demonstrates that people are most likely to be out and about in the City mid-day and at home during the evenings where usage levels start dropping off. Would be interesting to explore this further to see if this behaviour holds true for different user types.
> The median and mean duration of usage is much higher on the weekends than weekdays. The average distance covered per usage session is also higher over the weekend suggesting that people typically use a vehicle for longer on weekends and cover more distance.
> The scatter graph took a while to produce in order to show a relationship between duration and distance. There does appear to be a correllation between duration usage and distance covered.
> It was really interesting to explore the duration usage and distance covered between customers and subscribers. Not only are customers more likely to use rented vehicles for longer but also cover a greater distance.
> Really interesting to see how usage levels are consistent for customers throughout the week, whilst for subscribers there is a big drop off in usage levels going into the weekend. This could be due to the vast number of subscribers renting for commutable purposes. Let's see if there is a difference in usage levels by hour of day (weekday vs weekend) between customers and subscribers.
> Although the bimodal distribution for customers looks flatter in comparison to subscribers during the weekdays. A bimodal distribution still exists. A strong unimodal distribution exists for both customers and subscribers over the weekend.
> Unfortuantely no standout points when putting together a heatmap of most popular journeys with the exception that Embarcadero at Sansome St seems to be a popular starting and ending journey point.
> No additional insights when visualising hour by day against day of week usage levels via a heatmap.

## Key Insights for Presentation

> Usage levels by hour of day is very interesting as the distribution is different during the weekdays (bimodal) vs weekends (unimodal)
> Usage levels between customers and subscribers across the weekdays is very interesting. For customers the usage levels are consistent across the week whilst for subscribers there is a big drop off going into the weekend.
> Distance and duration usage is much longer for customers than subscribers which is something worth pointing out.
> Heatmap of most popular journeys can help highlight keystations to ensure there is adequate demand in terms of vehicles for hire