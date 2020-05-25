---
title: Data Visualization Exam 2020
date: "2020-05-01T22:12:03.284Z"
description: "Hello World"
---

# Introduction

Data Visualization is an extremely powerful tool that enables you to convey a message to the reader. As someone who studies Data Science, who gets overly excited about watching a number approach one, i have found it difficult to convey exactly why that is to friends and family, However after converting this endless stream of numbers into a visually pleasing representation, it becomes much more interpretable for the average person.

While this tool can be incredibly valuable to shed some light on difficult topics, it can also easily be abused to convey messages that are favorable for the publisher, either by creating misleading visualizations and thus discrating the consumer from valuable insight, or by creating factually wrong representations of the data. Data Visualizations are often taken at face value by the general public but it is vital to always be skeptical when introduced to a new visulization.

## Data
The data chosen from this project was my Google data downloaded via Google's Takeout tool. This data included location history, search history, youtube videos watched, youtube videos commented, youtube subscriptions, purchases through the Google store, Google Assistant conversations, amongst others. 

I do realize this choice of data is a lot more interesting to me than it is to you, but i hope you can still enjoy the visualizations they enabled.

A theme throughout these visualizations is my choice of more visually pleasing visualizations over functionality. This choice was made due to the data at hand does not contain any opinionated data. I will make sure to either state when these choices are made, or show alternatives for each of them.

The data arrived in two formats; either as a JSON or HTML file. Extracting the right data was an iterative process as the formatting for the individual files varied. 

Exploring the data, we see the first logs appear on May 2nd 2013 and continue until now. Plotting this graph we first see a spike around the period i purchased an Android phone, and a drop when i purchased an iPhone. Furthermore splitting the data into types of logging, we see the main source of logging with an android phone was from tracking location. 

<iframe src="https://eu-west-1a.online.tableau.com/t/datavisualisationanddatadrivendecisionmakingspring2020/views/Logging_v3/Dashboard2/hjbo@itu.dk/Public?:showAppBanner=false&:display_count=n&:showVizHome=n&:origin=viz_share_link&:embed=yes" width="1000" height="827" frameborder="0"></iframe>

<iframe src="https://flo.uri.sh/visualisation/2546372/embed" width="1200" height="900" frameborder="0"></iframe>


### Location History


Given the temporal aspect of the data, various visualizations was made where this extra dimension was utilized. From the location data, a map was visualized to both show general trends, and trends over time. The choice of a simple map was based on keeping the attention on the data, and not to the surroundings. A consequence of this choice is that a certain amount of knowledge about Copenhagen is required to get full value from the visualization, however, based on my knowledge on the target audince of this graph, it felt like the appropriate choice. 

After countless attempts of embedding this album, it did not seem to wanna play ball, so i hope this link will do.

<a href="https://imgur.com/a/XzlF7jF">https://imgur.com/a/XzlF7jF</a>

### Youtube

To further explore the trends occuring throughout time, the views for each Youtube channel was visualized through a racing bar chart. This chart type has the advantage of utilizing the extra time dimension, and due to the fast moving pace of the graph, it has potential to attract the attention of the reader compared to other choices. Besides from this advantage and being visually pleasing, it should be considered more as a gimmick than a viable option. Since we have data that is constantly moving, it is hard to gain any deeper insight into the data. A more reliable, but certainly not as eye catching, choice would be to either visualize the same data though an interactive dashboard as such:

<iframe src="https://flo.uri.sh/visualisation/2544074/embed" width="1200" height="900" frameborder="0"></iframe>



<iframe src="https://flo.uri.sh/visualisation/2544331/embed" width="1200" height="900" frameborder="0"><script src="https://public.flourish.studio/resources/embed.js"></script></iframe>

Or create a stacked bar chart.

### Google Assistant

The remaining data that seemed viable options for creating good visualizations was the Google Assistant data, and the Search History data. 

Given the logging of my conversations with Google Assistant, each command was categorized and given a color label respectively, and plotted as a "Packed bubbles" map. Again, from a purely practical point of view, this would not be the first choice since humans are poor at comparing sizes of circles (and angles). A treemap, or a plain old bar chart would be more practical. 

<iframe src="https://flo.uri.sh/visualisation/2545213/embed" width="1200" height="900" frameborder="0"><script src="https://public.flourish.studio/resources/embed.js"></script></iframe>

### Seach Queries

Finally we have the youtube search history. To filter out stop words, the TF-IDF score was calculated for all words and ranked accordingly. The visualization of choice for this data was the treemap. It provides a good overview of the data and is easier to compare than the packed bubbles presented previously. To amplify the differences between the importance of words, the score was used to determine both the area used and the opacity of the color. 

<iframe src="https://flo.uri.sh/story/367595/embed" width="1200" height="900" frameborder="0"></iframe>

### Conclusion

In conclusion i have not utilized the Google Suite very productively.

### Resources

![](ColorScheme.png)


![](tools.png)


### Appendix

<blockquote class="imgur-embed-pub" lang="en" data-id="a/XzlF7jF"><a href="//imgur.com/a/XzlF7jF"></a></blockquote><script async src="//s.imgur.com/min/embed.js" charset="utf-8"></script>