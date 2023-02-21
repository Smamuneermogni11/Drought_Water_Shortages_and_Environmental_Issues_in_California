# Drought_Water_Shortages_and_Environmental_Issues_in_California








Drought, Water Shortage, and Environmental Issues in California 
 
 
 
 
A+ Team (group 4)
May 3, 2022 
 
  






















TABLE OF CONTENTS

Abstract	2
Business Understanding	3
Data Understanding & Preparation	4
Analysis	5
Environmental issues (PM2.5) (Muneer)	5
Drought & Water Shortage(reservoir) issues (David)	6
Conclusion:	9
Reference:	9

 
ABSTRACT
In terms of drought challenges in the United States, California is at the top of the list. Drought conditions are severe in comparison to other states, and there are several environmental concerns associated with drought. Particulate matter PM 2.5 has had a significant influence on agriculture, forestry, and cloud formation, resulting in a decrease in rainfall in the state because of the drought. PM 2.5 has also caused plenty of health problems. This research examines the drought's impacts on several places as well as the particulate matter in those areas. The correlations based on our meticulous exploratory analysis clearly depict the locations that are highly affected by these environmental issues and the specific group of population vulnerable in those locations.
BUSINESS UNDERSTANDING

Research Problem & Question 
The state of California is regularly facing water shortages and drought issues. According to Aghighi et al., “the issues are due to groundwater depletion, poor water administration, elevated temperatures, lack of strong government policies, and lack of systems for water resources management (Haghighi et al, 2018). Furthermore, the issues of water shortages and drought negatively impact public safety (in case of wildfire), public health, and the environments just to cite a few. An example of public health is the case of PM2.5 particulates. It is said that these particulates highly contribute to lung disease and cancer making it one of the dangerous environmental issues that must be monitored closely. 
So, our research question is framed as follows: Using GIS (Geographic Information Systems) analytic capabilities, what are locations in California that are highly impacted by PM2.5, droughts, and water shortages? 
Furthermore, the goal of this project is to perform analysis in the state of California, to have actionable information related to the status of drought, water shortages, and level of PM2.5 particulates. Moreover, the insights derived from the analysis could help to determine a data-backed strategy that would help individuals, or the State of California to minimize the populations’ exposure to these issues. 
In addition, our analytic objectives in support of the project’s goals are to establish where populations in California are more exposed to water shortages, drought, and air pollution, especially PM2.5 particulates. These objectives include:
	Having maps that depict the level of drought, water shortages, PM2.5 particulate matter, and the population in California
	Determine which areas in California have the level of PM2.5 that exceeds the state regulation and the number of people affected
	Determine which areas are highly affected by drought and the number of people affected 
	Determine Which areas are highly affected by water shortages
Meanwhile, criteria that will help to evaluate the success of our project include:
•	A list of areas in California that have a level of PM2.5 exceeding the state regulation
•	A list of areas in California with elevated level of drought 
•	A list of areas in California with elevated levels of water shortages.
Meanwhile to successfully perform the analyses, we are planning to use several tools or applications such as ArcGIS Insights, ArcGIS Online, ArcGIS Pro, ArcMap, and ArcGIS Notebooks just to cite a few. Furthermore, concerning the inventory of resources, all team members have access to the above-listed software via the Claremont Graduate University Advanced GIS Lab. 
Software
ArcGIS Online (Story Maps)	We used the Story Maps to summarize our project, as shown below 
https://storymaps.arcgis.com/stories/48f2916a80df4d658d6ea0de57c06b8e

ArcGIS Desktop	To create a customed feature layer, import PM2.5 particulate matter data and perform Analysis
https://agis.maps.arcgis.com/home/webmap/viewer.html?webmap=4610f5b84b854a07b569d5c846eba23c


Risk and Contingencies:
The only minor constraint that we face while working on this project is time constraints. The project must be completed, submitted, and presented by early May. This short deadline could lead to slightly poor data triangulation, insufficient data understanding, data preparation, and /or insufficient analyses.  Also, regarding the contingencies plan, if one of the team members stops working due to unforeseen circumstances, the remaining members will continue to work tirelessly to complete the project within the time limit.
DATA UNDERSTANDING & PREPARATION

