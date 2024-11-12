---
title: "Exploring Housing Inequality through Mapping
"
excerpt: "<br/><img src='https://github.com/hjyu483/hojungyu.github.io/blob/master/images/housing_map2.gif?raw=true'>"
collection: portfolio
---
*Course Work, Geovisualization and Geovisual Analytics Software, Georgia Tech, 2024* <br>

<!-- ![images/housingmap](/images/housingmap.png){: .align-center width="300px"} -->
<img src = 'https://github.com/hjyu483/hojungyu.github.io/blob/master/images/housingmap.png?raw=true'>

This map enables users to examine housing affordability by comparing median household income with median house value through a housing affordability index map. <br>
The data includes median income, housing price and affordability index. Median income and median housing price were sourced from ACS-5Year Survey data (2016-2020). The housing affordability index was calculated by dividing the median housing value by the median household income. I then  visualized a choropleth map of the housing affordability index using a  diverging color legend. This index provides an intuitive understanding of the spatial and economic disparities in housing affordability. <br>
In Exploratory Spatial Data Analysis, interactivity plays a big role in gaining insights. In my map, brushing and linking in one graph to be simultaneously selected in another, providing deeper insights. This approach helps users to quickly identify which counties are unaffordable within the scatter plot. Also, given that larger areas may be overemphasized on the map, brushing and linking provide more accurate insights for users compared to using a single graph alone.


[Housing Affordability Map](https://public.tableau.com/app/profile/hojung.yu/viz/HousingAffordabilityMap_17280173108570/Dashboard1?publish=yes) was created using Tableau Software, with data cleaned in R.
