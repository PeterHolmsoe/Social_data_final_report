<p align="center">
Link to website: https://peterholmsoe.github.io/Social_data_final_report/
</p>

# Visualization of the covid-19 outbreak in the USA.

The Corona virus has spread around the world. The first case of the virus was first reported in the Wuhan a city located in the Hubei provence in China. A we live in a globalised world, the virus has had the perfect conditions for spreading around the world. The first person who died in the U.S. was a 58-year old man February 29. 

This article will give the reader an idea of how the virus has spread throughout the United States. 

The first plot illustrates the distribution of dead people in the different US states. Of course this can give a twisted view of how the different states are handeling the virus. It's clear that the state of New York has the most cases of COVID-19. In the next plot, the data has been normalized based on the population in the states, and it gives a better picture of how "good" the different states are handeling the virus outbreak. 


![alt text](https://raw.githubusercontent.com/PeterHolmsoe/Social_data_final_report/master/death.png)
![alt text](https://raw.githubusercontent.com/PeterHolmsoe/Social_data_final_report/master/ratio.png)

Again, we see that New York is the worst, however, many factors are involved, eg. population density and poverty. These factors can be in explored in the following interactive map. 

<p align="center">
<iframe src="https://demo-map-us.herokuapp.com/pop-notebook" width="800" height="525"></iframe>
</p>

The test strategy is high in New York (NY), this makes sense since they are the worst affected state. However, it's interesting to notice how California (CA) performes many tests even though the spread of the virus isn't that severe in that state.  

![alt text](https://raw.githubusercontent.com/PeterHolmsoe/Social_data_final_report/master/posneg.png)


Lets look at how the development of infected people has spread in the different states. 

<iframe src="https://giphy.com/embed/YPz8U1fwR64d5RHAkl" width="960" height="512" frameBorder="0" class="giphy-embed" allowFullScreen></iframe>

We see how New York suddenly goes very dark, and how the virus quickly can get out of control. In the following two plots, we see the development of tests performed in New York and California since the first outbreak was detected. California has learned from New York, and we see in the graph how political initiatives to boost the testing is made with the steep increase in testing around day 73, 86 and 91.   

![alt text](https://raw.githubusercontent.com/PeterHolmsoe/Social_data_final_report/master/NY.png)
![alt text](https://raw.githubusercontent.com/PeterHolmsoe/Social_data_final_report/master/CA.png)


<p align="center">
<iframe src="https://trond123fred.herokuapp.com/interactive_map" width="800" height="525"></iframe>
</p>

Se dette

# Test

When talking about flattening the curve, the idea is that it is desired to minimize the number of Corona infections such that the health care capacity can handle the extra load that COVID-19 is causing. It is wellknown that an epidemic like the corona virus grows exponentially in the beginning before it starts to slow down. As humans, it is hard to wrapping your head around exponentially growth as it is hard to realize how fast an epidemic grows and locate when the growth might start to slow down. One of the big questions people might wonder is if each state is lowering the number of infections over time or that the growth of COVID-19 is still exponential. This question alone is hard to answer from simple plots like the ones seen previously in this article, which is the main motivation behind the following graph:


<p align="center">
<iframe src="https://covid-development.herokuapp.com/myapp2" width="750" height="525"></iframe>
</p>

This graph gives insights into whether of not each state is starting to get the infection under control or if the COVID-19 is still on the path of exponential growth. There are a few main ideas behind this plot that help indicate if the exponential growth is ending:
1.	New weekly confirmed cases of COVID-19 are plotted on the vertical axis and total confirmed cases is plotted on the horizontal axis. Both axes are on a logarithm scale as this is the natural scale for exponential growth. Hence a straight upward going line represents weeks of exponential growth for each state. The vertical axis expresses the growth rate of COVID-19, which is the important take away here, as a decreasing growth rate indicates the exponential growth is ending.
2.	Time is not on any of the axes. An epidemic does not care about which date it is. The pattern of an epidemic mostly comes down to the total number of infection and the growth rate (new weekly infections), as the number of new cases is proportional to the number of existing cases. Instead time is expressed using the timeline slider to get an idea of the progress of the epidemic on a week to week basis.
3.	If the weekly new cases start to go down, the line starts to plummet which indicates that a state has started escaping exponential growth and improvements are being made. This is typically a results of public health regulations, such a social distancing and isolation has taken effect.
4.	Predictions using machine learnings techniques are made two weeks into the future in order to predict if a state is making improvements. These predictions can give insights into whether or not public health guidelines are actually working or if the different states should relax or tighten regulations in order to combat COVID-19.

One can compare different states current status on COVID-19 using this graph. It can be seen that a state like New York was following an exponential growth of COVID-19 the first 6 weeks of infections, but it has seen improvements in the last couple weeks and the prediction two weeks into the future also predicts that the exponential growth is slowing down. One can also look at Hawaii which was on an exponential path the first 4 weeks of the epidemic but was super effective at reducing the number of new infections as the line starts to plummet. Many states such as Iowa, California, Arizona and others still seems to be on the path of exponential growth and should probably consider tightening the public health regulations.	



# Test
<p align="center">
<iframe src="https://cover-death.herokuapp.com/myapp3" width="750" height="525"></iframe>
</p>

# Gifs

<iframe src="https://giphy.com/embed/JoIOHEOUrV1OZugEMv" width="960" height="512" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/JoIOHEOUrV1OZugEMv">via GIPHY</a></p>

<iframe src="https://giphy.com/embed/UTBLHQds90s9QMk5HL" width="960" height="512" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/UTBLHQds90s9QMk5HL">via GIPHY</a></p>


<iframe src="https://giphy.com/embed/UrnyxJmrg5x8qKJ2XY" width="960" height="512" frameBorder="0" class="giphy-embed" allowFullScreen></iframe>

