# Data-Science-Volcano-Project

This project was made by two dear friends who had a question in mind:
Can we predict Volcano Eruptions? or atleast predict their scale of the eruption?

we"ll learn the answer dor this question in the future.

Some information:


DATA ACQUISTION:

We made a crawler which loads a webpage ("Global Volcanism Program") with a search query(just clicking on the search button :D) that gives back a table with the entire volcanic activity history (almost 10000 years back).

The crawler - using Selenium and BeautifulSoup - iterated through the table and acquired each eruption throughout the history for each volcano.
for every single row the crawler need to crawl through links and acquire the right data:

1)Volcano Name(duh)
2)Eruption type -  confirmed/unconfirmed/no evidence
3)Start Date - when it happened.
4)Max. VEI - the scale of the explosion.
5)Volcanic Region- yes. it exists... for research purposes only.
6)Country - research purposes
7)Volcano type- research purposes
8)Lat
9)Long
10)Summit



