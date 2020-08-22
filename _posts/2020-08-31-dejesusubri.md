---
layout: post
date:   2020-01-01
image: "/summer2020_research/images/csr_thumbnail.png"
title:  "nd2584"
author: "Nelson De Jesus Ubri"
---
This is a document that is written in markdown. What is markdown? It is a 'markup language' that allows you to format plain text in a way that is easily converted to many different formats. For example, this document was written in markdown but will be used as an webpage and converted into HTML.

To present and turn in your final projects for Conflict Urbanism: Puerto Rico Now you will be editing this template. You will include all of the text of your paper here, along with any and all images, maps, videos, or other materials that you produce.

[This webpage](https://guides.github.com/features/mastering-markdown/) provides a comprehensive guide to markdown syntax. But to make things easier for you we are including a cheat sheet of the main things you need to know here.

#### Please use level 4 headings for major section divisions
(make sure to put two spaces after the end of the heading)

Social Vulnerability Index (SVI) Breakdown at County Level

As a measure of vulnerability during the Coronavirus pandemic, **crowding**, one of the fifteen social factors composing the *Social Vulnerability Index (SVI)*, serves as a metric to identify vulnerable US counties with high rates of **occupancy per room (PPR)**. The CDC calculates PPR at 1.5 or more persons per room, which leads to higher vulnerability of a household. This metric is particularly important during the spread of a new highly contagious infectious disease because crowding is a condition-based indicator that helps understand vulnerability at an urban and rural scale based on the National Center for Health Statistics(NCHS)/CDC classification.

Italics are *similar* and are formatted like this.

To make a paragraph break you need to add two spaces at the end of your line before going to the next line.

Social Vulnerability Index (SVI) Breakdown at Census Tract Level

Understanding the underlying conditions that lead to underhoused households and crowding vulnerability is dependent on identifying the location of high concentrations of said vulnerability indicators. The census tract breakdown will help build a more accurate picture of crowding vulnerability within a county. This data will be enhanced by satellite imagery to locate population clusters and identify some of its physical characteristics.

For this analysis, correlations between **high crowding and Covid-19 case rates** will be the main criteria taken into account when describing and comparing counties and census tracts. Urban and rural counties will be compared down to census tract level and counties with the same NCHS/CDC classification.

The crowding vulnerability indicators used include:
1. Housing type
1. Transportation mode
1. Industry
1. Covid-19 Count/Share of Population
    * Household Size
    * Household Occupancy per Room
      - Current news stories that help connect these indicators


Use Author-Date parenthetical citations following Chicago Manual of Style conventions throughout your document, and add a works cited at the bottom of your post. See Author-Date quick guide [here](https://www-chicagomanualofstyle-org.ezproxy.cul.columbia.edu/tools_citationguide/citation-guide-2.html) for citation conventions.

Link to sources [text of link](https://www.politico.com/states/new-york/albany/story/2020/04/11/new-york-citys-most-crowded-neighborhoods-are-often-hardest-hit-by-coronavirus-1274875).

To embed images first ensure that the file is at least 740px wide. Then place the image file in a folder named for your group in the images folder. Then link to that image using the format here, but replace the file path with the name of your group's folder and appropriate image file name:

![COVID Cases](/summer2020_research/images/crowding/COVID Data_State-01.png)

If you want to include html files (i.e. an interactive map) host these via your personal github page, and then you can embed them in your document with a iframe. The format looks like this:

<div class="iframe-column"><iframe src="https://player.vimeo.com/video/290575503?title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0"></iframe></div>


All you need to do to use one is replace the url that is between the two " ". Here is an iframe of mapbox tiles:

<div class="iframe-column"><iframe src="https://api.mapbox.com/styles/v1/mapbox/satellite-v9.html?title=true&access_token=pk.eyJ1IjoibWFwYm94IiwiYSI6ImNpejY4NDg1bDA1cjYzM280NHJ5NzlvNDMifQ.d6e-nNyBDtmQCVwVNivz7A#2/0/0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0"></iframe></div>
