# goingviral

# Background and Motivation
Twitter (https://twitter.com) is social network, real-time news media service, and micro-blogging service where users can use text, photos, and videos to express moments or ideas in 140-characters or less. These 140-character messages are called "tweets.” According to Twitter’s website, millions of tweets are shared in real time, every day. Registered users can read and post tweets, favorite other people’s tweets, retweet other people’s posts, favorite tweets, and follow other accounts. Unregistered users can read tweets from public accounts.
In today's day and age of Twitter, popularity is measured in hearts, retweets, follows, and follow-backs. What posts get popular over time? What seems to resonate most with people? Do positive or negative sentiments invite more engagement? In this project, we use Twitter's publically available archive of content to like to examine some of the shared characteristics of popular posts, including length of post, visual content, positivity, negativity.

# Initial Questions
How does the distribution of retweets and hearts vary for a post depending on the time of day when tweet is created?
How does positive and negative sentiment affect popularity?
What Tweets do we think will become popular?

# Method
This data is publicly available via the Twitter Static API that gets queries based on specific parameters. We limited the data set to look at tweets within a specified period of time. We are storing the data in CSV files for now. To reduce file-sizes, we will try to have multiple CSVs so that we don't load too much data into memory. If data exceeds computer memory, we will consider AWS/SQL database alternatives.

# Analysis
