# PyBer Analysis of Driver Data

## Overview of Project
The purpose of this project was to analyze a set of ridesharing data from several different towns and cities that fall under 3 location types (Urban, Suburban, and Rural). This data is used to determine total fare, drivers, fare per driver, and more specific to these location types.

### Results
<insert summary table>
As to be expected, the vast majority of rides and the majority of fares come from the 'Urban' areas, followed by 'Suburban' and then 'Rural'. The total number of drivers follows this trend, with 'Urban' areas having nearly five times the number of drivers as 'Suburban' areas. This pattern continuing with 'Rural' areas having over six times less drivers than 'Suburban' areas. This reflects in the average fare, with 'Rural' areas being the most expensive, followed by 'Suburban' and 'Urban'.

<insert graph>
Another interesting pattern emerges when analyzing 'Fare' by month. We can see that 'Urban' areas set the trend when it comes to 'Fare' peaks, with prices peaking several times starting in late February and continuing through March before peaking in April. 'Suburban' largely follows the trends set by 'Urban' but to a lesser degree, with a major peak in late February before falling off and not substantially rising until April. The most interesting data comes from the 'Rural' area which, with the exception of a late-February peak, largely follows it's own pattern when it comes to 'Fare' peaks. This could be due to the relatively-low amount of rides happening in this area, a quirk unique to the 'Rural' area, or some other as-yet unknown factor.

## Summary and Recommendations
In summary, we can see that the vast majority of activity is focused in the more populated 'Urban' areas, with steep dropoffs for 'Suburban' and 'Rural' respectively. There also seems to be larger trends with peaks in riders correlating to specific dates, although more data from a larger period of time is needed to confirm this. Based on these observations here are a couple of recommendations:

1.) Begin tracking how many indiviudals considered booking a trip, but later cancelled. Would be an indicator if price, or difficulty finding a driver, is leading to revenue loss. If so, instituting a program to incentivize some 'Urban' drivers to work in the 'Suburban' and 'Rural' areas may be worthwhile.
2.) Institute a 'fare scale' to automatically increase 'Fare' by a set percentage during peak hours.
3.) Raise costs per mile within 'Urban' locations, given the (generally) smaller distances and relatively lower average fare.