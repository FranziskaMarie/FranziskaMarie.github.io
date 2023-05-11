---
title: Evictions in NYC
description: New law during covid - Hotspot Neighbourhoods - Rent prices - Insight about people
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
       At first glance, anyone can detect that there has been a significant drop in evictions from 2020 onwards. This is related to a law that was enacted on March 7th 2020 helping to protect tenants that suffer financial hardship due to Covid-19. Tenants have to affirm in court that they have financial issues caused by the pandemic in order to stop the landlord from evicting them. This law was valid until the 15th of Janunary 2022 which is strongly noticeable in the distribution of figure 1. What is interesting is that there is still a rather low amount of evictions in 2022. 

</p>

<p>
       Looking at the period after the moratorium in figure 2, we can see that evictions are rising again but do not reach the level before Covid. This could be related to the fact that courts are overwhelmed with the floods of legal requests for evictions from landlords. “There are some evictions going through, but there are many inherent delays with the court system resulting in evictions occurring but not at the pace or the level they were prior”, reports a lawyer in NYC for an 
       <a href='https://gothamist.com/news/nyc-eviction-rate-continues-to-rise-since-ban-was-lifted-as-homelessness-surges'>article in the Gothamist</a>.
</p>

<p>
       <figure style='width: 40%; display:inline-block'>
              <embed 
                     type="text/html" 
                     src="/assets/distribution_years.html"
                     width='100%'
                     height="350"
              />
              <figcaption>Fig.1 - Occurences of evictions in NYC from Janurary 1st 2017 - May 10th 2023.</figcaption>
       </figure>
       <figure style='width: 40%; display:inline-block'>
              <embed 
                     type="text/html" 
                     src="/assets/after_moratorium.html"
                     width='100%'
                     height="350"
              />
              <figcaption>Fig.2 - Development of evictions in NYC since the moratorium ended due to Covid-19.</figcaption>
       </figure>
</p>


<h2>Hotspot areas</h2>
<aside style='width:40%'>
       <figure style='width: 100%; margin-right: auto; margin-left:10px'>
              <embed 
                     type="text/html" 
                     src="/assets/boroughs.html"
                     width='100%'
                     height="310"
              />
              <figcaption>Fig.3 - Ratio of evictions in boroughs in NYC Janurary 2017 - May 2023.</figcaption>
       </figure>
