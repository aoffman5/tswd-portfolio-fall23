| [home page](https://aoffman5.github.io/tswd-portfolio-fall23/) | [visualizing government debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Visualizing Government Debt

## What are we looking at?
This series of data visualizations represents the debt-to-gross domestic product (GDP) ratio for several countries around the world from 1995 to 2019. This ratio is often used to indicate a government's financial stability (or lack thereof). The OECD (Organisation for Economic Co-operation and Development) presents this data in four ways on its website. 

- A static bar chart that represents these ratios for a single year
- A line chart that a user can highlight specific countries on
- A table with year-by-year data of a country's debt
- A world map with dots of various sizes to indicate the size of a country's debt

### Bar Chart
I've attached the bar chart with 2019's numbers here for you to look at. I chose to disable the country highlights to focus on the overall form of the chart (also, because after playing around with it a little bit, I realized that the colors are arbitrary and just something meant to pull your eye). Another decision I made was to omit the OECD average and just focus on individual countries. *I tried to omit the OECD total from the bar chart, but was unable to do so. It is omitted in the rest of the visualizations.* I chose to do this because it added an extra non-country variable and because it wasn't something being measured each year. I think that if we had the OECD averages starting in 1995, I would have chosen to use it as a comparison tool (perhaps, to compare one continent or country's ratios to the average) The chart is sorted in a way that is predictable and easy to read, with the values being sorted in ascending order. With the graph's interactive component of being able to roll over a bar to get the country name and exact percentage of the country's ratio, the x-axis labels and gridlines on the y-axis are unnecessary. This bar chart would be most useful for comparing two countries at a point in time.

<iframe src="https://data.oecd.org/chart/7bh3" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/7bh3" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2019</a></iframe>

### Line Chart
If we want to look at a country's debt to GDP ratio over time, it would be more efficient to use a line chart showing the directional trends of the data over a few years. By creating a grid of line charts, we can isolate each country's data to avoid entanglement and highlight any anomalies with greater ease. The challenge with this dataset overall is that data is not present for each country for every year. 

A challenge that arises with the grid of line charts is that it's challenging to pinpoint exact values on the very small grid, but it's very useful for those who are visual learners and can analyze the shapes of each line to determine trends. For example, Japan is continuously trending upward throughout its line chart, while countries like Estonia and Luxembourg essentially flatline at ratios below 50%. Some countries with notable spikes include Greece at the end of the 2000's and Great Britain's 28% jump from 2008-2009. Many other countries have graphs that look like rolling hills, like Slovakia. 

A design choice I made was to turn the gridlines a light gray. I wanted them to still be present due to the overall size of the charts, but I did not want them to be prominent as they can be distracting.
<div class="flourish-embed flourish-chart" data-src="visualisation/14983815"><script src="https://public.flourish.studio/resources/embed.js"></script></div>


### My Visualization
For my data visualization, I chose to use a bubble chart, a variation on the scatter plot. I took inspiration from the world map visualization on the OECD site using dots of different sizes to indicate the size of a country's debt-to-GDP ratio. By having three variables (time, value, and the name of the country), we are able to create bubbles for each country. I used the country name on the x-axis to create separation between the countries, because otherwise, it would just be one large line. I chose to hide the names in the x-axis to avoid redundancy and limit eye travel. 

I grouped the countries by geographical region to assign colors to each of the dots. Since, as we established with the line charts, Japan is a consistent outlier, I wanted to highlight its region (East Asia and Pacific) by using black. Besides that, I chose to pair up the remaining six regions with colors based on geographic location, using a blue-to-orange gradient going from the Western Hemisphere to the Eastern Hemisphere. 

Three additional elements I used to highlight my data even further were the time slider feature, the use of labels, and row filters. First, I added a time slider to show all of the country data for a single year in one place. You can use the animation to go to a particular year of interest or to see certain dots grow or shrink over time. I set up my labels to only show labels for dots of a certain size, which helps your eye catch the countries with the highest ratio in a given year. Finally, I used row filters so, if the reader chose, they could filter the data by geographic region and have a clearer image of how countries in the same region are stacking up against each other. However, this feature is completely optional.

I think that bubble charts can be effective because they can measure the size of a variable in a very intuitive way for an audience. A larger circle = a larger variable. A challenge with bubble charts is that it can sometimes be clunky and distracting to have so many labels, especially when your dots are so minuscule. Thankfully, some of the regions only have one or two countries. Another challenge is without the addition of the time slider, it would be challenging to depict the passage of time with this sort of chart. 

<div class="flourish-embed flourish-scatter" data-src="visualisation/14984250"><script src="https://public.flourish.studio/resources/embed.js"></script></div>



