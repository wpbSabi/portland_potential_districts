# Portland's Potential City Council Districts

Background:
* There is a city charter on the ballot for Portland, Oregon on November 8, 2022.  As part of this city charter update, Portland would establish four city council districts.  Read more about that change from [Portland United for Change](https://portlandunitedforchange.com/about).
* This GitHub repository uses 2020 census tract data to illustrate what four potential city council districts could look like based on relatively equal population representation from each district.  There will be at least five options shown below.

Data:
* The data used in this analysis is for educational purposes only.
* Although the 2020 Census Data is available to the public, [Portland State University](https://www.pdx.edu/population-research/census-data-oregon) and [Oregon Metro](https://rlisdiscovery.oregonmetro.gov/datasets/census-tracts-2020-redistricting-data) made this data accessible.  The Oregon Metro data was particularly helpful for the mapmaking due to the shapefiles provided, and the Portland State University data was particularly helpful due to the documentation about the fields in the data.

# Portland population distribution:
* While it would be easy to draw the potential new district lines along Portland's five "quadrants" (not including South), the distribution of population in Portland is not equal among these quadrants.
* The largest quadrant by population is Southeast, whereas the smallest quadrant by population is North.

The following map shows the Portland quadrants by census tracts and displays the population per quadrant:

![Portland Population by "Quadrant" Image](https://github.com/wpbSabi/portland_potential_districts/blob/main/images/quadrants_map.png)

# Portland Neighborhood Associations:
* [Portland Neighborhood Associations](https://www.portlandoregon.gov/civic/index.cfm?c=28385) are already geographically organized communities that have a political voice.
* The population by neighborhood association is not easily combined into four city council districts.

The following map from [portlandoregon.gov](https://www.portlandoregon.gov/civic/index.cfm?c=28385) shows the Portland neighborhood association groups:

![Portland Neighborhood Associations](https://github.com/wpbSabi/portland_potential_districts/blob/main/images/portland_neighborhood_associations.png)
| Neighborhood Association Group  | Population (estimated by census tract) |
| ------------- | ------------- |
| CNN | 46,064  |
| EPCO  | 150,280  |
| NECN  | 69,748  |
| NPNS  | 71,070  |
| NWNW  | 42,018  |
| SEUL  | 171,566  |
| SWNI  | 105,124  |


# Options for Creating City Council Districts
While developing options for the four potential districts, the following resources can be helpful:
* [Tract Map](https://github.com/wpbSabi/portland_potential_districts/blob/main/images/tracts.png)
* [Population by Tract Map](https://github.com/wpbSabi/portland_potential_districts/blob/main/images/population.png)



## Option 1 - Keep districts close to neighborhood association group districts 
* [Link to interactive html map to zoom into street level - and then click Download](https://github.com/wpbSabi/portland_potential_districts/blob/main/images/option_1.html)
* NW, SW, and St John's from N
* East 
* SE (less a little in the East)
* NE (plus inner N)
![Option 1](https://github.com/wpbSabi/portland_potential_districts/blob/main/images/option_1.png)

## Option 2 - Keep similar communities within districts
* [Link to interactive html map to zoom into street level - and then click Download](https://github.com/wpbSabi/portland_potential_districts/blob/main/images/option_2.html)
* NW, SW and Sellwood 
* N and Forest Park 
* East Portland 
* SE (less Sellwood)
![Option 2](https://github.com/wpbSabi/portland_potential_districts/blob/main/images/option_2.png)

## Option 3 - Keep the most dense communities in the same district
The following density map is calculated as Population / GISacres for each census tract; the density is correct although the numbers might not be particularly meaningful.  In this map we can see that Portland's central density is greater than the outer density, but not by a particularly large degree:
![Density](https://github.com/wpbSabi/portland_potential_districts/blob/main/images/density_zoom.png)

Here's the district map for Option 3:
* [Link to interactive html map to zoom into street level - and then click Download](https://github.com/wpbSabi/portland_potential_districts/blob/main/images/option_3.html)
* The 24 most dense census tracts are in inner NW/SW/NE/SE
* Inner Southeast and West
* North and Northeast
* Outer Southeast
![Option 3](https://github.com/wpbSabi/portland_potential_districts/blob/main/images/option_3.png)


# Conclusion:
* While each approach/option meets good objectives, drawing perfect districts is not possible. 
* Fortunately, the city charter update would take into account that there are no perfect maps.  Each district would have three representatives and each of those representatives would be elected by ranked-choice voting in the same election.  That is to say, the top three candidates for each district would win a seat on the city council. 
* That way, multiple communities within each district can have their representative of choice elected, as long as that candidate is one of the top three vote earners in the election. See [Portland United for Change](https://portlandunitedforchange.com/about) for more details.

