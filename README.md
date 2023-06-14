# Ibd and Ibs
![Python shield](https://img.shields.io/badge/-Python-yellow?logo=Python) ![Jupyter shield](https://img.shields.io/badge/-Jupyter-white?logo=Jupyter) 
[![Reddit](https://img.shields.io/reddit/subreddit-subscribers/CrohnsDisease?style=social)](https://www.reddit.com/r/CrohnsDisease/)
[![Reddit](https://img.shields.io/reddit/subreddit-subscribers/IBD?style=social)](https://www.reddit.com/r/IBD/)
[![Reddit](https://img.shields.io/reddit/subreddit-subscribers/ibs?style=social)](https://www.reddit.com/r/ibs/)
[![Reddit](https://img.shields.io/reddit/subreddit-subscribers/UlcerativeColitis?style=social)](https://www.reddit.com/r/UlcerativeColitis/)

This is the thesis work for my graduation in Computer Science, University of Bologna.

# Table of Contents

- [Ibd and Ibs](#ibd-and-ibs)
- [Table of Contents](#table-of-contents)
  - [About the project](#about-the-project)
  - [Notes](#notes)
    - [Reddit Api](#reddit-api)
    - [Dataset of comments](#dataset-of-comments)


## About the project 

This repository represents the work for my university thesis.
The goal of the project is to discover if there is any correlation between the sentiment in subreddits about Crohn's Disease and COVID-19.

My work follows a previous one made by my thesis relator and another researcher.

## Notes

### Reddit Api

To use reddit apis is mandatory to register the script at [your reddit apps](https://reddit.com/prefs/apps). Registering you'll obtain the infos to access the api.
I suggest to collect the data in a file called `reddit_access.ipynb` and import its variables whenever necessary.

```
# ./reddit_access.ipynb

client_id=""
client_secret=""
password=""
user_agent=""
username=""
```

### Dataset of comments

The comments dataset is larger than 100Mb, that's the github's size limit.
You may contact me for the full dataset or just run the script `./crohn_scraping_comments.ipynb`.  
You'll wait a little bit...