</aside>
<p>
       The distribution of evictions in the boroughs can be seen in figure 3. The Bronx with over 40% stands out with the highest number of recorded evictions. A more detailed look at this area is shown in figure 4. The interactive map displays the Neighborhood Tabulation Areas (NTA's) of New York City with the amount of evictions. Additionally we are displaying specific buildings with 10 or more evictions on the map, further investigation shows that the building with most evictions is a storage in Manhatten.

       The two main aspects that the research is focusing and trying to give a clear interpretation about, is firstly: which are the "hotspot" areas in the city and what is the justification behind that trend and secondly: what is the reason behind the eviction rates decreasing from 2017-2019.

       As far as the later is concerned, additional information should be retrieved in order to better justify this "trend". In this regard, housing data together with economic data are merged, only to depict the mean household income and how it is distributed over the years. After this inspection, it was founded that household income increases in this period, answering to some extent the reason why evictions have dropped. Adding up to this, one would be interested in viualizing the rent prices over the years. As such, the corresponding information was calculated and plotted, showing that rent prices are also following an upward "trend". This information though, contradicts the main findings that evictions are decreasing. At this point, it is necessary to provide more solid information on the economic state of New York in these years in order to explain eviction incidents. Thus, it was decided to delve into the unmployment rates on those years. After isolating the civilian labor force out of the total population from the supplementary economic dataset, the unemployment rates over the the years were showed. The results reveal that unemployment is decreasing from 2017 to 2019 and then it goes up again following the COVID-19 pandemic. Taking the above into consideration, it can now become more clear, at least to a certain extent,why there is a fall in evictions.

       The second aspect of this analysis is to search for "hotspot" areas through the city and analyze them further. As such, first thing is to categorize New York into boroughs and NTAs(neighborhood tabulation areas). New York city is divided into 5 boroughs, namely Manhattan, Bronx, Queens, Brooklyn and Staten island. After retrieving the relevant information, the corresponding ratio of occurrences of evictions compared to the population of each borough is plotted and investigated further. Although Bronx is 4th in rank in terms of population, it is standing out as the borough with the highest ratio of evictions in the examined years. For all the other four boroughs, the numbers are proportional. In particular, Brooklyn and Queens are the highest populated boroughs and come 2nd and 3rd in ranking of evictions, while Manhattan and Staten Island are the least populated boroughs but with the less recorded evictions too. In this regard, it is interesting to look upon Bronx and its characteristics as a borough. A relatively important information that can help us better interpret the augmented evictions in Bronx, is to search for and visualize the corresponding industries of each borough. The values are normalized based on the total civilian labor force that each borough has and thus, comparisons among the boroughs can objectively be performed. From the plot, someone can immediately point out that Educational services (healthcare, social) is by far the industry in which the majority of the population works and Bronx is once again the district with the highest values. However, scientific and management industry (both fields in which the average salary is escalated compared to other fields) has the lowest values in the Bronx borough. Furthermore, the finance and insurance sector, also takes its lowest value in Bronx, leading up to an overall estimate that Bronx is a Borough with "less" money compared to the other ones. In contrast, we can see that the fincance sector is dominating in Manhattan, something which does not come as a surprise since the financial district lies there. However, it confirms once more why the evictions are not in high degree in Manhattan.


       Another interesting information that could enhance our research about the boroughs and their corresponding eviction rates, is to find out about the percentages of ethnicity groups that reside in each borough. Thus, a first plot of the ethnicity groups in the city of New York had to be schemed. It appears like the city is mostly comprised of Caucasians, followed by Hispanic-Latino and then from African-Americans. Asian is the 4th ethnicity group in percentage while all the other ethnicities appear in a much lower extent.  The findings of the plotted distribution of all the ethnicity groups in all boroughs reveals some intriguing facts. In particular,  for Bronx, which is of immerse interest, Latinos and African Americans appear to be the majority while Caucasians are the minority of the Borough. Furthermore, Queens has a very high number of Asian people compared to other ethnicities in the borough while Staten Island which has the least evictions is mainly inhabited by Caucasians. Manhattan, which is relatively low in the rank of eviction occurrences, is also inhabited mainly by Caucasians. 

       Having the above in mind, it can be referred that the distribution of different professions among the boroughs can explain, at least to some extent, why evictions might be higher in Bronx compared to other districts. The information retrieved from the ethnicity groups residing in each district cannot provide us with an explanation or justification about eviction rates but it can display some interesting facts that could be relevant for another research topic. For example, based on the above findings, someone could enhance his/her knowledge on how the wealth is distributed among ethnicity groups in New York city, which are the main professions of each group and why does it happen that Hispanic-Latino and African Americans are working in lower-salary industries.
</p>
<p>
       More text with 
       <a href='https://hcr.ny.gov/covid-19-eviction-protections-tenants'>
       (link)
       </a> 
</p>

<figure style='width: 80%; margin-right: auto; margin-left:auto'>
       <embed 
              type="text/html" 
              src="/assets/evictions-map.html"
              width='100%'
              height="600"
       />
       <figcaption>Fig.4 - Interactive map of the NTA's in New York City showing the amount of evictions from 2017 - May 2023. Darker colors indicate a higher number of evictions. Black dots indicate more than 10 evictions in one building. The slider can be used to select a specific year.</figcaption>
</figure>
<figure style='width: 80%; margin-right: auto; margin-left:auto'>
       <embed 
              type="text/html" 
              src="/assets/evictions-acs-map.html"
              width='100%'
              height="600"
       />
       <figcaption>Fig.5 - Interactive map of the NTA's in New York City showing different factors from the ACS. Darker colors indicate higher amounts. Select a topic from the drop-down menu to explore the distribution over the neighborhoods.</figcaption>
</figure>
<br>
<p>
       If you want more information see our
       <a href='https://github.com/FranziskaMarie/Evictions-NYC'>
       explainer notebook
       </a>.
</p>
<figure>
              <img src="" width='100%' height='auto' alt=""/>
              <figcaption>Fig.1 - Figure text</figcaption>
</figure>

