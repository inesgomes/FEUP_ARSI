# FEUP_ARSI
Project accomplished during the Social Networks and Information Analysis class. 

Exploration of an Youtube Trending Dataset linking videos with the same tag.

This content follows the book 'Networks, Crowds, and Markets: Reasoning About a Highly Connected World', David Easley and Jon Kleinberg.

### Youtube Trending Videos Dataset

Top dayly Youtube Videos from United States, Great britain, and Canada collected between November 2017 and May 2018.
(https://www.kaggle.com/datasnaek/youtube-new)

#### The Statistics
video_id, trending_date, title, channel_title, category_id, publish_time, tags, views, likes, dislikes, comment_count, thumbnail_link, comments_disabled, ratings_disabled, video_error_or_removed, description


### Run:
```
cd Notebooks
jupyter notebook
```

### Folders
 - **OriginalCSV's** : directory that contains the original CSV's downloaded from kaggle 
 - **Created CSV's** : directory with new csv's created so that it can be imported at gephi
 - **Visualization Data** : directory that contains a collection of images generated at gephi
 - **GephiFiles** : files to be imported at gephi with the work developed during this semester
 - **Notebooks** : files with data analysis and csv creation
 - **Notebooks-html** : HTML version of notebooks in case of not having the *Jupyter* or *Anaconda* software installed. 


### Some Inspiration
https://www.kaggle.com/ankkur13/sentiment-analysis-nlp-wordcloud-textblob/notebook

https://www.kaggle.com/donyoe/exploring-youtube-trending-statistics-eda

https://www.kaggle.com/quannguyen135/what-is-trending-on-youtube-eda-with-python

https://www.kaggle.com/jpnewmenji/k-means-clustering-youtube-eda/code