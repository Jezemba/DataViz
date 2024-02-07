## Introduction to the Data

The data is on a post by Time Use on a special issue exploring how people spend their time during 24 hours across multiple countries (https://ourworldindata.org/time-use#who-do-we-spend-time-with-across-our-lifetime). It majorly asks the question of how activities daily differ across countries. The data has information on a breakdown of people's daily activities, the amount of time spent on each activity in minutes, and the associated country for each daily activity. 14 categories are tracked in the dataset as shown below. 

1.	Paid work
2.	Education
3.	Sleep
4.	Care for household members.
5.	Housework
6.	Shopping
7.	Other Unpaid work
8.	Personal Care
9.	Eating and Drinking
10.	Sports
11.	Attending Events
12.	TV & Radio
13.	Seeing Friends
14.	Other Leisure

These categories are further grouped into 9 categories that are displayed on the chart below. This chart is the target of this page’s redesign activity.


![image](https://github.com/Jezemba/DataViz/assets/98770734/184db015-7f76-4768-81b8-5c8a02f7e0c5)


## Data Visualization Critique

The chart from the website has a few key sticking features that were initially observed. The first feature was the title. From the title it is initially seen that the chart shows a breakdown of the time of individuals from varying countries. I loved that the legends were close to the datapoint that they were representing making it easy to follow as I scanned across the graph. The legends also were color-coded which helped simplify the understanding of different groups. The stacked horizontal chart was also left aligned with the paid work making it easy to see which country spent the most amount of time working than others. The font of the text that was chosen was good as it made it easy to read from afar and there were no contrast issues with the text color of bar colors. 

Some features of this chart could also be improved. One of the first improvements includes standardizing the time unit. The graph uses both hours and minutes, and it is confusing because hours are easier to understand, especially if the minutes are so large which is the case for the paid work and total leisure. The category of paid work is also confusing because the maximum reported time does not reach the time allotted for a regular 8-hour workday. The author did not try to clarify if the breakdown indicates that people work at most 5 hours a day even though they might be employed for longer. A good way to fix this issue is to include clarification in the subtext of the plot because (At least for the US) less than 8 hours does not seem sufficient. Another improvement that I will make is the condensing of the segments. While the authors did do some of this from the initial 14 categories in the dataset to the 9 categories on the graph, it is still too many confusing categories and color grouping. For example, one could argue that eating and drinking could be part of enjoyment or personal care so giving different colors to these categories raises more questions on what those colors mean. I would simplify the groups to 4, Paid Work, Unpaid work, Sleep, and Leisure. This eliminated the confusion and footnotes can be added to the breakdown of each category. 
Some other improvements include ranking the activities based on size or importance. It is unclear if the author is trying to emphasize the paid work but the color choice of red and the sorting based on the paid category draws one's attention to that, but the title does not confirm if that was the intent making it confusing. I would either pick another representation like a waterfall chart with the simplified three categories so that there is a baseline to compare each category because it is difficult to know which country has the most unpaid work or the most sleep with no baseline. Adding a time scale to the x-axis at the bottom could also clear up some text if the details of the exact minute do not need to be exactly known. 

## Wireframe Solution

While the initial chart displays a lot of information and I initially made critiques to redesign the chart with the same information, I went with the approach of introducing a story aspect to the data to make targeted modifications based on the story that I wanted to tell from the data. The interesting thing in this chart to me was the amount of time that was spent on unpaid labor. I know that it has been shown that the unpaid labor market disproportionately affects women (also referenced in this article) more than men so I wanted to use this data to see if these disparities exist among countries.
The initial idea was to use some sort of simplified stacked bar chart for unpaid work in different countries but that seemed too simplistic and does not compare with the paid work that they still do during the day which is needed to compare how much work done in a day is paid.

![image](https://github.com/Jezemba/DataViz/assets/98770734/e03d9bf6-6c85-43f6-b0eb-693247d70d3e)

The second idea included using lines to represent the amount of time spent in a day based on the country. This idea will be further refined to include information on the countries and hours.

![image](https://github.com/Jezemba/DataViz/assets/98770734/2e528d00-0609-415c-a435-3f8a420709c4)

![image](https://github.com/Jezemba/DataViz/assets/98770734/6238818d-49e7-4664-8aa3-66ac74097611)

This refined sketch was used to elicit feedback during the class activity. The feedback given about the sketch was that the categories were too many and that it would be difficult to represent all the countries. I was suggested to start with just the top five countries based on unpaid work. They liked the idea of a line graph and agreed with the removal of the sleep section which skewed the graph because it was a higher number and was not relevant in communicating the story. I was also advised to only use color to point out countries of interest and standardize the timescale to hours.

## Revision 2

Based on this feedback I reduced the number of countries from 33 to 16 which reduced the clutter in the line graph. I was also able to simplify the lines to straight lines to mimic a slope line architecture between these three-time points. To better distinguish between countries, I added some color coding to the countries to group them based on the continents. The colors chosen were distinct to show a separation of categories. So, I went with the three primary colors and the gray to call out four continents. 

![image](https://github.com/Jezemba/DataViz/assets/98770734/afdfce0c-4894-41ac-91f4-cbfb435d90a2)

I used this digital mock-up to get additional feedback from 4 people and found that the countries were still too many as it was difficult to read. All participants could not understand the true meaning of the graph. One participant misunderstood unpaid work as employers not paying employees and said that she was outraged that companies did this. Another participant did not understand what unpaid work meant and was confused about the term. This prompted me to take steps to clarify the terminology used in the Title and the meaning of unpaid work. Feedback was also asking questions about why some countries were missing like countries in Africa. Across the board, people found it too cluttered to read the labels and follow the lines and did not understand what data the graph was trying to represent. They did like the color categories except gray because it made Australia and New Zealand obscure. Many little things were suggested such as changing gray to another color, changing unpaid labor to unpaid work for consistency, etc. But from speaking to multiple people without the initial graph as a reference and with the initial graph as a reference, people couldn’t understand what I was trying to communicate. 
I realized that I had overthought the slope graph and lost the meaning of the message I was trying to communicate and the trends that I wanted people to find and be able to tell apart in the optimization of a visually pleasing visual. Trying to explain my idea in the context of this plot was difficult for me and required a lot of backstories which defeats the point of this style. So, the final revision was story-centered.
In one statement, I wanted people to understand that some countries such as Mexico spent most of their hours a day working while most countries in Europe spent most of their day on leisure activities. I also wanted to let people know that high unpaid labor is bad because it could mean that people do not have enough time to work to earn money. I cannot communicate my full story because I do not have an average income for these countries so I can only communicate that some spend more time working than relaxing and some of that work is unpaid.

## Final Revision

This final revision simplifies the design based on the feedback from the in-class activity and the peer review process. Although most people liked the continent category colors, I removed the continent color categories to convey the idea of the change in time spent. I used one color to highlight countries that had less available time for leisure activities because of a rise in unpaid labor. I got feedback that the countries were too close together and because the time for most of them was similar I couldn’t scale it in a way that wouldn’t involve skewing the y-axis but removing 0-2 hours which could lead to a perception of data manipulation. This led me to switch to a rank-based system to better compare the countries and still allow users to understand the trends in the data and the countries with the greatest and least unpaid labor time spent and leisure time spent. I also included a topic that emphasized the duration of the time spent when data was collected and what unpaid labor means which were critiques that I received. I also added a call out as an example to understand how to read the chart using Mexico. I changed the font to the Tableau Light Font for a more cleaner look but all other defaults were kept in place because it worked with the data. 
I spent a significant part of this assignment trying to figure out the slope chart and found some videos (listed below) to convey my idea. While I would have loved to also highlight the text labels that show the red trends, I couldn’t figure out how to do that on Tableau. Given more experience and time I would have worked to implement that.

<div class='tableauPlaceholder' id='viz1707276393879' style='position: relative'><noscript><a href='#'><img alt='Drop in Available Time Spent During the DayAverages of minutes per day from time-use diaries for people between 15 and 64. Unpaid Labor includes elderly care, child care, housework, etc. Leisure includes seeing friends, watching TV, etc. ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Un&#47;UnpaidandLeisureTime&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='UnpaidandLeisureTime&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Un&#47;UnpaidandLeisureTime&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1707276393879');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

### Video Resources
1. https://www.youtube.com/watch?v=k0EiW4IJvrI
2. https://www.youtube.com/watch?v=CBH-OA-99AM

