## Correlation One Data Science 4 All Fellowship
Names: Natalie Davis, Silas Humphries, Vianny Lugo Aracena, Mariana Martinez, Kathia Vargas 
## Project scope: DC, Washington 
November 19th 2020 

## Business Problem

A food desert can be described as an area or region where people have limited access to healthy and affordable food. The United States Department of Agriculture (USDA) defines food deserts as the following: For urban areas, at least 500 people or 33% of the population must live more than 1 mile from the nearest large grocery store. In rural areas, at least 500 people or 33% of the population must live more than 10 miles from the nearest large grocery store. Moreover, the USDA identified more than 6,500 food deserts tracts in the US based from 2000-2006 data. “Food desert” is a term officially defined by the USDA. They may have a conflict of interest in solving the problem when they are defining it narrowly and in a way that ignores the government’s role in creating and maintaining inequitable access.  

Our project will focus on the issue of food insecurity by mapping food deserts/apartheid(s). Many historically distressed communities lack economic investment, including grocery stores that provide quality fresh food to people. For example,in 2018  in Washington DC, Wards 7 and 8 on the east side of the Anacostia river have 3 grocery stores to serve 148,000 residents.

## Business Impact

The lack of access to healthful foods and simultaneous over-exposure to fast foods may be linked to poor diets that are high in sugar, sodium, and unhealthful fats. It seems to be cheaper and more convenient to buy a quick fast food meal for the family than quality whole foods for a healthy meal. This can contribute to diet-related conditions such as diabetes, high blood pressure and cardiovascular disease.

Some of the health effects of living in a food desert include the following:
Higher incidence of obesity and other comorbidities
Increased prevalence of diabetes and other potentially fatal health conditions
Other weight-related conditions, especially in children
Lower life expectancy
Lower quality of life

Many food deserts also provide limited or unaffordable healthcare services. This contributes to negative health outcomes for people living in these areas. Moreover, the convenience stores in food deserts list higher prices for common food items (ie. flour, eggs, fruits, vegetables) than many grocery stores, which results in lower-income residents being priced out of healthier quality foods. The consequence is the convenience store may stop offering the healthier options because it doesn’t bring in revenue, leading to even less options for local residents. 

Beyond the health implications, we also see food deserts as another symptom of systemic racism. According to DC Health Matters, Wards 7 and 8 are both approximately 92% Black/African American. In Ward 7, the median household income is approximately $41K ($38K Black) and $37K ($34K Black) in Ward 8. In Ward 7, 25.21% of families live below the poverty line, while 30.73% do in Ward 8. Conversely, the median household income for the entire District of Columbia is approx. $90K. Furthermore, the median white household income is approx. $142K in DC. There is no doubt that historic and systemic racism have contributed to the large socioeconomic gaps along racial lines; these gaps are exacerbated by historic geographic segregation, leading to the manifestation of many inequalities, including our focus - food deserts. In our project, we hope our insights will lead to helpful solutions. 
 

## Data

Food Access Research Atlas data (USDA)
This file contains a total of 147 columns with county-level information. The data combines population data from the 2010 Census Population and Housing reported at the block level, and aggregated at the census tract level. It combines income data from the 2010-14 American Community Survey’s census  tracts estimates, and a directory of supermarkets, supercenters, and large grocery stores in the United States. 

Some of the major variables/fields available in this dataset are:
Pop2010 - population, tract total 
Povertyrate - tract poverty rate
Medianfamilyincome - tract median family income
LA1and10, LAhalfand10, LA1and20, LATracts_half -- variables highlighting accessibility by vehicle
Low access information by race and distance
Racial breakdown 
Age breakdown

## Google Maps API 
We will be using Google Maps API to find the exact location of supermarkets in the DMV (DC, Maryland,Virginia)  area 

Twitter API:  
We will be using the Twitter API to predict Food Deserts Via Population Health and Twitter Sentiment Analysis using the following topics: healthy foods, unhealthy foods, fast foods, and grocery stores created.


## Methods  
Visualizations and models 
Map: showing food desert areas, when you hover over an area you see more demographic characteristics
Google Maps API data will show grocery stores 
Text analysis of Twitter data to quantify sentiment of of people living in food deserts vs others
Predicting areas were grocery stores would be successful based on demand/need
Logistic regression / classification to try to predict contributing factors
Linear regression
Correlation
Factor analysis or clustering analysis for tier solution 

## Interface
Interactive dashboard where user can explore areas affected by food deserts and the tier system and solution representing the extent of the problem by area 
Correlation plots or graphs
Linear regression plots/graphs
Clustering/factor analysis results 
Text analysis sentiment analysis results 
input/field where you can submit location and return probability of success by area 
Simple wireframe or sketch 


## Milestones - 

We expect to finish Version 1 with 100% probability, Version 2 with ~70% probability, Version 3 with ~20% probability, and Version 4 with ~5% probability (if things go extremely well). 

V1 (mvp -- deliver 100% within 13 weeks): processed data, analyzed, model results, 2 graphs: static map, and a correlation plot
V2 (additional features): interactive map with demographic information by ward/area, one graph showing predictive model  
V3: interactive map with tiers, text analysis results 
V4 (stretch goal): final interactive map, final versions of previously mentioned graphs, factor analysis 

## Timeline


Date
Deliverable
Details
## Week 1
Team Formation 
Meet up
## Week 2
- Work on idea formation 
- Selected project topic on food deserts in  DC
## Week 3
- Idea should be finalized & Start on Scoping
- Completed project description
## Week 4
- Project Scoping Completed 
- Finalize and deliver the project scope 
## Week 5
- Datasets sourced 
- Identify final datasets 
## Week 6
- Basic EDA/Cleaning of datasets completed 
- Process the data, initial data discovery and exploration individually and meet as a group to discuss findings 
- Meet with mentor to discuss direction of data possible analysis options
## Week 7
- In-depth EDA, jupyter analysis, mockup of frontend
- Use jupyter notebooks to conduct appropriate statistical analysis 
- Finalize EDA and finalize possible analysis 
## Week 8
- Frontend Design 
- Create static maps and include appropriate analysis for a tier system
## Week 9
- Front End Complete
- Meet with mentor to get comments on analysis results and graphs/maps produced
- Create interactive maps with tier system 
## Week 10
- Application infrastructure complete
- Complete interactive map on a website 
## Week 11
- Project and Datafolio complete
- Meet with mentor to get final comments and implement comments
## Week 12
- Presentation rehearsed and ready
- Get in Top 10 best projects

## Concerns
Not having sufficient data
Team members have no domain knowledge on the topic, and different ranges of knowledge of data. 
Concerned about being innovative and not reinventing the wheel.
