# Extreme Weather Fatalities in the United States

I used official data from the National Weather Service (NWS) to examine U.S. fatalities from tornadoes, floods, and hurricanes since 1940. The NWS data are compiled from Storm Data, which collects information from National Weather Service offices across the United States.

For each year, I added the number of tornado, flood, and hurricane fatalities together. I then grouped the annual totals by decade and calculated the average number of fatalities per year for each period.

---

## Trend in Weather-Related Fatalities

Using the same National Weather Service data, there were a total of 20,387 fatalities from tornadoes, floods, and hurricanes in the United States between 1940 and 2024.

The average number of fatalities from these three types of extreme weather was approximately **240 deaths per year** over the entire 1940–2024 period.

![Storm fatalities table](storm-fatalities-table.png)

Looking only at tornado, flood, and hurricane deaths, I would say the general trend has gone down, but definitely not in a straight line. In the earlier decades, the average was usually around 260 to 300 deaths per year. By the 1980s and 1990s, it had dropped to around 170 deaths per year. There are still some periods where the number goes back up, so I would not say the decline is perfectly consistent.

![Average annual storm fatalities chart](poster_chart_1_avg_storm_fatalities.png)

Once I include heat and cold deaths, though, the picture gets more complicated. Heat deaths especially can change a lot from year to year. So I would not simply say that weather-related deaths are falling. A better way to put it is that deaths from tornadoes, floods, and hurricanes have generally become lower over time, but once heat and cold are included, the overall trend is much less clear.

**Source:**  
National Weather Service, 80-Year List of Severe Weather Fatalities, 1940–2024  
https://www.weather.gov/media/hazstat/80year_2024.pdf


---

## Population-Adjusted Death Intensity

The raw death numbers are useful, but the U.S. population is a lot larger now than it was in the 1940s. Because of that, I decided to use deaths per million people as my “death intensity” measure.This way, a more accurate answer can be obtained.

I calculated it as:

**Death intensity = average annual deaths ÷ average population (in millions)**

![Population-adjusted death table](population-adjusted-table.png)

My biggest discovery is that once the population is taken into account, this decline seems more obvious. For instance, the original death toll in the 1950s was actually higher than that in the 1940s, but the mortality rate per million people was slightly lower. By the 2010s, the mortality rate was only about 0.61 per million people, while it was approximately 1.91 per million people in the 1940s. This is not a completely smooth recession. In the first decade of this century, this ratio rose again, and the period from 2020 to 2024 is not even a complete decade. Despite this, after this survey, we can more clearly see that the probability of ordinary people being exposed to these three extreme weather risks is much lower than the original total number of deaths.

![Storm fatalities per million Americans](poster_chart_2_deaths_per_million.png)

**Sources:**

National Weather Service, Weather Related Fatality and Injury Statistics:  
https://www.weather.gov/hazstat

U.S. Census Bureau, Historical and Annual Population Estimates:  
https://www.census.gov/data/tables/time-series/demo/popest/pre-1980-national.html

U.S. Census Bureau, National Population Totals, 2020s:  
https://www.census.gov/data/datasets/time-series/demo/popest/2020s-national-total.html
