
In this project, the Ford GoBike System Data is analyzed. This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.The dataset can be found [here](https://www.fordgobike.com/system-data).

## Summary of Findings

In the exploration, found that there is a strong relationship between the distance traveled with the duration that the bike is used only when the duration is less than 20 min. After this time there seems to be no relationship between the distance and the time. 

The duration that the bike is borrowed is approximately normal distributed. The duration has also been examined in with customer/subscriber and male/female and found that they are also close to normal distribution. The distance traveled is also examined and found that a surprising amount of people travel 0 km. If one ignores those that travel 0 km the shape of the distribution is also close to normal distribution. 

I have also examined relation of month and time with the amount of bikes that are borrowed. It's found that at 8:00 and 17:00 of each day the number of bike users reaches the maixum. This is also in correlation with the rush hour. 

## Key insights for presentation

For the presentaion, I focus on the distribution of distance and duraion. I plotted the majority of the data with histgram and left out some outliers. I also focus on the month and hour of the day when the bikes are borrowed. I plotted the distribution with barplot.

In the end, I study the relationsihp of distance and duration with the heatmap. I found that there's a linear relationship between distance and duration only when the duration is less than 20 min. I also looked at this relationship within each user group and gender group. I can conclude that there's a stronger lineat correlation between distance and duration in subscriber group than the customer group.