We began to familiarize ourselves with our phenomenon by examining drought, water shortages, PM2.5 particulate data through the following sources:
United States Geological Survey (USGS): Most of the data used in this project related to water are obtained from U.S. Geological Survey GAGEII Dataset (http://water.usgs.gov/GIS/metadata/usgswrd/XML/gagesII_Sept2011.xml), U.S. Geological Survey NWIS dataset (http://waterdata.usgs.gov/nwis/sw), and U.S. Geological Survey Water Watch (http://waterwatch.usgs.gov/). Link to dataset : https://github.com/USGS-VIZLAB/CIDA-Viz/tree/main/ca_discharge#readme
Esri dataset related to Particulate Matter Exposure: This dataset is licensed as public domain by Esri. It is purposed for training, demonstration, and education. 
In addition, we would like to give full credit to both USGS and Esri for dataset preparation. Our team has not altered the original dataset obtained from the above-mentioned sources. 
Data
Data Description	Source
U.S.Geological Survey Water Watch	https://github.com/USGS-VIZLAB/CIDA-Viz/tree/main/ca_discharge#readme

U.S. Geological Survey GAGEII Dataset	http://water.usgs.gov/GIS/metadata/usgswrd/XML/gagesII_Sept2011.xml

Esri dataset PM2.5	Esri educational and training PM2.5 data licensed as public domain
ANALYSIS
ENVIRONMENTAL ISSUES (PM2.5) 
California is more vulnerable to pollution, particularly PM 2.5. (Particulate Matter). These are microscopic particles that might cause major health problems. People in California can participate in a variety of cardiopulmonary rehabilitation programs. One of the program's advantages is that it offers cost-effective chronic illness management.
When compared to natural resources, some human-made resources produce a lot of pollution PM 2.5. Pollutants emitted into the atmosphere include roadside emissions, industrial emissions, and wildfires.
Long-term exposure to PM2.5, according to researchers, has the greatest impact on public health from particle air pollution. Long-term exposure raises the chance of death by age, especially from cardiovascular causes. Identifying places with substantial senior populations will aid in the establishment of cardiopulmonary rehabilitation clinics. It is also possible that doing so will reveal locations where higher referral rates are predicted.
Forest cover can also have a negative connection with PM concentrations, which could be related to the settling and/or absorption of PM by trees. PM2.5 exposures, both chronic and acute, are concerning because of the small particles' potential to penetrate deep into the respiratory system and into the circulation. Middle-aged and older persons with acute or chronic respiratory and cardiovascular problems, as well as pregnant women, are the most vulnerable to wildfire smoke.
The San Joaquin Valley and the Sacramento Valley are two big valley regions in California. In California, meteorological subsidence is often higher and more frequent, resulting in a dry, very persistent cap on pollution releases. Because boundary layer air is limited to valleys, it does not mix across vast areas, exposing it to a variety of restrictions on PBL height. Due to diurnal heating, air mixing height is low in the winter, and mixing happens later and for a shorter amount of time on a given day. As a result, column AOD may have a weaker relationship with ground-level PM2.5 concentrations.
Newer epidemiological models indicate a larger death load in California than prior models, implying that improving air quality in California might result in more health benefits than previously assumed. Between ground PM2.5 sensors, these geographically precise PM2.5 concentrations can offer subject specific PM2.5 exposure estimates, reducing exposure errors in health effect research.
 Fig.1
•	The map depicts different amounts of Particulate Matter, ranging from 4.0 to 20.0.
•	Los Angeles and Fresno have the highest levels of particle matter in the range of 15.0 to 20.0.
•	Sacramento, Carson City, San Francisco, San Jose, San Diego, Tijuana, and Mexicali are among the other cities affected between 4.0 and 15.0.

DROUGHT & WATER SHORTAGE(RESERVOIR) ISSUES 
  While droughts are natural hazards defined by their prolonged period of below-average precipitation, water shortages depict insufficient water resources to meet the demands in a region. In addition, the continued drought issues in California over the past years have triggered changes in water laws resulting in significant water reforms which guide the behavior of water users and managers.
The California water code section 106.3 of the human right to water declared access to sufficient water for cooking, consumption, and sanitation as a fundamental human right. However, water shortages threaten basic household needs due to ongoing drought.
According to the U.S Federal drought classification, we are concerned about the persistent drought experienced in California as the record has it to be the most severe, resulting in over 80% of the state being plagued with drought issues.
We are aware of the economic impact drought has caused in California. However, our concern is even more fundamental to the environmental implication this may have on its citizenry.
Paleontological and tree-ring records indicate that California has experienced many multilayer droughts over several millennia (Cody et. al 2015). As a result, we may continue to see the exodus of people leaving for another state. 
Our report focuses on the drought and water shortage issues and whether it is causative of environmental problems like PM2.5.
Extreme Drought Counties
Siskyou, Humboldt, Trinity, Shasta, Mendocino, Tehama, Glenn, Colusa, Butte, Sutter, Yuba, Placer, Nevada, Sonoma, Merced, Mariposa, Madera, Fresno, Kings, Tulare, Kern, Inyo, San Bernardino.
Severe Drought Counties
Del Norte, Modoc, Lassen, Plumas, Sierra, El Dorado, Amador, Alpine, Sacramento, Yolo, San Joaquin, Solano, Napa, Marin, San Mateo, Marin, Contra Costa, Alameda, Calaveras, Tuolumne, Stanislaus, Santa Clara, Mono, Monterey, San Luis Obispo, Santa Barbara, Ventura, Los Angeles, San Bernardino, Imperial
Moderate Drought Counties
Riverside, San Diego, Orange
 
 
 
Correlation between drought and exposure to Particulate in California
1.	The correlation between drought and Particulate Matter Exposure in California shows that many regions are affected by both issues, making them more vulnerable to public health and potentially causing severe cancer and other health-related problems in some cases. When particulate matter levels in the atmosphere rise, the precipitation level changes, causing drought then the agriculture, forests, and wildlife are all negatively impacted.
2.	Fresno, San Francisco, San Jose, and Los Angeles are the cities in California most affected by severe drought and particle matter in the atmosphere.
3.	Particulate matter can lead to serious health problems like asthma, cardiovascular disease, and death.
4.	Several obligatory rules are being adopted to combat air pollution through car smog testing, since California has been lacking rain due to stagnant air pollution.
5.	The cities with the most traffic pollution are Fresno and Los Angeles caused by vehicles.
6.	Due to the heat, there are more wildfires in the summer, which produces more particulate matter.
CONCLUSION:
To conclude, the project's purpose is to evaluate the drought and water shortages in California, with the goal of exposing Californians to many sorts of concerns linked to water shortages, such as particulate matter PM 2.5 and its effects on health. So, in an examination of drought and particulate matter utilizing numerous Arc GIS tools, distinct sources of PM 2.5 are identified in various locations with variable amounts of PM 2.5 in the state of California, as well as their correlation to drought conditions. Also mentioned is a comparative analysis map between PM 2.5 and drought. It shows how severe droughts may boost particulate matter by changing atmospheric factors like precipitation amounts, preventing rain from falling, and adversely damaging agricultural regions.
Links:
Story Map:
https://storymaps.arcgis.com/stories/48f2916a80df4d658d6ea0de57c06b8e
Find_Locations_in_Annual_PM25_Monitoring_Sites:
https://services.arcgis.com/q3Zg9ERurv23iysr/arcgis/rest/services/Find_Locations_in_Annual_PM25_Monitoring_Sites/FeatureServer
Drought and PM 2.5 Map: 
https://agis.maps.arcgis.com/home/webmap/viewer.html?webmap=4eab739d94c14dbb982dcde1acee2b83

REFERENCE:
[1] Haghighi, E., Madani, K., & Hoekstra, A. Y. (2018). The water footprint of water conservation using shade balls in California. Nature Sustainability, 1(7), 358-360.
[2] Tianyang Wang, Bin Zhao, Kuo-Nan Liou, Yu Gu, Zhe Jiang, Kathleen Song, Hui Su, Michael Jerrett, Yifang Zhu, Mortality burdens in California due to air pollution attributable to local and nonlocal emissions, Environment International, Volume 133, Part B,2019,105232,ISSN 0160-4120, https://doi.org/10.1016/j.envint.2019.105232 
[3] Chow, J. C., Watson, J. G., Fujita, E. M., Lu, Z., Lawson, D. R., & Ashbaugh, L. L. (1994). Temporal and spatial variations of pm 2.5 and pm 10 aerosol in the southern california air quality study. Atmospheric Environment, 28(12), 2061–2080. https://doi.org/10.1016/1352-2310(94)90474-X
[4] Meo, S. A., Abukhalaf, A. A., Alomar, A. A., Alessa, O. M., Sami, W., & Klonoff, D. C. (2021). Effect of environmental pollutants pm-2.5, carbon monoxide, and ozone on the incidence and mortality of sars-cov-2 infection in ten wildfire affected counties in california. The Science of the Total Environment, 757, 143948–143948. https://doi.org/10.1016/j.scitotenv.2020.143948
[5] Nussbaumer, C. M., & Cohen, R. C. (2021). Impact of oa on the temperature dependence of pm 2.5 in the los angeles basin. Environmental Science & Technology, 55(6), 3549–3558. https://doi.org/10.1021/acs.est.0c07144
[6] Lee, H. J., Chatfield, R. B., & Strawa, A. W. (2016). Enhancing the applicability of satellite remote sensing for pm2.5 estimation using modis deep blue aod and land use regression in california, united states. Environmental Science & Technology, 50(12), 6546–55. https://doi.org/10.1021/acs.est.6b01438
[7] Jennifer, D. S., Jianzhao, B., Mohammad, Z. A.-H., Hyung, J. L., Sang-Mi, L., Frank, F., Patrick, L. K., & Yang, L. (2020). Estimating pm2.5 in southern california using satellite data: factors that affect model performance, 15(9). https://doi.org/10.1088/1748-9326/ab9334
[8] Air pollution a culprit in worsening drought and ... - NSF. (n.d.). Retrieved April 23, 2022, from https://www.nsf.gov/news/news_summ.jsp?cntn_id=122231
[9] Nuccitelli, D. (2021, June 8). California, 'America's garden,' is drying out " Yale climate connections. Yale Climate Connections. Retrieved April 23, 2022, from https://yaleclimateconnections.org/2021/06/california-americas-garden-is-drying-out/
[10] Scott, C. (2017, September 28). California climate and health, part I: Drought stirs up trouble F. Healthline. Retrieved April 23, 2022, from https://www.healthline.com/health-news/california-climate-and-health-part-1-drought-stirs-up-trouble-for-states-air-quality-111215#Harsh-Winter

