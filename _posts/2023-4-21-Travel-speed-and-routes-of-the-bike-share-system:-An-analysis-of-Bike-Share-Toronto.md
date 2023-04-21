---
title:  "Travel speed and routes of the bike-share system: An analysis of Bike Share Toronto"
mathjax: true
layout: post
---

![master/images/GGRC32_routing_workflow.png](https://zehuiyin.github.io/images/GGRC32_routing_workflow.png)

This project was a part of [GGRC32](https://utsc.calendar.utoronto.ca/course/ggrc32h3), an essential spatial analysis course taught by [Dr. Christopher D. Higgins](https://www.utsc.utoronto.ca/geography/christopher-higgins) in Winter 2023. It examined the Bike Share Toronto system and used the R5 routing engine to address the following two research questions.
-	RQ1. What are the travel speeds of cyclists in the Bikeshare Toronto System?
-	RQ2. To what extent do the existing bike lanes complement the Bikeshare Toronto System?
<!-- readmore -->

To answer these two research questions, I simulated the shortest cycling paths between every pair of Toronto bike-share stations using the OpenStreetMap road network and the R5 routing engine. I estimated the average cycling speed within the system by calculating the seasonal average cycling speeds at each station. I also created the estimated travel flow by aggregating the simulated paths and visually comparing them with the existing bike lanes in Toronto. The project results showed that the average travelling speed in the bike-share system was at least 12 km/h and that the existing bike lanes did not complement the bike-share system well.

You can find codes used in this project by clicking <a href="https://github.com/zehuiyin/travel_speed_and_routes_toronto_bikeshare" target="_blank">here</a>.

<embed src="https://zehuiyin.github.io/files/routing_toronto_bikeshare.pdf" width="100%" height="800px" />
<p style="text-align: left;">If the embedded PDF is not displayed properly, <a href="https://zehuiyin.github.io/files/routing_toronto_bikeshare.pdf" target="_blank">please click here.</a></p>
