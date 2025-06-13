# Exploring Hacker News Posts

## Introduction 
Hacker News is a site started by the startup incubator Y Combinator, where user-submitted stories (known as "posts") receive votes and comments, similar to reddit. Hacker News is extremely popular in technology and startup circles, and posts that make it to the top of the Hacker News listings can get hundreds of thousands of visitors as a result.

The original dataset can be found [here](https://www.kaggle.com/datasets/hacker-news/hacker-news-posts), but for this analysis, the data has been reduced from almost 300,000 rows to approximately 20,000 rows by removing all submissions that did not receive any comments and then randomly sampling from the remaining submissions.

## Data Description
Below are descriptions of the columns:
* id: the unique identifier from Hacker News for the post
* title: the title of the post
* url: the URL that the posts links to, if the post has a URL
* num_points: the number of points the post acquired, calculated as the total number of upvotes minus the total number of downvotes
* num_comments: the number of comments on the post
* author: the username of the person who submitted the post
* created_at: the date and time of the post's submission

Here are the first few rows of the dataset:
|id|title|url|num_points|num_comments|author|created_at|
|--|-----|---|----------|------------|------|----------|
|12224879|Interactive Dynamic Video|http://www.interactivedynamicvideo.com/|386|52|ne0phyte|8/4/2016 11:52|
|10975351|How to Use Open Source and Shut the F*ck Up at the Same Time|http://hueniverse.com/2016/01/26/how-to-use-open-source-and-shut-the-fuck-up-at-the-same-time/|39|10|josep2|1/26/2016 19:30|
11964716|Florida DJs May Face Felony for April Fools' Water Joke|http://www.thewire.com/entertainment/2013/04/florida-djs-april-fools-water-joke/63798/|2|1|vezycash|6/23/2016 22:20|
11919867|Technology ventures: From Idea to Enterprise|https://www.amazon.com/Technology-Ventures-Enterprise-Thomas-Byers/dp/0073523429|3|1|hswarna|6/17/2016 0:01|
10301696|Note by Note: The Making of Steinway L1037 (2007)|http://www.nytimes.com/2007/11/07/movies/07stein.html?_r=0	|8|2|walterbell|9/30/2015 4:12|



We are specifically interested in posts with titles that begin with either **Ask HN** or **Show HN.** Users submit Ask HN posts to ask the Hacker News community a specific question. Below are a few examples:
![image.png](attachment:f1411897-847c-43b7-afb7-98e76486f94c.png)

Likewise, users submit Show HN posts to show the Hacker News community a project, product, or just something interesting. Below are a few examples:
![image.png](attachment:bc430135-2d40-4bf9-a51d-0b3e8ef519c6.png)

We will compare these two types of posts to determine the following:

* Do *Ask posts* or *Show posts* receive more comments on average?
* Do posts created at a certain time receive more comments on average?
