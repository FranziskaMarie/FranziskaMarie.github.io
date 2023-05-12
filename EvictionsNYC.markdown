---
title: Evictions in NYC
description: New law during Covid - Hotspot Neighbourhoods - Rent prices - Insight about areas
permalink: /posts/evictions-NYC
---

<p>
       Evictions have been a hot topic, especially in New York City since they enacted the 
       <a href='https://hcr.ny.gov/covid-19-eviction-protections-tenants'>Tentant Safe Harbor Act</a> 
       to protect tenants who were unbale to pay their rent during Covid-19. For this reason, what this new law involves and how eviction occurrences have been fluctuating over the recent years for New York City will be investigated in the following. The 
       <a href='https://data.cityofnewyork.us/City-Government/Evictions/6z8x-wfk4'>dataset</a> 
       contains information about evicted properties and can be found on the Open Data NYC website. Analytically, it contains information about performed evictions from 2017 until now (May 10th 2023) such as their geographic location, the executing marshals who performed them and information about the buildings is also provided (i.e. commercial or residential property). To expand the analysis and correlate it with other factors that can play a vital role on explaining why and where evictions are taking place, 
       <a href='https://www.nyc.gov/site/planning/planning-level/nyc-population/american-community-survey.page'>5-year-estimates</a>  
       from the American Community Survey (ACS) containing housing, economic, social and demographic data will be used.
</p>

<h2>Eviction rates during Covid-19</h2>

<p>
       At first glance, anyone can detect that there has been a significant drop in evictions from 2020 onwards (figure 1). This is related to a law that was enacted on March 7th 2020 helping to protect tenants that suffer financial hardship due to Covid-19. Tenants have to affirm in court that they have financial issues caused by the pandemic in order to stop the landlord from evicting them. This law was valid until the 15th of Janunary 2022 which is strongly noticeable in the distribution of figure 1. What is interesting is that there is still a rather low amount of evictions in 2022. 
</p>


<p>
       <figure style='width: 40%; display:inline-block'>
              <embed 
                     type="text/html" 
                     src="/assets/distribution_years.html"
                     width='100%'
                     height="350"
              />
              <figcaption>Fig.1 - Occurences of evictions in NYC from Janurary 1st 2017 - May 10th 2023. 
              Significant drop in 2020 due to moratorium.</figcaption>
       </figure>
       <figure style='width: 40%; display:inline-block'>
              <embed 
                     type="text/html" 
                     src="/assets/after_moratorium.html"
                     width='100%'
                     height="350"
              />
              <figcaption>Fig.2 - Development of evictions in NYC since the moratorium on the 1st of January 2022.</figcaption>
       </figure>
</p>

<p>
       Looking at the period after the moratorium in figure 2, we can see that evictions are rising again but do not reach the level before Covid. This could be related to the fact that courts are overwhelmed with the floods of legal requests for evictions from landlords. “There are some evictions going through, but there are many inherent delays with the court system resulting in evictions occurring but not at the pace or the level they were prior”, reports a lawyer in NYC for an 
       <a href='https://gothamist.com/news/nyc-eviction-rate-continues-to-rise-since-ban-was-lifted-as-homelessness-surges'>article in the Gothamist</a>.
</p>

<h2>Rent prices, Household Income, Unemployment</h2>
<aside style='width:30%'>
       <figure style='width: 100%; margin-right: auto; margin-left:10px'>
              <embed 
                     type="text/html" 
                     src="/assets/unemployment_rate.html"
                     width='100%'
                     height="250"
              />
              <figcaption>Fig.3 - Unemployment rate in NYC 2017 - 2021. Decreasing from 2017 to 2019 and afterwards going up due to Covid-19.</figcaption>
       </figure>
</aside>
<p>
       We also see a decrease in eviction rates from 2017 to 2019. In this regard, we looked more in detail at housing and economic data. It was found that the household income increases by 13.2% in this period, answering to some extent the reason why evictions have dropped. Adding up to this, one would be interested how the rent prices developed over the years and they are also following an upward trend increasing by 11.2%. So the household income increases faster than the rent prices which could make it easier to pay rent. At this point, it is necessary to provide more solid information on the economic state of New York City in these years in order to explain eviction incidents. Thus, it was decided to delve into the unmployment rates on those years. The unemployment rate is decreasing from 2017 to 2019 and then it goes up again following the Covid-19 pandemic (see figure 3). Taking the above into consideration, it can now become more clear at least to a certain extent, why there is a decrease in evictions.
</p>


<h2>Hotspot areas</h2>
<figure style='width: 80%; margin-right: auto; margin-left:auto'>
       <embed 
              type="text/html" 
              src="/assets/evictions-map.html"
              width='100%'
              height="600"
       />
       <figcaption>Fig.4 - Interactive map of the NTA's in New York City showing the amount of evictions from 2017 - May 2023. Darker colors indicate a higher number of evictions. Black dots indicate more than 10 evictions in one building. The slider can be used to select a specific year.</figcaption>
