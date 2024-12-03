---
permalink: /visualisations/
title: Project Visualisations
layout: visualisations
---
# Outline

## NYC Crash Data

We intend to explore and display the data, as well as discover what the main outside causes for accidents are. From the initial data, we can display an overall view of every crash that has happened by location. This data view implies a map, by only plotting the crashes and allowing us to guess where streets and intersections are, and was our first view into the data available.

![plot-one]


We intend to create a dynamic (animated) graph that visualises the data by following a specific road in NYC and plotting the crashes that happened around it. Maybe adding cartoony toy trucks in the background to disguise the gruesome reality of what we are actually visualising... Or angry truckers...

![plot-two] 
![plot-three]


Next, we want to analyse the reasons behind crashes. There are multiple factors that are recorded in the dataset, and more that we can assume and analyse outside of it.

<br>

Let's start by taking the recorded factors that went in to the crashes, by visualising the most common vehicle types and contributing factors, as recorded on the scene:

(Note: use tree map?)

![vehicle-crash-types]

![vehicle-crash-factors]


Even with this information, we can assume outside factors have an impact on the crash rates. Let's take data from the same area, NYC, which analyses the weather and plot the crashes in clear weather against that in rain:

![crashes-without-rain]

![crashes-with-rain]



It seems that rainfall does not affect the crash occurrence by much, although we expected it to have an effect. This suggests that there are much more influentual causes behind these accidents, such as the time of day which shows a very clear trend in this plot, and it may also suggest that humans tend to be more aware and careful when the conditions are not the best, negating the effects of the weather this way. It might also be an indicator that in NYC one simply does not move fast enough to let road conditions determine the frequency of crashes, and we may need to look elsewhere for outlying causes.

<br>
<br>

Plan to add graphs:
- Study whether holidays and festivities affect accident rates;
- Crashes per year and how they changed (animated slideshow);
- Interactive graphs by time: select between day of week, time of day, and year;
- Interactive map where can zoom into various famous areas and view more detailed breakdown of info (like with road);
- Types of accident per location / density of vehicle types;
- Possibly initial visualisation of weather data for weather exploration part

Add more features, not graphs:
- Introduction to theme of vehicle crashes in a more lighthearted tone: comic style and use of light imagery for decoration;
- Final thoughts: what we have learned so far and answer question on how best to stay safe from accidents in NYC.


[plot-one]: {{ "/assets/images/nyc_crashes_plot.jpg" | relative_url }}

[plot-two]: {{ "/assets/images/nyc_crashes_plot_road.png" | relative_url }}

[plot-three]: {{ "/assets/images/nyc_crashes_plot_road_zoom.png" | relative_url }}

[vehicle-crash-types]: {{ "/assets/images/common_vehicles.png" | relative_url }}

[vehicle-crash-factors]: {{ "/assets/images/common_factors.png" | relative_url }}

[crashes-without-rain]: {{ "/assets/images/crashes_in_clear_days.png" | relative_url }}

[crashes-with-rain]: {{ "/assets/images/rain_crahes.png" | relative_url }}
