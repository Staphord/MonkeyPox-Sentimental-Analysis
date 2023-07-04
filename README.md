# MonkeyPox-Sentimental-Analysis
In our study of Monkeypox sentimental analysi, we  extracted tweets using the Twitter API and Tweepy library. Tweepy is a python package for accessing Twitter API that allows developers to access Twitter content, such as tweets, retweets, and timestamps. A python script was used to search for all the tweets related to the keyword “#monkeypox”. All text that met our criteria was extracted and stored in a comma-separated values (CSV) file. We considered a total of five features for our analysis: text, timestamps, author, source, and language. Google Translate API was used to translate all non-English tweets to English.

We collected over 500,000 tweets between July 2022 and September 2022; however, after preprocessing, we were left with 107,000 unique tweets which is expressed in [**MonkeyPox Dataset file**](https://github.com/Staphord/MonkeyPox-Sentimental-Analysis/commit/9a45cb4c8dd434b8f32e35ac78d16a5b8cc503bd#diff-8e36ab8d620db36b2f03ea01752665fb7bb7b0a93e7311db669ab870ee870b91)
We collected over 800,000 tweets between July 2022 and December 2022; however, after preprocessing, we were left with 237,000 unique tweets which is expressed in [**Emotion file**](https://drive.google.com/file/d/1MKHcdXyT8ks3zWCydvxETer6oUS3WoNV/view?usp=sharing)

If you are using this dataset for the experiment then please cite the following paper
1. Bengesi, Staphord, et al. "A machine learning-sentiment analysis on Monkeypox outbreak: An extensive dataset to show the polarity of public opinion from twitter tweets." IEEE Access 11 (2023): 11811-11826.
   [Paper link](https://ieeexplore.ieee.org/abstract/document/10036414)
2. Olusegun, Ruth, et al. "Text Mining and Emotion Classification on Monkeypox Twitter Dataset: A Deep Learning-Natural Language Processing (NLP) Approach." IEEE Access (2023).
   [Paper Link](https://ieeexplore.ieee.org/abstract/document/10129946)

