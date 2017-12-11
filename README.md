# Web Spider

Some web spiders including: Reddit and experience project.

There are two versions of Reddit spiders using Scrapy and Reddit API.

To run these spiders, some folders need to be created and the path name should be modified.

## Reddit API
There are three scripts in the folder of redditapi.

[(1)](redditapi/crawl_reddit.py) crawl the posts (including titles and text bodies) of subreddit.

[(2)](redditapi/comments.py) crawl the posts and comments.

[(3)](redditapi/gen_seq.py) get the sequences of comments.

## Reddit Scrapy
Scrapy is used to crawl the [posts](redditscrapy/spiders/reddit.py) and [comments](redditscrapy/spiders/comments.py).
XPATH and CSS are used to match specific information.

## Experience Project
Scrapy is used to crawl the posts from [Experience Project](http://www.experienceproject.com).
XPATH and CSS are used to match specific information.