# Newbie-Bot

Many subreddits have daily/weekly threads where beginners can ask basic questions. `Newbie-Bot` reads previous questions and directs users towards an answer when no human has given a response.

Initially I will be focusing on a single community.

# General Pipeline

  1. Scrape data from reddit.
  1. Clean data by removing e.g., non-questions, non-answers.
  1. Use NLP to identify the sentiments of each question.
  1. Use similarity metric to direct users to similar questions asked in previous posts.
  
# Future Looking

  - Interactive console application for offline Q & A
