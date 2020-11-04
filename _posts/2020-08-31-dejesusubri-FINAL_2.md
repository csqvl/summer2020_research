---
layout: post
date:   2020-08-31
image: "/summer2020_research/images/Nelson.jpg"
title:  "COVID-19 and Household Overcrowding Vulnerability"
author: "Nelson De Jesus Ubri"
---


#### Social Vulnerability Index (SVI) Breakdown at County Level


As a measure of vulnerability during the Coronavirus pandemic, **crowding**, one of the fifteen (15) social factors composing the *Social Vulnerability Index (SVI)*, serves as a metric to identify vulnerable US counties with high rates of **occupancy per room (PPR)**. The Centers for Disease Control and Prevention (CDC) calculates PPR at 1.5 or more persons per room, which leads to a higher vulnerability for a household. This metric is particularly important during the spread of highly contagious and infectious diseases because crowding is a condition-based indicator that helps understand vulnerability at an urban and rural scale based on the National Center for Health Statistics (NCHS)/CDC classification.

**Methodology: Part 1:**
As the Social Vulnerability Index (SVI) is broken down, how can focusing on a single social factor (Crowding) help us understand the vulnerability of a household at a county/census tract level through the following framework:
1. SVI Vulnerability Level: 0.975-1 Level
1. SVI Crowding Vulnerability Level: 0.975-1 Level
1. National Center for Health Statistics(NCHS)/CDC classification
  * What is the classification of the most vulnerable counties?
  * What region are they located in?
  * What are their characteristics?
      - Population
      - Main Industry(ies)
      - Housing typologies (Mobile Homes/Multi-Unit Structures)
1. Total household count
  * Percentage of household considered crowded (PPR: 1.5 or higher)
1. Socioeconomics
  * Poverty Levels (census tract level)


  --


#### Plotting the Data: Overall SVI at County Level per State

