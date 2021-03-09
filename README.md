# Wordcloud

This project works on generating word clouds of News Title according to Sustainable Development Goals (SDG) score breaking days (outliers). Key words of News related to SDG can inform what happened during that specific days.

Here is the main workflow
![alt text](https://github.com/zwang752/Wordcloud/blob/main/Wordcloud.png)

Step 1, find outliers through observing SDG time series data of companies. This step locate which specific days we should focus.

Step 2, extract key words from news URLs and match their similarity to a specific SDG. (NLP is used)

Step 3, plot wordcloud to visualize key words.

![alt text](https://github.com/zwang752/Wordcloud/blob/main/Sample%20output.png)
