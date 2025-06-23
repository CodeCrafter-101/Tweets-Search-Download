# Tweets Search / Download Tool
- A Python-based utility that allows you to search, filter, and download tweets based on keywords, hashtags, date ranges, or user handles. Useful for research, data analysis, or sentiment studies using Twitter data.

## Definition
- Tweets Search/Download is a project designed to fetch tweets from Twitter using search queries or filters, and optionally save them for offline analysis. It enables developers, researchers, and analysts to collect real-time or historical tweet data programmatically — without manual browsing or copying.
## Requirements 
- ````
  !pip install tweepy
  ````
- ````
  !pip install pandas
  ````
## Tips
You can modify the query to:
- Search by hashtag: `#AI`
- Filter by user: `from:elonmusk`
- Exclude retweets: `-is:retweet`
- Filter by language: `lang:en`
- Filter by date: (only supported via `start_time` and `end_time` params)

## Project Structure
![image](https://github.com/user-attachments/assets/e6607092-9b5a-4121-84a8-dd5bfc33dbdb)

  
