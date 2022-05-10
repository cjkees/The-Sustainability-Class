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
<img width="277" alt="Screenshot 2022-05-09 162817" src="https://user-images.githubusercontent.com/60239725/167531953-f2dc652d-8e9a-4bed-9c07-4af015ba57c5.png"> Figure 3 is a table with the R-Squared values showing the relationship between Median Income and Vegetation Cover for each of the nine counties. The R-Squared values show that there is not a significant relationship between these two variables for any of the counties. Out of the nine, Contra Costa County, Alameda County, and Solano COunty have the most significant relationship, but they are not significant enough. This shows us that access to green space is not spatialy significant at a regional scale.







You can use the [editor on GitHub](https://github.com/cjkees/The-Sustainability-Class/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/cjkees/The-Sustainability-Class/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
