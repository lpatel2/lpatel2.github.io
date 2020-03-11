# Project 1: Analyzing Pipeline Routes in Chester County, PA

## Topic
This project will examine if and how pipeline development in Chester County, PA affects non-white neighborhoods and municipalies disproportionately to predominantly white neighborhoods. I could expand this to multiple counties or the entire state if this scope turns out to be too small/specific however, I chose this scale because of the high Hispanic migrant population in Chester County.

## Data
 I found Chester County demographic data from https://chescoplanning.org/Resources/Data.cfm and pipeline data at https://chesco.maps.arcgis.com/apps/MapTools/index.html?appid=873f036ecb6d418c9cf80eaa022c48b7

## Analysis

<img src="/images/chesco_race.png?raw=true"/>

For my first project, I wanted to see if there was a spatial relationship between the placement of pipeline routes and predominantly-non white municipalities, since the pipeline installation is a hot issue in my hometown and wanted to know how it was actually affecting the people who live here. The map above simply shows the non-white population as a percentage of the total population in each municipality. I got this race data from a demographics excel spreadsheet that I found on the Chester County Planning website, and joined to a shapefile of the boroughs and townships. I then performed calculations in the attribute table to add up all the minority populations and symbolize them as a percentage of the total population, to show the distribution and clustering of non-white populations on the map. I chose to add all the minority populations into one category since Chester County is predominantly white in most places and therefore some of the numbers for a single minority population were miniscule.

<img src="/images/chesco_race_pipeline.png?raw=true"/>

I then downloaded a shapefile of pipeline routes through the county, also from the Chester County Planning website. For this analysis, I chose to simply calculate the average nonwhite population in Chester County as a whole, and then categorize each municipality as having a  below or above average non-white population. I calculated the total length of pipeline throughout the county, which was 307,458 meters. Then, I selected the sections of pipeline that fell within only municipalities with above average non-white populations, which turned out ot be 114, 733 meters, or 37% of the total pipeline length. However, these municipalities cover only 29% of the county total area, which means there is a higher ratio of pipeline length per unit space of municipalities with above average non-white populations versus those with below waverage populations.
