# characterizing-online-attitude

**CKIDS Characterizing Online Attitudes: code repo**

[Project Website](https://cllei12.github.io/)

- Histogram of users commenting on multiple posts (submissions)

- Topic model of comments (gensim)

- Timeline (by year)
  - Users posts by year
  - Comments in submissions by year

- How long people are engaging
  - Locations in comments, spaCy NER
  - How many users mention a location
  - Histogram of locations by user starting from 0

- Gender from comments (Michael)

Structure

```
.
├── README.md
├── data-exploration\ 
│   ├── Histogram.png
│   ├── Sentiment_scores.png
│   ├── USC_DataFest_2022.ipynb
│   ├── negative_wordcloud.png
│   └── positive_wordcloud.png
└── topic-model
    ├── lda_8.html
    └── topic_model.ipynb
```

