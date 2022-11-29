# Analyzing & Predicting YouTube Metrics & Text

#### Project for analyzing and modelling Youtube numerical (views, likes, comments) and textual (titles, tags, comments) data. 

## Original data:
#### 1. raw-video-stats.csv
  - Title: Video Title.
  - Video ID: The Video Identifier.
  - Published At: The date the video was published in YYYY-MM-DD.
  - Keyword: The keyword associated with the video.
  - Likes: The number of likes the video received. If this value is -1, the likes are not publicly visible.
  - Comments: The number of comments the video has. If this value is -1, the video creator has disabled comments.
  - Views: The number of views the video got.
#### 2. raw-comments.csv
  - Video ID: The Video Identifier.
  - Comment: The comment text.
  - Likes: The number of likes the comment received.
  - Sentiment: The sentiment of the comment. A value of 0 represents a negative sentiment, while values of 1 or 2 represent neutral and positive sentiments respectively.

## Processed data:
#### 1. videos-with-comments-aggr.csv
#### 2. comments-with-videos-stats.csv
#### 3. videos-with-comments-aggr-norm.csv

## Code, models, tables, & figures:
#### 1. preparation.ipynb
#### 2. analysis.ipynb 
#### 3. text-models.ipynb
#### 4. number-models.ipynb






