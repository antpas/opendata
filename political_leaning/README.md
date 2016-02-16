### Data Sets ###

### Twitter User List By Political Leaning  ###

As part of our research on classifying political leaning from tweets, we run experiments on users that were listed on [Twitter Lists](https://dev.twitter.com/rest/reference/get/lists/list) as **Democrat** or **Republican**. We identify users as follows: 
   - **DEMOCRAT** - is a user on a list having 'democrat', 'democratic party', or 'democrats' in it's title 
   - **REPUBLICAN** - is a user on a list having 'republican', 'republican party', or'republicans' in it's title
   
This list includes 27,130 users, with roughly equal number of **Democrat** and **Republican** users. The list file contains Twitter usernames and the political leaning for these user. The tab-separated file can be downloaded [here](https://github.com/klout/opendata/blob/master/political_leaning/twitter_users_by_political_leaning.tsv). 

The tweets of these users sampled over a period of 3 months between Oct 12th 2015 and Jan 12th 2016 is used for our experiments.
