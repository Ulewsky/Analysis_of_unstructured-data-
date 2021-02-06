# Analysis of unstructured data


## Assignment nr 1
1. Find structured data (on Kaggle) but not Titanic and not Real Estate data (these sets are boring)
2. Use Pandas library: https://pandas.pydata.org/docs/
3. Find exciting facts about your data.
4. Be curious and ask questions to your data.
5. You should have at least 6 different analyses (questions to your data) + at least 4 different classic charts (pie/stacked/scatter/bar/hist etc.)


## Assignment nr 2

Visit the “Publications” section of the Hugo Steinhaus Center website (http:
//prac.im.pwr.wroc.pl/~hugo/HSC/hsc.html). Scrape the data on research
papers from that site and generate a cooperation network of authors in the
following way:

1. members of HCS are the nodes,
2. the size of a node is proportional to the number of papers co-authored by
the node,
3. a link between two nodes means a paper written together by the corresponding members,
4. a weight of the link indicates the total number of common papers.
Visualize the network (with names and link weights). Detect the connected
components.


## Assignment 3

1. Collect tweets published via Endomondo by people which (both sets should be analyzed):
* SET_1
  * Are from 3-4 major cities in US.
  * Contain hastags #GEO2020, #GE2020, #GeneralElection,
  #GeneralElection2020, #Election2020.
  * Are published between 2020-10-21 and 2020-11-05.
  * Only English language.
* SET_2
  * Collect tweets from 2 different thinking parties/people/tv station in the same period.

2. Save tweets into the file (cleaned data) - because requesting lots of tweets could block your account, besides that it takes a while to download it.

3. Analyze the SET_1 in case of:
  * Whole data.
  * Candidates (categorize tweets: cointains only Biden/Trump/both candidates).
  * Cities.
4. Things which should be checked:
  * Check the number of tweets/likes/retweets over time.
  * SET_1: Check if other hashtags are included in tweets (popularity)
  * SET_2: Check which hashtags are used?
  * Check the most popular words.
  * Check the sentiment of tweets.
  * Check the sentiment over time.
  * SET_2 when people tweets (which part of the day).
  * You can also create your own questions.
5. Beside of standard plots, please visualize sth on map.
6. Remember to comment your results.

## Assignment 4

Using Google YouTube API analyze two channels' data. You should investigate:

 1. Users stats
 2. Videos Stats
 3. Two selected video stats

Channels requirements:
 * Please select channels which are not new (has data) and publish videos not occasionally
 * For 2nd point, please analyze data for all users videos (e.g. Views in time)
 * For 3rd point, please select one video for each user and analyze it (e.g. In case of
comment sentiments)

Please provide the following information:
* Links to channels
* describe the channels published content (area)
* tell why you selected these channels
* tell why you compere selected videos
* indicate the differences and similarities between channels (in the analysis)

## Assignment 5
Download the novel “Around the world in 80 days” by J. Verne from the Project
Gutenberg website.

1. Find all cities visited by Phileas Fogg, the protagonist of the novel.
2. Find = use Python code **NOT WIKIPEDIA**
3. Draw the path of his journey on a world map.
4. Compare the results with Wikipedia and try to find the reason why your
code did not return all of them (you can adjust the code and be more
accurate).
5. Visualize the character mentions per page/chapter
6. Find the top 20 keywords in book/chapter - you can also check the most
popular words in case of part of the speech
7. Visualization sentiment per page/chapter (you can use different algorithms
for sentiment)
8. Visualize graph of co-occurrences (defined as mentions on the same
page).
