## **Income Disparities in Access to Green Space in the Nine Bay Area Countines**
by Cam Kees | CP 255 | Spring 2022

### **INTRODUCTION**

#### _Background_
Green open spaces have been proven to have a variety of positive physical and mental health impacts. Green spaces and tree canopy cover improve air quality, lower the risk of asthma and cardiovascular diseases, provide exercise and leisure space, and improve an individual's overall wellbeing. In addition to the benefits provided to individuals, green open spaces also provide environmental benefits, such as protection from Urban Heat Islands (UHI). UHI is the disproportionate rise in temperatures in urban areas due to impervious surface materials. Green space and canopy cover protect from UHI by providing natural surfaces with high albedos and shade refuge. However, because green spaces have become increasingly desirable, resilience is equated with wealth and many cities in the United States are now experiencing the emergence of the Sustainability Class.

The Sustainability Class refers to the disproportionate access to green open spaces. Previous studies have found that populations with low socioeconomic status, as well as non-white minority populations, overall have less access to open spaces than more affluent neighborhoods. This creates an environmental justice issue as these populations are being excluded from the sustainability benefits provided by these spaces. The environmental justice framework is based on the principle that all people, regardless of race or socioeconomic status, have a right to equitable distributions of environmental amenities (Wen, 2013). While the Sustainability Class is a relatively new concept in education and research, the effects of it have been around for decades. Many of the communities that were redlined in the 1930s as part of the HOLC security maps that enforced systematic denial of services to numerous minority communities across the United States. Today a large portion of these redlined communities remain as low-income minority communities, and still lack the access to necessary public amenities, such as green open space.

#### _Research Question_
What is the relationship between income and proportion of vegetated land cover across the nine Bay Area Counties? Is the Sustainability Class more prevalent in some geographies than others? Which communities have the most disproportionate access to green spaces?

#### _Hypotheses_
1. Census Tracts with lower median incomes will experience lower access to green spaces

#### _Motivation_
My motivation for pursuing this topic is to better understand which communities in the Bay Area are most excluded from sustainable developments. Having grown up in Alameda County, I call the Bay Area my home and would like to have a positive impact as a future planner in these communities.



### **METHODS AND ANALYSIS**
For this analysis proportion vegetation cover was used to estimate access to green open spaces. Vegetation cover was calculated using NDVI values derived from satellite imagery. While NDVI does not equate to open space, it is useful in measuring the relative amount of greenspace in each census tract across large geographies. Proportion vegetation cover was summarized by census tract to be at the same analysis level as the census income data.

#### _Study Area_
The study area chosen for this project are the Nine Bay Area counties. This project analyzes access to vegetated land cover at the county scale, city/place scale, and at the census tract scale. Through assessing spatial relationships between vegetation cover and socioeconomic status, this project identifies disadvantaged communities in the Bay Area experiencing environmental injustices.

#### _Data_
The data sources used for this analysis are as follows:
  - USGS LANDSAT 8 Imagery, 2020
  - US Census ACS 5 Year Estimate Summary Tables, 2020
  - Association of Bay Area Governments Open Data Portal
  - University of Richmond Mapping Inequality Project

#### _County Level Association_
Figure 1 below shows a map of the census tracts that make up the Nine Bay Area Counties. Figure 2 shows the proportion vegetation cover by census tract for the same geography. As expected, the more urbanized areas near city centers have a low amount of observed vegetation cover when compared to the rural and forested areas that surround Bay Area Cities.


##### **Figure 1:** Bay Area Census Tracts by County
<img width="719" alt="Screenshot 2022-05-09 162738" src="https://user-images.githubusercontent.com/60239725/167530987-148e79f4-fb1e-4e10-833c-c7a04d203543.png">


##### **Figure 2:** Proportion Vegetation Cover by Census Tract
<img width="719" alt="Screenshot 2022-05-09 193708" src="https://user-images.githubusercontent.com/60239725/167531542-1564bfbc-a824-4a53-a28c-098942866f56.png">


##### **Figure 3:** County Level Relationship Between Median Income and Proportion Vegetation Cover
<img width="277" alt="Screenshot 2022-05-09 162817" src="https://user-images.githubusercontent.com/60239725/167531953-f2dc652d-8e9a-4bed-9c07-4af015ba57c5.png"> 
Figure 3 is a table with the R-Squared values showing the relationship between Median Income and Vegetation Cover for each of the nine counties. The R-Squared values show that there is not a significant relationship between these two variables for any of the counties. Out of the nine, Contra Costa County, Alameda County, and Solano COunty have the most significant relationship, but they are not significant enough. This shows us that access to green space is not spatialy significant at a regional scale.

#### _Urban Rural Divide_
The urban rural divide is the concept that there is a strong divide in land use, policy, and politics between urban and rural areas. By nature, rural areas have amuch larger proportion of vegetation cover than urban areas because there is more land and less density. In order to account for the urban rural divide, this analysis clipped the census tracts to only include tracts that fall within census designated 'places.' These include cities, towns,a nd a handful of other designated places.  This is not the most accurate way of accounting for the divide, but it is efficient for analyzing large geographies. Figure 4 and 5 below show the clipped County Boundaries and the Proportion Vegetation Cover within these new defined areas.


##### **Figure 4:** Bay Area Census Tracts by County 'Places'
<img width="718" alt="Screenshot 2022-05-09 165247" src="https://user-images.githubusercontent.com/60239725/167533947-5336f650-3e3d-46df-8b80-8588e92e1880.png">


##### **Figure 5:** Proportion Vegetation Cover by Census Tract 'Places'
<img width="716" alt="Screenshot 2022-05-09 164426" src="https://user-images.githubusercontent.com/60239725/167534044-f2ce0e5b-9255-4ec2-926f-66556568fb5c.png">


##### **Figure 6:** County 'Places' Level Relationship Between Median Income and Proportion Vegetation Cover
<img width="278" alt="Screenshot 2022-05-09 162845" src="https://user-images.githubusercontent.com/60239725/167534273-810f204d-d28f-46a6-82fc-1d0f5a9e2025.png">
Figure 6 above shows the changes in R-Squared Values for the nin counties after accounting for the urban rural divide. The results are insignificant, in that there was no trend in how the R-Squared values changed amongst the counties. While some counties experienced a slight inclrease and others a slight decrease, no change was highly significant.

Figure 7 below shows a scatterplot of the relationship between Median Income and Proportion Vegetation Cover, with the colors identofying the Counties and the size representing the population of each census designated place.


##### **Figure 7:** Scatterplot Relationship Between Median Income and Proportion Vegetation Cover


In the figure above each point represents a census designated place. While the scatterplot does not show a strong relationship between the two variables, there are a few interesting takeaways from this chart. The plot shows that each place within each County cluster together in terms of Median Income. While the range of Median Income across the whole region is large, the range within each county is relatively small. Next, the size of the points in the plot show that there is a relationship between population size and vegetation cover. Places with higher populations are geberally lower on the y-axis than less populated places. Figure 8 below shows a picked apart version of the above figure, separated into each different county.


##### **Figure8** Scatterplot Relationship Between Median Income and Proportion Vegetation Cover by County



#### _Places Level Association_
Since the relationships between income and vegetation were insignificant at the county level of analysis, the next step is to look at a more granular geography.  
