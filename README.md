# Wordcloud

This project works on generaing word clouds of News Title according to Sustainable Development Goals (SDG) score breaking days (outliers). Key words of News related to SDG can inform what happened during that specific days.

Here is the main workflow
![alt text](https://github.com/zwang752/Wordcloud/blob/main/Wordcloud.png)

For step 1, we found outliers through observing SDG time series data of companies. This step locate which day we are looking into.

For step 2, we extracted key words from news URLs and matched their similarity to a specific SDG. (NLP was used)

For step 3, we plot wordcloud to visualize key words.

![alt text](https://github.com/zwang752/Wordcloud/blob/main/Sample%20output.png)
