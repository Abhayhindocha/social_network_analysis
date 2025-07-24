# social_network_analysis
🐦 Twitter Social Network Analysis using Mentions
This project extracts recent tweets for a given hashtag (e.g., #AI) using the Twitter API v2, stores relevant data in MongoDB, and constructs a directed weighted graph using user mentions to analyze social interactions.

🚀 Features
✅ Fetches recent tweets using a hashtag query

✅ Extracts author_id and @mentions from each tweet

✅ Stores tweets in MongoDB (twitter_sna > tweets)

✅ Builds a directed graph where:

Nodes = Twitter users

Edges = Mentions (weighted by frequency)

✅ Visualizes top active users using NetworkX and Matplotlib

📦 Requirements
Python 3.x

Tweepy
Pymongo
NetworkX
Matplotlib
Install dependencies:
bash
Copy
Edit
pip install tweepy pymongo networkx matplotlib
🧪 How it works
Tweets with the selected hashtag are fetched.

All @mentions from tweets are extracted.

Data is stored in MongoDB to avoid duplicate API calls.

A graph is built and visualized showing mention patterns.

📊 Sample Output
Top 30 users are plotted in a graph showing who mentions whom, with edge thickness representing frequency.<hr>
