| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Untangling a web (or net, if you will)...
For this assignment I chose to look at this very complicated line chart by the folks at [Icy Data](https://www.icydata.hockey/vizzes/attendance/17). The chart looks at average NHL attendance, by team, over a period of 7 seasons.
I chose to work on this chart because another one of my passions is hockey, and working with a measure like average attendance is a common thread between sports and the arts.


## My initial thoughts
The audience for this chart appears to be fellow hockey fans interested in learning the trends of their favorite team's at-home attendance over time. This data would also be significant for team ownership, staff of the venue, prospective season ticket buyers, local governments for the cities the teams play in, and the league executives. 
I found this chart to be very hard to read. A few things I noted were...

- The random use of color throughout the lines. The creator of this viz didn't even use the colors of the teams to connect the logos together.
- Speaking of the logos, they are eye-catching, but distracting seeing them every single year. Since the images are so large, we are also not getting to see all of the data points. It's a good thing that there is a filter to sort by team.
- There’s a lot of space at the bottom of the chart, maybe zooming in on the 10-24k range would spread out the lines a bit more.
- I am unsure if the chart is entirely accurate. The average attendance for the league overall seems to be a constant across the seasons? I don’t think this is accurate and I would want to find this statistic from another source.

Some recommendations I would make would be to isolate a specific team by using color and putting the rest of the teams in grey or color-code by division if it wouldn't look too messy. Another possibility would be to change the data we are looking at altogether to evaluate attendance by capacity percentage as attendance numbers alone can be misleading. A final recommendation I would like to experiment with before settling on a final visualization is using a different type of chart, like a stacked bar or column chart, to help identify those teams that consistently have packed houses.

## Trying things out

For my process, I ended up using Flourish to create several visualizations using the data I was able to obtain from the original viz and capacity percentages that [Wikipedia provides from ESPN Archives,](https://en.wikipedia.org/wiki/List_of_National_Hockey_League_attendance_figures). I ended up also needing another fan-powered [repository](https://hockey.sigmagfx.com/compseason/nhl/1011) to find all of the attendance averages for each season. I made sure to cite my sources for all of my visualizations for credibility, and to keep a reference for myself. 

First, I tested out changing the variable from attendance to capacity percentage. I thought that there may be enough variance between the percentages to help spread out the lines. For this chart, I was not able to get data for the 2010-11 season, so I omitted that season for this draft. Another thing I did pre-emptively to keep a constant throughout all of my drafts was to isolate one team throughout the process by color. I, of course, chose my favorite team, the Toronto Maple Leafs. Besides being my favorite, the Leafs are notorious for having an exorbitantly long waitlist for season tickets, making single-game seats a challenge to get. So I chose to look at if those season tickets are really being put to use each game!

I took the feedback I gave the original visualization and:
- zoomed in on the area where most of the data was
- provided a title and description that focused the reader on the piece of the data I wanted them to

<div class="flourish-embed flourish-chart" data-src="visualisation/15091432"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

I showed each of my visualizations to three people.

*A, hockey watcher, 20's*

- Can you tell me what you think this is?

Showing how full NHL arenas are each year. 
- What is your main takeaway from this graph?
I can't see Toronto after 2015. 
- Is there anything you find surprising or confusing?
I can't really tell where the other teams are just by looking. 
- Who do you think is the intended audience for this?
Probably Maple Leafs fans or people in team leadership
- Is there anything you would change or do differently?
Find a way to separate the lines or make each line at least show up every year

*B, classmate, not a sports person, 20's*

- Can you tell me what you think this is?

Measuring how full an NHL team's arena is compared to everyone else
- Can you describe to me what this is telling you?

I can't see the blue line all the way through, which means the data is getting overlapped somehow. The team seems to be doing well, but there are a few others at the top making it harder to read.

- Is there anything you find surprising or confusing?
A lot of the dots at the end are very close together, is there a way to tell them apart?
- Who do you think is the intended audience for this?
People who work for the team in blue
- Is there anything you would change or do differently?
Make the data more separate by team

*C, avid hockey watcher and Leafs fan, 50's*

- Can you tell me what you think this is?
Measuring how full the Scotiabank Arena is each season compared to the other teams
- Can you describe to me what this is telling you?
The Leafs are filling arenas consistently, but there are a lot of other teams at the top.
I can't see the line all the way through. 

- Is there anything you find surprising or confusing?
I can't see the line all the way through. What are the teams on the bottom?
- Who do you think is the intended audience for this?
Probably people with the Leafs organization or fans trying to sell tickets
- Is there anything you would change or do differently?
Make the data more separate by team

As you can tell, I got a lot of feedback to separate the teams, so that's exactly what I did next.

### Second Draft

For my second visualization, I decided to try a stacked bar chart. I think the strength of this visualization was that I was able to separate out each team just like my audience was asking for. The big glaring issue to me is that you need to do a lot of scrolling in order to actually see all of the data for each year, even after filtering out by season. Some other features that came back in for this visualization were the addition of the first season, since I have the data again, as well as the league average that I was able to have as its own set to compare with the rest of the teams. The last major change I made was tweaking the title a bit to clarify and specify that we were looking at teams selling in their OWN arenas. 

<div class="flourish-embed flourish-chart" data-src="visualisation/15089784"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

Since my three test subjects knew that I was going to be asking them the same five questions, I asked them to use them to just give me a summary of what they thought. 

*A*
This one looks very different from the last one! I can tell that you're still looking at attendance but changed from percentage to totals. Toronto seems to be performing a lot better from this chart! I sort of got the idea before, but now I really get it. I'm glad you were able to label all of the teams. The audience still feels the same for this chart, which feels like a good thing. I just don't really understand why the chart is so big. Is there a way to cut it down at all? 

*B* 
This looks like it's a lot more separated than the last one. You can really tell who did well overall over the period of time. It's kind of hard to tell the difference between the sizes of each segment, and it is also quite a challenge to remember all of the teams once you start scrolling down to the bottom. I think it's good to still have the total attendance in the axis otherwise I would have forgotten. Vegas only has one segment, and I didn't see their little dot on the first graph. Is it fair to keep them in?

*C*
This chart is a lot easier to read. It's nice to see that Toronto came out in the top 5. I can't really tell the difference between the sizes of each segment, but it's easier to distinguish the years compared to the lines that got very tangled. I notice that there is a league average now. Keeping Las Vegas in doesn't feel fair, they only played the one season so they're obviously going to be an outlier and they're not even your focus. 

Between this visualization and my final one, my goals were to:
- Cut Vegas from the visualization since they were such a clear outlier, and the reason isn't exactly apparent from just looking at the chart.
- Make the league average more distinct
- Make the bars closer to each other so the chart itself isn't so large, and the scale remains visible the whole time.
- Make the language in the title a bit more formal, as the audience seems to be skewing more towards team leadership than just fans.

  ## Final Visualization

  I finally settled on a stacked column chart. I feel like the column chart accomplishes a lot of the same goals as the bar chart, by accumulating the totals for each city over time, it allows the audience to gain a sense of the overall trend over the time period. For those who wanted to get more of a detailed look at each team's performance year-by-year, I added a row filter so the reader can see how each team is performing side-by-side compared to not only the team I chose to focus on, but the league average. 

  <div class="flourish-embed flourish-chart" data-src="visualisation/15090407"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