</figure>
<br>
<aside style='width:40%'>
       <figure style='width: 100%; margin-right: auto; margin-left:10px'>
              <embed 
                     type="text/html" 
                     src="/assets/boroughs.html"
                     width='100%'
                     height="310"
              />
              <figcaption>Fig.5 - Amount of evictions in boroughs divided by housing units in NYC Janurary 2017 - May 2023.</figcaption>
       </figure>
</aside>

<p>
       New York city is divided into 5 boroughs, namely Manhattan, Bronx, Queens, Brooklyn and Staten island. After retrieving the relevant information, the corresponding ratio of occurrences of evictions compared to the total of housing units of each borough is plotted and investigated further. Although Bronx is 4th in rank in terms of population, it is standing out as the borough with the highest ratio of evictions in the examined years (figure 5). For all the other four boroughs, the numbers are proportional. In particular, Brooklyn and Queens are the highest populated boroughs and come 2nd and 3rd in ranking of evictions, while Manhattan and Staten Island are the least populated boroughs with least recorded evictions too. In this regard, it is interesting to look upon Bronx and its characteristics as a borough. A relatively important information that can help us better interpret the augmented evictions in Bronx, is to search for and visualize the industries most people work in for each borough. This information can be related to the income and economic situation. The values are normalized based on the total civilian labor force that each borough has and thus, comparisons among the boroughs can objectively be performed. From figure 6, someone can immediately point out that educational services, which also includes healthcare and social assistance, is by far the industry in which the majority of the population works including the population of the Bronx. However, the Bronx has the lowest amount of people working in scientific and management positions, both areas in which the average salary is comparably high. Furthermore, the finance and insurance sector, also has its lowest value in the Bronx, leading up to an overall estimate that people living in the Bronx earn "less" money compared to the others. In contrast, we can see that the fincance sector is dominating in Manhattan, which is not a surprise since the financial district lies there. However, it supports once more why the evictions are not in high degree in Manhattan.
</p>
<p style='margin-right: auto; margin-left:auto; text-align: center'>
       <img src="/assets/industries.jpg" width='80%' height='auto' alt=""/>
       <figcaption>Fig.6- Distribution of poeple in NYC working in different industries per borough (standarized)</figcaption>
</p>
<p>
       Another interesting information that could enhance our research about the boroughs and their corresponding eviction rates, is to find out about the percentages of ethnicity groups that reside in each borough. It appears like the city is mostly comprised of Caucasians, followed by Hispanic-Latino and African-Americans. Asian is the 4th ethnicity group in percentage while all the other ethnicities appear in a much lower extent.  The findings of the plotted distribution of all the ethnicity groups in all boroughs in figure 7 reveals some intriguing facts. In particular for the Bronx Latinos and African Americans appear to be the majority. Furthermore, Queens has a very high number of Asian people compared to other ethnicities while Staten Island, which has the least evictions, is mainly inhabited by Caucasians. Manhattan, which is relatively low in the rank of eviction occurrences, is also inhabited mainly by Caucasians. 

</p>
<p style='margin-right: auto; margin-left:auto; text-align: center'>
       <img src="/assets/ethnicities.jpg" width='80%' height='auto' alt=""/>
       <figcaption>Fig.7 - Distribution of ethnicities throughout the boroughs in NYC (standarized)</figcaption>
</p>
<p>
       Having the above in mind, it can be referred that the distribution of different professions among the boroughs can explain, at least to some extent, why evictions might be higher in the Bronx compared to other districts. The information retrieved from the ethnicity groups residing in each district cannot provide us with an explanation or justification about eviction rates but it can display some interesting facts that could be relevant for other research topics. For example, based on the above findings, someone could enhance his/her knowledge on how the wealth is distributed among ethnicity groups in New York City, which are the main professions of each group and why does it happen that Hispanic-Latino and African Americans are working in more lower-salary industries.
</p>

<h2>Other factors</h2>

<p>
       To be determined of why there are so high differences in evictions in NYC, we need to look at many factors that could have an influence. Unfortunatly we cannot discuss all aspects of the ACS data in detail in this article. Nevertheless, we selected possibly related factors and display them on the map in figure 8. We encourage to click the drop-down button and find potential correlations to the distribution of evictions yourself! If you want further information see also our
       <a href='https://github.com/FranziskaMarie/Evictions-NYC/blob/main/ExplainerNotebook.ipynb'>
       explainer notebook
       </a>.
     
</p>

<figure style='width: 80%; margin-right: auto; margin-left:auto'>
       <embed 
              type="text/html" 
              src="/assets/evictions-acs-map.html"
              width='100%'
              height="600"
       />
       <figcaption>Fig.8 - Interactive map of the NTA's in New York City showing different factors from the ACS. Darker colors indicate higher amounts. Select a topic from the drop-down menu to explore the distribution over the neighborhoods.</figcaption>
</figure>


