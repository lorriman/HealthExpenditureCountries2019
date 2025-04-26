# AI generated html/javascript survey of countries' health expenditure vs GDP per capita

Just playing around with AIs. Based on 2019 data from sources found by the AIs.

I wanted a dynamic web page with controls, buttons. It was quite a clunky experience, and the results are not so fantastic. Whatever data the two AIs fetched didn't agree with significant differences, but this was really about seeing what it would do for chart generation.

However, it's certainly useful to clearly see that the research these AIs do needs to be thoroughly checked. 

## view results

Grok 3 version: https://lorriman.github.io/HealthExpenditureCountries2019/healthExpenditureByCountry.html

Gemini 2.5 version : https://lorriman.github.io/HealthExpenditureCountries2019/googlesHealthExpenditure.html

## prompt

It took a few iterations. 

Generating so much html and javascript meant that refining the result was best served by getting the AI to clearly separate out distinct parts and data points in to distinct sections so that I could avoid regenerating the whole thing each time (which also uses up one's credits) and copy-paste just the affected code/html. 

Grok also needed correcting to keep the chart within the bounds of the view window (it made an infinite scroll chart, haha) as it didn't have enough common sense for that. 