<img src="/summer2020_research/images/crowding/COVID Data_State_Graphs-01.png" alt="description of image" class="full-img">
Source: CDC Social Vulnerability Index (SVI). Link to sources [text of link](https://svi.cdc.gov/map.html).

**Mapping: Overall SVI at County Level per State**
![Overall SVI](/summer2020_research/images/crowding/Overall SVI_0_975_1_Crowded_Map-08.png)

All of the counties and their overall vulnerability is being plotted in the graph above. The sizes of the circles represent the count of COVID-19 cases in the county. The data reflects the vulnerability scale that the *CDC Social Vulnerability Index (SVI)* uses to classify counties based on their individual vulnerability. It ranges from 0 to 1.
The map geolocates the counties that are most vulnerable based on the *overall SVI scale*. Counties that have a *vulnerability of 0.975* or higher are shown. Highlighted with the red outline are the counties with the highest vulnerability.

--


#### Plotting the Data: Overall SVI at County Level per State based on Crowding Vulnerability

<img src="/summer2020_research/images/crowding/COVID Data_State_Crowding-02.png" alt="description of image" class="full-img">
Source: CDC Social Vulnerability Index (SVI). Link to sources [text of link](https://svi.cdc.gov/map.html).

**Mapping: Overall SVI Crowding at County Level per State**
![Overall SVI](/summer2020_research/images/crowding/Overall SVI_0_975_1_Crowded_Map-07.png)

All of the counties and their crowding vulnerability is being plotted in the graph above.
The map geolocates the counties that are most vulnerable based on the **Crowding**. Counties that have a *vulnerability of 0.975* or higher are shown. Highlighted with the red outline are the counties with the highest vulnerability.

--

#### Plotting the Data: Covid-19 Cases Count Based on Shared of Population at County Level

<img src="/summer2020_research/images/crowding/COVID Data_State_Graphs-03.png" alt="description of image" class="full-img">
Source: CDC Social Vulnerability Index (SVI). Link to sources [text of link](https://svi.cdc.gov/map.html).

--

#### Mapping: COVID-19 Case Count at County Level

![Overall SVI](/summer2020_research/images/crowding/SVI_Crowding_Covid_Cases_Per_10k-01.png)
Source: NYT Covid_19 Data Count. Link to sources [text of link](https://github.com/nytimes/covid-19-data).

All of the counties and their crowding vulnerability is being plotted in the graph above. The sizes of the circles represent the share of population of each county with COVID-19.

The color combination sequences of the three graphs above use six (6) colors to identify under which National Center for Health Statistics (NCHS)/CDC classification each county falls. The six classifications are as follows:
1. Large Metro
  * Large Central Metro (1)
  * Large Fridge Metro (2)
1. Medium Metro (3)
1. Small Metro (4)
1. Micropolitan (5)
1. Noncore (6)

Source: National Center for Health Statistics(NCHS)/CDC. Link to sources [text of link](https://www.cdc.gov/nchs/data/series/sr_02/sr02_166.pdf).

--

#### Social Vulnerability Index (SVI) Breakdown at Census Tract Level

Understanding the underlying conditions that lead to underhoused households and crowding vulnerability is dependent on identifying the location of high concentrations of said vulnerability. The census tract breakdown will help build a more accurate picture of crowding vulnerability within a county. This data will be enhanced by satellite imagery to locate population clusters and identify some of its physical characteristics.

**Methodology: Part 2:**
For this analysis, correlations between **high crowding and COVID-19 case rates** will be the main criteria taken into account when describing and comparing counties and census tracts. Urban and rural counties will be compared down to census tract level and counties with the same NCHS/CDC classification.
Site Identification:
1. Census Tract Level analysis: Breakdown of SVI
  * Using the crowding vulnerability:
      - What census tract is most vulnerable based on crowding?
      - What are the population centers within the census tract?
      - Overlapping with COVID-19 case count is data is available
1. Satellite Imagery
  * Population Clusters
      - Potential Housing Typology: The CDC considers mobile homes and multi-unit structures a point of vulnerability
      - Household composition?
      - Industry: What is the most preventable employment industry?
1. The crowding vulnerability indicators to be used include:
  * Housing type
  * Transportation mode
  * Industry
  * Covid-19 Count/Share of Population
  * Household Size
  * Household Occupancy per Room
  * Current news stories that help connect these indicators

**Counties with Highest Crowding Vulnerability**
![Overall SVI](/summer2020_research/images/crowding/Overall SVI_0_975_1_Selected Sites-09.png)

The list of counties above are the most vulnerable based on the Crowding Social Factor from the Social Vulnerability Index (SVI). Four of these counties were selected to break down to the census tract level to identify where crowding vulnerability is located. As described above, **high crowding and COVID-19 case rates** were considered the main vulnerability indicators to select these counties.

--

#### NCHS/CDC Classification: 1

**Site 1: Bronx County, NY**

Household crowding in New York City has been an issue that has worsened over the last decade. A report released by the Office of Comptroller of New York City in October 2015 details crowding conditions in each of the five (5) boroughs, with an increase of 15.8 percent city-wide between 2005 and 2013. The Bronx was the borough (county) with the most crowded households, with 12.4 percent of all of its housing units being crowded. 

Based on the overall Social Vulnerability Index (SVI), crowding conditions and COVID-19 infections, the Bronx County is the most vulnerable county. Within this borough, Highbridge/Concourse Village was one of the most affected community districts by the COVID-19 based on antibody result data released by the NYC Health Department. It also has some of the highest levels of crowding vulnerability at the census tract level. Below is a case study that compares county and census tract vulnerability.

<img src="/summer2020_research/images/crowding/Bronx_County_Satellite_-01.png" alt="Bronx County, NY" class="full-img">

![Overall SVI](/summer2020_research/images/crowding/Demographic_Housing_Industry_Info_A1_Bronx_Demographics.png)


**Census Tract**

<img src="/summer2020_research/images/crowding/Bronx_County_Satellite_Census_Tract-01.png" alt="Census Tract" class="full-img">

![Overall SVI](/summer2020_research/images/crowding/Demographic_Housing_Industry_Info_A2_Bronx_Housing.png)

![Overall SVI](/summer2020_research/images/crowding/Demographic_Housing_Industry_Info_A3_Bronx_Industry.png)

**Satellite Images on Site**

<img src="/summer2020_research/images/crowding/Satellite Images_Bronx Satellite.png" alt="description of image" class="full-img">

The site above is representative of *Large Central Metro (1)* based on the National Center for Health Statistics(NCHS)/CDC classification.

--

#### NCHS/CDC Classification: 2

**Site 2: Tunica County, MS**

Tunica County is the most vulnerable county in terms of overall SVI and crowding social factor with a classification of Large Fridge Metro (2). This county experiences less crowding than others compared in this analysis, but as a county in the middle of the Lower Mississippi Delta with a majority Black population, it represents a different demographic breakdown that is not as represented in the other counties. Below is a case study that compares county and census tract vulnerability.

<img src="/summer2020_research/images/crowding/Tunica County MS-01.png" alt="description of image" class="full-img">

![Overall SVI](/summer2020_research/images/crowding/Demographic_Housing_Industry_Info_B1_Tunica_Demographics.png)

**Census Tract**

<img src="/summer2020_research/images/crowding/Tunica Census Tract MS-01.png" alt="description of image" class="full-img">

![Overall SVI](/summer2020_research/images/crowding/Demographic_Housing_Industry_Info_B2_Tunica_Housing.png)


![Overall SVI](/summer2020_research/images/crowding/Demographic_Housing_Industry_Info_B3_Tunica_Industry.png)

**Satellite Images on Site**

<img src="/summer2020_research/images/crowding/Satellite Images_Tunica Satellite.png" alt="description of image" class="full-img">

The site above is representative of *Large Fridge Metro (2)* based on the National Center for Health Statistics(NCHS)/CDC classification.

--

#### NCHS/CDC Classification: 3

**Site 2: Kern County, CA**

<img src="/summer2020_research/images/crowding/Kern_County_Satellite_-01.png" alt="description of image" class="full-img">

![Overall SVI](/summer2020_research/images/crowding/Demographic_Housing_Industry_Info_C1_Kern_Demo.png)

**Census Tract**

<img src="/summer2020_research/images/crowding/Kern_Bakersfield_Census_Tract_-01.png" alt="description of image" class="full-img">

![Overall SVI](/summer2020_research/images/crowding/Demographic_Housing_Industry_Info_C2_Kern_Housing.png)


![Overall SVI](/summer2020_research/images/crowding/Demographic_Housing_Industry_Info_C3_kern_Industry.png)

**Satellite Images on Site**

<img src="/summer2020_research/images/crowding/Satellite Images_Kern Satellite.png" alt="description of image" class="full-img">

The site above is representative of *Medium Metro (3)* based on the National Center for Health Statistics(NCHS)/CDC classification.

--

#### NCHS/CDC Classification: 4

**Site 2: Imperial County, CA**

<img src="/summer2020_research/images/crowding/Imperial CA-01.png" alt="description of image" class="full-img">

![Overall SVI](/summer2020_research/images/crowding/Demographic_Housing_Industry_Info_D1_Imperial_Demo.png)

**Census Tract**

<img src="/summer2020_research/images/crowding/El Centro CA_-01.png" alt="description of image" class="full-img">

![Overall SVI](/summer2020_research/images/crowding/Demographic_Housing_Industry_Info_D2_Imperial_Hosuing.png)


![Overall SVI](/summer2020_research/images/crowding/Demographic_Housing_Industry_Info_D3_Imperial_Industry.png)

**Satellite Images on Site**

<img src="/summer2020_research/images/crowding/Satellite Images_Imperial Satellite.png" alt="description of image" class="full-img">

The site above is representative of *Small Metro (4)* based on the National Center for Health Statistics(NCHS)/CDC classification.

--

#### NCHS/CDC Classification: 5

**Site 2: Zapata County, TX**

<img src="/summer2020_research/images/crowding/Zapata_County_TX_-01.png" alt="description of image" class="full-img">

![Overall SVI](/summer2020_research/images/crowding/Demographic_Housing_Industry_Info_E1_zapata_Demo.png)

**Census Tract**

<img src="/summer2020_research/images/crowding/Zapata Census Tract TX-01.png" alt="description of image" class="full-img">

![Overall SVI](/summer2020_research/images/crowding/Demographic_Housing_Industry_Info_E2_Zapata_Housing.png)


![Overall SVI](/summer2020_research/images/crowding/Demographic_Housing_Industry_Info_E3_Zapata_Industry.png)

**Satellite Images on Site**

<img src="/summer2020_research/images/crowding/Satellite Images_Zapata satellite.png" alt="description of image" class="full-img">

The site above is representative of *Micropolitan (5)* based on the National Center for Health Statistics(NCHS)/CDC classification.

--

#### NCHS/CDC Classification: 6

**Site 2: Oglala Lakota County, SD**

<img src="/summer2020_research/images/crowding/Oglala_Lakota_Satellite_01.png" alt="description of image" class="full-img">

![Overall SVI](/summer2020_research/images/crowding/Demographic_Housing_Industry_Info_F1_Oglala_Demo.png)

**Census Tract**

<img src="/summer2020_research/images/crowding/Oglala Lakota_Satellite_Census Tract-01.png" alt="description of image" class="full-img">

![Overall SVI](/summer2020_research/images/crowding/Demographic_Housing_Industry_Info_F2_Oglala Housing.png)


![Overall SVI](/summer2020_research/images/crowding/Demographic_Housing_Industry_Info_F3_Oglala_Industry.png)

**Satellite Images on Site**

<img src="/summer2020_research/images/crowding/Satellite Images_Oglala Satellite.png" alt="description of image" class="full-img">

The site above is representative of *Noncore (6)* based on the National Center for Health Statistics(NCHS)/CDC classification.

--

References:
1. "CDC's Social Vulnerability Index (SVI)." Centers for Disease Control and Prevention. Accessed June 07, 2020. https://svi.cdc.gov/data-and-tools-download.html.
1. Census Reporter: Making Census Data Easy to Use. Accessed July 20, 2020. https://censusreporter.org/.
1. Cimini, Kate. "California's Housing Crisis Sickens Families." CalMatters. February 27, 2020. Accessed July 16, 2020. https://calmatters.org/projects/californias-housing-crisis-causes-illnesses/.
1.  Community Development Department. Housing Element 2015-2023. PDF file. February 16, 2016. http://www.ruralhome.org/storage/documents/ts2010/ts_full_report.pdf
1. Dougherty, Conor. "12 People in a 3-Bedroom House, Then the Virus Entered the Equation." The New York Times. August 01, 2020. Accessed August 03, 2020. https://www.nytimes.com/2020/08/01/business/economy/housing-overcrowding-coronavirus.html.
1. Feldman, Justin. "Does COVID-19's Toll Reflect Social Inequality? Early Evidence from NYC." Medium. April 02, 2020. Accessed July 10, 2020. https://medium.com/@jmfeldman/does-covid-19s-toll-reflect-social-inequality-early-evidence-from-nyc-209c3b0a0ff7.
1. Goldstein, Joseph. "1.5 Million Antibody Tests Show What Parts of N.Y.C. Were Hit Hardest." The New York Times. August 19, 2020. Accessed August 20, 2020. https://www.nytimes.com/2020/08/19/nyregion/new-york-city-antibody-test.html.
1.  Housing Assistance Council. Taking Stock: Rural People, Poverty, and Housing
in the 21st Century. PDF file. December 2012. http://docs.bakersfieldcity.us/weblink/0/edoc/1273910/Bakersfield%20Housing%20Element%20(2015-2023).pdf
1.  Lovett, Ian, Dan Frosch, and Paul Overberg. "Covid-19 Stalks Large Families in Rural America." The Wall Street Journal. June 07, 2020. Accessed July 25, 2020. https://www.wsj.com/articles/covid-19-households-spread-coronavirus-families-navajo-california-second-wave-11591553896.
1. Marvel, Shannon. "Pine Ridge Reservation Holds Strong during COVID-19 Pandemic." The Mitchell Republic. June 10, 2020. Accessed September 07, 2020. https://www.mitchellrepublic.com/newsmd/coronavirus/6529999-Pine-Ridge-Reservation-holds-strong-during-COVID-19-pandemic.
1. "NYC Planning Population FactFinder." NYC Population FactFinder. Accessed August 02, 2020. https://popfactfinder.planning.nyc.gov/profile/5854/housing?comparator=2.
1. Nytimes. "Nytimes/covid-19-data." GitHub. Accessed July 01, 2020. https://github.com/nytimes/covid-19-data.
1. Scott M. Stringer. NYC Housing Brief: Hidden Households. PDF file. October 2015. https://comptroller.nyc.gov/wp-content/uploads/documents/Hidden_Households.pdf
1. United States Census Bureau. Accessed July 01, 2020. https://data.census.gov/cedsci/.
1. "Zapata County, Texas Coronavirus Cases and Deaths." USAFacts.org. August 14, 2020. Accessed August 14, 2020. https://usafacts.org/visualizations/coronavirus-covid-19-spread-map/state/texas/county/zapata-county.
