# Project 2: Pipeline Routes & Overlap with Minority Populations and Below Average Income Levels in Pennsylvania

In my last project, I analyzed the pipeline routes and neighborhoods with higher minority populations in Chester County, Pennsylvania to see if there was any of an indication of a trend between pipeline routes being constructed through more predominantly non-whote neighborhoods. I did end up seeing a larger total length of pipeline running through minority neighborhoods, and wanted to see if income played a similar role by being constructed more frequently in lower income areas. I also wanted to see if the patterns, if any, also existed at the state level or if these trends were more county specific.

<img src="/images/chesco_income.png?raw=true"/>

I got the data for this map by downloading a spreadsheet of household income data from chescoplanning.org, then joined it to the Chester County shapefile to assign the values to each municipality. I calculated the median value and then selected the municipalities that had household income levels below the median levels, as shown in red above. Only about 37% of the pipeline passed through these areas, suggesting that there is not a relationship between lower income areas and where pipeline routes were constructed in the county. 

I was curious to see if spatially, these areas I was analyzing overlapped at all. I decided to overlay the layers of municipalities with above average minority populations with the layer of below average income to create the map below. I was surprised to see that there was not much overlap between these two classes.

<img src="/images/cc_income_race.png?raw=true"/>

I wanted to see if the entire state of Pennsylvania followed the same trends as I saw in Chester County. I gathered census data from the Pennsylvania Geospatial Data Clearinghouse and subsetted it by county, using the same method I used in my last project to highlight counties with above average minority populations. I found that only about 35% of the total pipeline length ran through these counties which make up about 42% of the total state area, so there was no correlation or trend here like that I saw in Chester County.

<img src="/images/PA_minority.png?raw=true"/>

There did seem to be more of a trend when pipeline routes were compared to income data. In total, about 60% of the pipeline passed through these counties which also make up around 42% of Pennsylvania’s area, suggesting that there is more pipeline construction in lower-income counties.

<img src="/images/PA_income.png?raw=true"/>

Like Chester County, I wanted to see how these areas overlapped. Again, there was barely any overlap between the two categories. From looking at the areas highlighted on the map, it seems that the areas with higher minority populations tended to be more urban, and the areas with lower income tended to be more rural counties. This makes sense in terms of the pipeline construction because it had a much higher occurrence in the lower income counties, which because they are rural, offer more available space for pipeline construction.

<img src="/images/PA_income_race.png?raw=true"/>
