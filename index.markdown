---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

#layout: home
#date: 2023-03-21 14:00:00 +0100
title: Vehicle thefts in San Francisco
---

<p>
       Over the past few years, San Francisco has experienced a high number of criminal incidents. The authorities made an effort to collect data on all recorded crimes that took place in the city and made it publicly available. The following investigation refers to the period 2003 to 2017 of this data. An initial inspection of the collected dataset indicates that there has been considerable fluctuations in the number of incidents in many of the 37 different crime categories during the years. In particular, the number of vehicle thefts in San Francisco had a significant change in the chosen period. Thus, our focus will be on examining and analyzing changes that have occured in this crime category.
       <br>
       In the early 2000s, San Francisco was struck by a surge in vehicle thefts. Cars parked on the streets were being stolen at an alarming rate resulting in frustrated citizens and increased workload for the police. However, there was a significant drop in occurrences starting 2006 which can be seen in figure 1.

</p>

<aside style='width: 50%'>
       <!-- <p style='text-align:center; font-size: 12px'>Occurrences of vehicle thefts in San Francisco from 2003 to 2017</p> -->
       <figure>
              <img src="/assets/calender_plot.png" width='100%' height='auto' alt="Calender plot of vehicle thefts in San Francisco from 2003-2017"/>
              <figcaption>Fig.1 - Occurrences of vehicle thefts in San Francisco from 2003 to 2017. Darker colors indicate a higher amount of vehicle thefts while lighter colors display a lower number. Interesting to see is that there is a significant drop from 2005 to 2006.</figcaption>
       </figure>
</aside>

<p>
       According to an article of the East Bay Times 
       <a href='https://www.eastbaytimes.com/2007/02/18/auto-thefts-in-state-decline-for-first-time-in-decade-2/'>
       (Auto thefts in state decline for first time in decade)
       </a> this is related to the increased use of security measures, like immobilizer systems which manufacturers started installing in new vehicles in this period.
       <br>
       An immobilizer system is a security feature that prevents a car from starting without the proper key. It uses a microchip embedded in the key that communicates with the car's onboard computer, allowing the engine to start only if the key is present. This made it much harder for thieves to steal cars, as they could not longer simply hotwire the ignition.
       <br>
       The impact of immobilizer systems soon became evident in the area. According to police data, vehicle thefts in the city dropped by more than 60% in the years following its implementation. This was a welcome relief for car owners, who no longer had to worry as much about their vehicles being stolen.

</p>

<p>
       Another method of prevention was focusing on districts with higher incidents.
       Figure 2 shows an interactive map of San Francisco and its districts. The amount of thefts is based on the years 2003-2017. Darker colors indicate higher occruences of vehicle thefts in an area.
</p>

<p>
       A visualization like this would have been extremely helpful for citizens and tourists to avoid leaving their car unattended in specific regions. It is shown that safer areas are typically neighborhoods with high pedestrian traffic and visible security cameras, as well as areas with strong police presence or important buildings such as ministries, embassies, town halls etc.
       <br>
       After the implementation of increased security measures like immobilizer systems, car break-ins became more and more popular in San Francisco and are still a very recent issue <a href='https://www.sfchronicle.com/news/article/san-francisco-auto-burglary-hot-spots-12756952.php?fbclid=IwAR3IF4jjp2ajAXWO80SvHfuTFviEiyF6tVOzJRDreWfT8xDKo4lIctct0v0.pdf'>
       (San Francisco’s auto break-in hot spots)
       </a>. 
       To see if there is a relation to former car theft regions we displayed the car break-in hotspots as black dots on the map. Two of these hotspots are in Northern and Bayview which are also districts with a high number of vehicle thefts. On the other hand two of them are in Richmond with a more moderate amount of thefts. At first glance at figure 2 you would say that the amount of car thefts is not equally distributed across the city and Ingleside seems to be the district with the highest amount of incidents. The same applies to Tenderloin with the fewest thefts, but it is also the smallest district. Hence, we need to look at the amount of car thefts related to the districts size to compare the ratio. This is shown in figure 3.
</p>

<figure style='width: 90%; margin-right: auto; margin-left:auto'>
       <embed 
              type="text/html" 
              src="/assets/vehicle_thefts_map_hotspots.html"
              width='100%'
              height="500"
       />
       <figcaption>Fig.2 - Occurrences of vehicle thefts in San Francisco from 2003 to 2017 in the different districts. Darker colors indicate a higher amount of vehicle thefts while lighter colors display a lower number. Black dots are hotspots of car break-ins.</figcaption>
</figure>

<p>
       Interesting patterns can be identified by looking at the interactive bar plot below. Some districts have a much higher relative frequency of vehicle theft than others, with one district in particular standing out which is Southern.
       <br>
       We decided to investigate further, looking at factors that might be contributing to the high rate of thefts in this particular district and found that the district has a high population density and a high percentage of rental properties, both of which are known risk factors for vehicle thefts.
       <br>
       Richmond appears to have a low relative frequency of car thefts. However, Point Lobos Avenue (seen as hotspot in figure 2) constitutes a major spot with an increased rate of thefts and break-ins throughout the years. The area around the avenue has large parking lots being out of sight of people's eyes. A supplementing factor on the increased theft in the Bayview district is beyond any doubt Illinois and Third Street in Dogpatch. As reported by both citizens and victims of car theft the area has become a popular nightlife destination where industrial backstreet runs and warehouses are located that provide free or relatively cheap parking spaces. The streets are becoming dark and quiet at night and thus vehicles can become an easy prey for lawbreakers.
       <a href='https://www.sfchronicle.com/news/article/san-francisco-auto-burglary-hot-spots-12756952.php?fbclid=IwAR3IF4jjp2ajAXWO80SvHfuTFviEiyF6tVOzJRDreWfT8xDKo4lIctct0v0.pdf'>
       (San Francisco’s auto break-in hot spots)
       </a>. 
       <br>
       To see the development of the amount of vehicle thefts in the districts over the years, figure 3 can be used by clicking on different years on the legend at the right.
</p>

<figure style='width: 90%; margin-right: auto; margin-left:auto'>
       <embed 
              type="text/html" 
              src="/assets/vehicle_thefts_ratio.html"
              width="100%"
              height="450"
       />
       <figcaption>Fig.3 - Relative frequencies of vehicle thefts in the districts of San Francisco from 2003-2017. The legend on the right shows how the ratio of vehicle thefts in the districts changed over the years. Click on certain years in the legend to disable them.</figcaption>
</figure>
