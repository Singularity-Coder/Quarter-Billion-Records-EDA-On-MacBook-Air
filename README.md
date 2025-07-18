# Quarter Billion Records EDA On MacBook Air (Work In-Progress)
Exploratory Data Analysis on 1/4 Billion records of Reddit data done on MacBook Air with 16GB RAM.
* [EDA on Laptop](https://github.com/Singularity-Coder/Quarter-Billion-Records-EDA-On-MacBook-Air/blob/main/README_local.md)
* [EDA on Google Cloud (BigQuery)](https://github.com/Singularity-Coder/Quarter-Billion-Records-EDA-On-MacBook-Air/blob/main/README_remote.md)

## Dataset 5 files
* [Reddit Comments 2015 dataset](https://archive.org/download/2015_reddit_comments_corpus/reddit_data/2015/)
* The data is in the JSONL or single object per line format. 
* Total records: 529,610,375 which is about 530 million or 1/2 billion records.


## Sample JSONL reddit comments 2015
```json
{
  "score_hidden": false,
  "name": "t1_cnas8zv",
  "link_id": "t3_2qyrla",
  "body": "Most of us have some family members like this. *Most* of my family is like this.",
  "downs": 0,
  "created_utc": "1420070400",
  "score": 14,
  "author": "YoungModern",
  "distinguished": null,
  "id": "cnas8zv",
  "archived": false,
  "parent_id": "t3_2qyrla",
  "subreddit": "exmormon",
  "author_flair_css_class": null,
  "author_flair_text": null,
  "gilded": 0,
  "retrieved_on": 1425124282,
  "ups": 14,
  "controversiality": 0,
  "subreddit_id": "t5_2r0gj",
  "edited": false
}
```