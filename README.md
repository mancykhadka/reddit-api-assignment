# Reddit API Project (Gym/Fitness)
Student: <Your Name>

This project collects posts from r/Gymshark, r/bodybuilding, and r/Fitness.
I fetch hot posts and keyword search results (like "preworkout"), clean them,
and export everything to reddit_data.csv.

## How to Run
1. pip install -r requirements.txt
2. Add your Reddit API keys to reddit.env (template provided)
3. Run the notebook or reddit_code.py

## Output
reddit_data.csv (no index) with columns:
title, score, upvote_ratio, num_comments, author, subreddit, url, permalink,
created_utc, is_self, selftext, flair, domain, search_query
