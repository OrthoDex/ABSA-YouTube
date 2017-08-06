# ABSA-YouTube
Aspect Based Sentiment Analysis (ABSA) of YouTube Comments!

# Overview
This follows from my work on my [undergrad project ](https://github.com/Orthodex-Development/Minerva) for Aspect Based Sentiment Analysis. YouTube Analytics is great but it does not provide a facility for tracking viewer sentiments about a video, specifically which aspects of the video do viewers have strong sentiments about. In this project, I run ABSA on the comments thread for [Sirav Raval's](https://github.com/llSourcell) awesome YouTube [video](https://www.youtube.com/watch?v=si8zZHkufRY).

Data gathered using the YouTube Data API's [commentThreads.list](https://developers.google.com/youtube/v3/docs/commentThreads/list) function.

# What It does
In one line:
Data -> Cleaning -> Feature Extraction -> Pruning -> Frequent Feature Selection -> Sentence Extraction -> Sentiment Analysis!

# Usage
Download these dependencies using pip:
 - TextBlob
 - matplotlib
 - seaborn
 - nltk (download the nltk Stop Words corpus by running nltk.download() in a python shell.)

Run the notebook by typing ```jupyter notebook``` in the terminal to run the code in a popup browser. If you don't already have jupyter, download it [here](https://jupyter.readthedocs.io/en/latest/install.html).

# Future work
 - Run TF-IDF to extract important terms from the data.
 - Use scikit-learn [Feature Extraction](http://scikit-learn.org/stable/modules/feature_extraction.html#feature-extraction) tools.
 - Replace TextBlob Sentiment Scoring with a Deep Learning model.
