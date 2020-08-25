---
layout: post
date:   2020-08-31
image: "/summer2020_research/images/csr_thumbnail.png"
title:  "COVID-19 AND HOUSEHOLD OVERCROWDING VULNERABILITY"
author: "Nelson De Jesus Ubri"
---

**Social Vulnerability Index (SVI) Breakdown at County Level**

As a measure of vulnerability during the Coronavirus pandemic, **crowding**, one of the fifteen social factors composing the *Social Vulnerability Index (SVI)*, serves as a metric to identify vulnerable US counties with high rates of **occupancy per room (PPR)**. The CDC calculates PPR at 1.5 or more persons per room, which leads to higher vulnerability of a household. This metric is particularly important during the spread of a new highly contagious infectious disease because crowding is a condition-based indicator that helps understand vulnerability at an urban and rural scale based on the National Center for Health Statistics(NCHS)/CDC classification.


As the Social Vulnerability Index (SVI) is broken down, how would focusing on a single social factor (Crowding) help understand the vulnerability of a household at a county/census tract level through the following framework?
1. SVI Vulnerability Level: 0.975-1 Level
1. SVI Crowding Vulnerability Level: 0.975-1 Level
1. National Center for Health Statistics(NCHS)/CDC classification
  * What is the classification of the most vulnerable counties?
  * What region are they located?
  * What are their characteristics?
      - Population
      - Main Industry(ies)
      - Housing typologies (Mobile Homes/Multi-Unit Structures)
1. Total household count
  * Percentage of household considered crowded (PPR: 1.5 or higher)
1. Socioeconomics
  * Poverty Levels (census tract level)

Plotting the Data: Overall SVI at County Level per State
![Overall SVI](/summer2020_research/images/crowding/COVID Data_State_Graphs-01.png)

All of the counties and their overall vulnerability is being plotted in the graph above. The sizes of the circles represent the count of COVID-19 cases in the county. The data reflects the vulnerability scale that the CDC Social Vulnerability Index (SVI) uses to classify counties base on their individual vulnerability. It ranges from 0 tp 1.  

Plotting the Data: Overall SVI at County Level per State based on Crowding Vulnerability
![Overall SVI](/summer2020_research/images/crowding/COVID Data_State_Graphs-02.png)

All of the counties and their crowding vulnerability is being plotted in the graph above.

Plotting the Data: Overall SVI at County Level per State based on Crowding Vulnerability
![Overall SVI](/summer2020_research/images/crowding/COVID Data_State_Graphs-03.png)

All of the counties and their crowding vulnerability is being plotted in the graph above. The sizes of the circles represent the share of population of each county with COVID-19.

The color combination sequences of the three graphs above use six colors to identify under which National Center for Health Statistics(NCHS)/CDC classification each county falls. The six classifications are as follows:
1. Large Metro
 * Large Central Metro (1)
 * Large Fridge Metro (2)
1. Medium Metro (3)
1. Small Metro (4)
1. Micropolitan (5)
1. Noncore (6)


**Social Vulnerability Index (SVI) Breakdown at Census Tract Level**

Understanding the underlying conditions that lead to underhoused households and crowding vulnerability is dependent on identifying the location of high concentrations of said vulnerability. The census tract breakdown will help build a more accurate picture of crowding vulnerability within a county. This data will be enhanced by satellite imagery to locate population clusters and identify some of its physical characteristics.

For this analysis, correlations between **high crowding and Covid-19 case rates** will be the main criteria taken into account when describing and comparing counties and census tracts. Urban and rural counties will be compared down to census tract level and counties with the same NCHS/CDC classification.

The crowding vulnerability indicators used include:
1. Housing type
1. Transportation mode
1. Industry
1. Covid-19 Count/Share of Population
1. Household Size
1. Household Occupancy per Room
1. Current news stories that help connect these indicators


## Plotting the Data
![COVID Cases](/summer2020_research/images/crowding/COVID Data_State-01.png)

Link to sources [text of link](https://www.politico.com/states/new-york/albany/story/2020/04/11/new-york-citys-most-crowded-neighborhoods-are-often-hardest-hit-by-coronavirus-1274875).

To embed images first ensure that the file is at least 740px wide. Then place the image file in a folder named for your group in the images folder. Then link to that image using the format here, but replace the file path with the name of your group's folder and appropriate image file name:



If you want to include html files (i.e. an interactive map) host these via your personal github page, and then you can embed them in your document with a iframe. The format looks like this:

<div class="iframe-column"><iframe src="https://player.vimeo.com/video/290575503?title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0"></iframe></div>


All you need to do to use one is replace the url that is between the two " ". Here is an iframe of mapbox tiles:

<div class="iframe-column"><iframe src="https://api.mapbox.com/styles/v1/mapbox/satellite-v9.html?title=true&access_token=pk.eyJ1IjoibWFwYm94IiwiYSI6ImNpejY4NDg1bDA1cjYzM280NHJ5NzlvNDMifQ.d6e-nNyBDtmQCVwVNivz7A#2/0/0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0"></iframe></div>

Use Author-Date parenthetical citations following Chicago Manual of Style conventions throughout your document, and add a works cited at the bottom of your post. See Author-Date quick guide [here](https://www-chicagomanualofstyle-org.ezproxy.cul.columbia.edu/tools_citationguide/citation-guide-2.html) for citation conventions.
