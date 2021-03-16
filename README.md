# Climate Change in King County, Washington
### Live Web Map Link: https://dhritiy.github.io/458FinalProject/

### ***Project Description:***
Greenhouse gases are one of the leading causes of climate change which can result in detrimental health effects for people living in areas where these gases are located. Specifically in this project, I show where greenhouse gas (CO2) emitting facilities are located in King County. Then I also show how much emissions these facilites release on a yearly basis through a graduated symbol layer (Total CO2 Emissions). Here the, the larger triangle and darker brown represents facilities with the highest metric tons of emissions. King County also uses this data to predict how much heat will accumulate in an area and predict how much seasonal warming will occur. To represent this data, I have created the choropleth Future Heat Accumulation and Warming layer. The darker red here shows areas where King County scientists predict will accumulate the greatest amount of heat.

To put this data in perspective, I created two demographic choropleth, quantile layers of King County. The first, Minority Percentage of Population, represents the percentage of people living in a census tract that are a minority. The second, Poverty Percentage of Population, represents how many people in each tract are living below the poverty line.

Through this project, you can toggle on and off different layers and compare and contrast where emission facilites, largest amounts of CO2, and heat accumulation are located. Then you can also compare these locations with the characterstics of residents of those areas.

### ***Project Goal:***
The main goal of this project is to show how different demographics in King County are disproportionately susceptible to climate change caused by greenhouse gases. Specifically, I wanted to display how census tracts with a high percetange of minorty population and high percentage of people living below the poverty line are at the greatest risk.

By turning on the CO2 Emission Facilities layer and the minority population layer, it is clear to see that the majority of these facilites are located in areas where the highest amount of minorites reside. When you turn on the poverty population layer with the facilties layer, you can once again see that typically CO2 emitting facilities are located in tracts with high poverty percentage. Furthermore, the same correlation can be seen when comparing the demographic layers with the heat accumulation layer. These findings inidicate that minorities and people living below the poverty line are at the greatest risk for the health effects caused by greenhouse gases and the climate change that comes with it.


### ***Sources:***
- [Demographic Data (CDC SVI Index 2018)](https://www.atsdr.cdc.gov/placeandhealth/svi/data_documentation_download.html)
- [Emissions (Greenhouse Gas Reporting Program 2019)](https://data.wa.gov/Natural-Resources-Environment/GHG-Reporting-Program-Map/gtyb-56w7?referrer=embed)
- [Heat Accumulation (King County GIS Open Data 2020)](https://climate-kingcounty.opendata.arcgis.com/datasets/growing-degree-days-all-scenarios?selectedAttribute=GDD4_50)
- [Climate Change and the Impact of Greenhouse Gases (Frontiers in Plant Science 2018)](https://www.frontiersin.org/articles/10.3389/fpls.2018.00273/full)

### ***Applied Libraries:***
I used the Google Fonts library to set a font for the legend. I also used chroma.js in order to create four different color schemes to represent the different colorings in each layer. I then added these colors to the legend. I also used Font Awesome for some style aspects Additionally, I also used the JavaScript leaflet.ajax library.

### ***Acknowledgement:***
The datasets and shapefiles I used in this project are from the CDC, King County GIS Open Data, and the Greenhouse as Reporting Program. The grayscale ad streets basemaps are from Carto DB. The Satellite basemap is from ArcGIS Online. I would also like to acknowledge Professor Zhao and Tyler McCrea for being great instructors for this course.


**Author:** Dhriti Yandapally
**Professor:** Bo Zhao
**Class:** GEOG 458
**Date:** 12th March, 2021
