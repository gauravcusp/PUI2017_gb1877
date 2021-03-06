## Review of bs3639's Visualization Plot

![](https://github.com/gauravcusp/PUI2017_gb1877/blob/master/HW9_gb1877/uber-ridership.png "Uber_plot")

According to Ben's decription for the plot, this plot gives us the ridership by hour for August & Sept 2014. 

### Review

CLARITY--
As the bins of the plot are too small, the change of colour is not noticeable. Only the drastic change such as blue to green is comprehensible. Also, the description suggests that there is spike at 9AM and 5PM but for most of the plot I can see blue bins for these timings. One thing that strikes me is the ridership around midnight is comparitively very high while its extremely low at around 6PM, when one can assume people use Uber the most for their commute.

ESTHETIC--
The blurriness of plot distracts me from the content its trying to present. Other than the points I discussed about above, the graph pretty much describes the change in ridership as per the hour of the day. 

HONESTY--
The plot does not entirely show perfect description of what one would assume about Uber. The sudden spikes at midnight and 3-6AM is somewhat weird and extremely low at evening rush hours makes me dooubt the data.

### Suggestions
Instead of the plot Ben created, I would have preferred a frequency plot which would give point and line plot of rides per day with dip and rise for each hour.

![](https://github.com/gauravcusp/PUI2017_gb1877/blob/master/HW9_gb1877/Monthly_Subway-App-based_Ridership.png "Ridership")

Courtesy[https://www.nycedc.com/blog-entry/transportation-trends-nyc]

# FBB feedback

Hi Gaurav,

in your comments and suggestions you fail to notice that Bens plot provides one further dimension compared to the plot you attach: his plot is 3D, your sugested plot would need to have >1500 points on the x axis to describe all this information, and the various periodicities (week, day) would likely be harder to spot: one thing that is obvious in Ben's plot is that weekends have a distinctly different behavior than week days, which is lost in a time series plot like the one you propose. 

Other points you make: the "blurrines" is fine because it helps honesty: the alternative would be to smooth the bins, but this would add a free variable (how do you smooth). 

I agree that the plot does not indicate spikes at 9AM and 6PM - although it indicates different behavior for these times in weekdays and weekends

10/10
