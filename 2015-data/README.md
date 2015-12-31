README

This repository contains several files with year-in-review data for 2015 on Reddit.com. Each file's name gives a decent indication of its contents, but a quick readme is still always good practice . . . and I guess I should probably follow that sort of thing in public repos.

Many of the datasets make a note that they not include mobile apps, which should be listed as a caveat when discussing the data, as it seems to be more and more frequent for heavy users to use mobile apps. For example, see the drop in "total" pageviews without a corresponding drop in any indicators of heavy use (voting, submitting, commenting). We'll be in a better position to actually report this data in 2016.

Contact:
Justin Bassett
/u/Drunken_Economist
justin@reddit.com

2015-accounts-created-by-day.csv
	date, num_accounts
	number of newly registered accounts each day of 2015

2015-comments-by-day.csv 
	date, num_comments
	number of comments posted each day of 2015

2015-flair-assigned-by-day.csv
	date, num_flair
	number of link flair assignments each day of 2015, does not include flair which is later unassigned

2015-pageviews-by-country.csv
	country, pageviews
	number of pageviews by country in 2015. Sampled from Google Analytics data; not gospel

2015-posts-by-day.csv
	date, num_posts
	number of posts created each day

2015-subscriptions-by-day.csv
	date, num_subscriptions
	number of subreddit subscriptions by day. Note that new accounts are not, by default, actually subscribed to any subreddits. Instead, they are simply displayed the default set, although it appears functionally the same. As soon a user changes their subscription status to any subreddit (either subscribing to a non-default or unsubscribing from a default), their entire set of subreddits are recorded as subscriptions. In other words, creating a new account and subscribing to any non-default will add 52 to this total (51 defaults + 1 non-default subscriptions created)

2015-subreddits-created-by-day.csv
	date, num_subreddits
	Number of subreddits created per day. Note that we had a really annoying subreddit-creation spam problem at the beginning of the year, so there's a ton of noise before 2015-02-26

2015-top-20-gilded-comments.csv
	num_gilds, comment_link
	The most-gilded comments of 2015, ordered by number of gilds

2015-top-20-gilded-posts.csv
	num_gilds, post_link
	The most-gilded posts of 2015, ordered by number of gilds

2015-uniques-by-day.csv
	date, uniques
	Unique visitors to reddit by date. Does not include mobile apps

2015-unqiues-by-month.csv
	year, month_num, month_name, pageviews
	Unique visitors to reddit by month. Does not include mobile apps