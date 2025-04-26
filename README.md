# AI generated html/javascript survey of countries' longevity vs health expenditure % GDP per capita

Just playing around with AIs. Based on 2019 data (ie. pre-covid) from sources found by the AIs.

I wanted a dynamic web page with controls, buttons. It was quite a clunky experience, and the results are not so fantastic. Whatever data the two AIs fetched didn't agree with politically significant differences (see note on that below), but this was really about seeing what it would do for chart generation.

However, it's certainly useful to clearly see that the the AIs' research needs to be thoroughly checked. 

## view results

Grok 3 version: https://lorriman.github.io/HealthExpenditureCountries2019/healthExpenditureByCountry.html

Gemini 2.5 version : https://lorriman.github.io/HealthExpenditureCountries2019/googlesHealthExpenditure.html

## prompt

It took a few iterations. 

Generating so much html and javascript meant that refining the result was best served by getting the AI to clearly separate out code parts and data points in to distinct sections so that I could avoid regenerating the whole thing each time (which also uses up one's credits) and copy-paste just the affected code/html. 

Grok also needed correcting to keep the chart within the bounds of the view window (it made an infinite scroll chart, haha) as it didn't have enough common sense for that. 

## data differences

The exercise was inspired by a chart on facebook showing absolute dollar denominated expenditure on health expenditure with the USA far outspending everyone else for a worse death rate. But more meaningful is a comparison by percentage GDP per capita. Well, Grok had the USA as the outlier, like the chart on facebook, but Gemini had it about the same as Germany and Portugal. One makes a political point the other doesn't. I haven't followed this up to find out the truth. 



