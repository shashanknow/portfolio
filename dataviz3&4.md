# FBI IC3 Crime Report Data Visualization Critique & Redsign

## 1️⃣ Find a data vizualization 

This is an interesting visualization provided by the FBI which gives us information about major crimes reported in the US and how they changed in the last 5 years (2017 - 2021). While it is useful for law enforcement and the media, it also informs general citizens and encourages them to take steps to protect themselves.

<img width="567" alt="Screen Shot 2022-11-14 at 8 23 53 PM" src="https://user-images.githubusercontent.com/117224363/202082282-8cb5c086-f9d8-438f-9942-e467b080035d.png">

Source: [2021 Internet Crime Report, Pg 8.](https://www.ic3.gov/Media/PDF/AnnualReport/2021_IC3Report.pdf)

## 2️⃣ Let's critique the viz 🧐

### What worked well 👍🏽

- The chart is very complete because it has all necessary information you want to relay to the audience like Top 5 crimes, their count per year and an informative title. 
- It is quite useful for people to know Top 5 crimes to watch out for and how many people are affected. 
- The data can be considered 100% truthful and reliable as it is provided by the FBI. 
- The graph did a good job of informing the audience of the trend for a particular type of crime through the years. 
- Once learned, the darker color makes you think of recent years and lighter colors make you think of many years ago. The numbers next to the bars are informative as well of the count.

### What did not work so well 👎🏽

- The chart is not very perceptible because it is not easy to compare different crime types for a particular year and there is no x-axis. 
- There is no distinction except the size of the bar to draw attention to Phishing. 
- Readers are accustomed to read time left to read, reading it from bottom to top is not very intuitive. 
- The categories are not used properly and can be eliminated by using text inside the bars. The Aesthetics are bad and it looks like black and white chart that is tilted 90 degrees. 
- The audience is not engaged enough because their eyes are darting back and forth between the bars and the legend. Also, there are no links to information about crimes to help them learn more about how to protect themselves.

### What would I do differently 😇

- I would tilt the graph so that bars become vertical and I would also add a y-axis with a Number of crimes label. 
- I would group the crimes by years in the x-axis and color code the crimes. 
- I would put an informative sub-heading and talk a little about crimes that are steadily rising. I would also try to highlight Phishing by using a shade of red.

### Intended Audience 

- General Public
- Law Enforcement
- Media

### Score on Stephen Few's [Data Visualization Effectiveness  Profile](http://www.perceptualedge.com/articles/visual_business_intelligence/data_visualization_effectiveness_profile.pdf)

![Screen Shot 2022-11-15 at 11 40 09 PM](https://user-images.githubusercontent.com/117224363/202085376-a3b156ed-fc4a-4a4e-901f-392b3582552d.png)
![Screen Shot 2022-11-15 at 11 40 25 PM](https://user-images.githubusercontent.com/117224363/202085386-78facf0e-82d8-462a-81ce-386af5f6f8cf.png)

## 3️⃣ Sketching a new solution ✍🏽

### Let's look at the new design

- **Chart Style**: I let go of the stacked bar-chart and instead used a line chart to show change in reported crimes for different types of crimes.
- **Title**: I changed the title to include a secondary title that informs readers to look out for Phishing because it's growing out of proportion!
- **Categories**: I removed the year based categories and used crime types instead. 
- **Axes**: I added an x-axis with years on it and a y-axis with the number of reported crimes.
- **Color**: I used different colors for different crimes and I particularly chose red to show just how alarming the phishing problem is. I also made the phishing line a little bolder than the rest to draw the viewer's attention.

### The First Sketch 🖼

![Assignment 5](https://user-images.githubusercontent.com/117224363/202324256-cca65d46-8c97-4738-905f-48cf79034af9.jpg)

## 4️⃣ Test the solution 🤝

### Interview 1: Data Analyst, 25

- _Q_:  _What do you think the chart is trying to convey?_
- _A_: _It’s trying to tell me how number of different types of reported crimes have changed over the years. Phishing particularly stands out._
- _Q_: _Did you feel any confusion? If yes, what confused you?_
- _A_: _Not confusion but the numbers were too heavy, I would rather look at the percentage change along with rough numbers._
- _Q_: _What do you wish was in the visualization to get the message better?_
- _A_: _I wish I could see what overall change in crime was i.e. all types combined._
- _Q_: _Who do you think is the intended audience for this?_
- _A_: _Just general citizens._

### Interview 2: Student - Music Major, 22

- _Q_: _What do you think the chart is trying to convey?_
- _A_: _Out of the top 5 crimes mentioned in the chart, phishing has had a massive increase over the years in comparison to other crimes._
- _Q_: _Did you feel any confusion? If yes, what confused you?_
- _A_: _Based on the secondary title,  I only think of phishing in the chart, but the main title says Top 5 crimes so I would want to see values for them as well in the beginning._
- _Q_: _What do you wish was in the visualization to get the message better?_
- _A_: _The initial stats for all crimes. A percentage increase because the numbers are too big. Final percentage change in 5 years. Numbers are hard to remember._
-  _Q_: _Who do you think is the intended audience for this?_
- _A_: _It’s relevant to general public to raise awareness towards phishing. I can see this visualization useful in a corporate setting to stop phishing attacks on their employees._

### What patterns in the feedback emerge?

- The numbers are scaring people.
- Change in percentage is particulary useful to viewers.
- The title is not that great

### What did you learn from the feedback?

- People tend to shut out big numbers and focus even more on the visual.
- Big titles are not great.
- People care about percentage changes more than absolute difference.

### Design Changes 

- Put percentages next to phishing points.
- Remove all big scary looking absolute numbers and write rough figures, for e.g., 114729 to 114K.
- Make a better focused title.
- Maybe add an overall trend line.

## 5️⃣ Build the solution 🔧

<div class='tableauPlaceholder' id='viz1668659536706' style='position: relative'><noscript><a href='#'><img alt='5 Most Reported Crimes in the last 5 years, Phishing Grows Exponentially ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Fi&#47;FinalAss34&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='FinalAss34&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Fi&#47;FinalAss34&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>
<script type='text/javascript'>
var divElement = document.getElementById('viz1668659536706');
var vizElement = divElement.getElementsByTagName('object')[0];
vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
var scriptElement = document.createElement('script');
scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

### Changes made from the sketch

After going through the interview answer, I was convinced that I made the right decision going with a line chart as it was much more perceptive and intuituve.

- I changed the numbers inside the chart to percentage change from last year
- Tweaked the title to be much more clearer and simpler
- Changed the color palette so that Phishing is bright red and the other categories are softer colors to draw more attention towards phishing.

### All about the new data viz... 🙏🏽

- I chose a line chart because it is so vivid in describing the trend of simething. Compared to the original data, the audience can now fully grasp the gravity of the situation,

- My redesigned viz shows how different crime types grew in the last 5 years and you can even see what how they compared against each other in a particular year. Focus has been more on the phishing side.

- What I attempted to do differently was to try to answer the questions that pop into your mind when you hear about a reported crime getting worse as effectively and quickly as possible. The categories were right infront of me and what better than line charts to show trends in time.





