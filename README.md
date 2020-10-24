# Examining the relationship of UK stock exchange and public sentiment 📉

This repository contains part of the code I wrote for my dissertation, presented for my postgraduate degree. 
</br> For this project, I gathered both social media data related to the Covid-19 pandemic and financial data to examine the relationship of the UK stock exchange and the public sentiment in the light of a crisis. The data were pre-processed and converted to time-series and Python was used for sentiment analysis, Granger causality analysis, and predictive modelling.

### Abstract 📃

The goal of this paper is to examine the relationship between the public sentiment and the UK stock exchange during a crisis (coronavirus). More specifically, this study assesses whether the sentiment for the pandemic has predictive power over the stock market. To analyse this relationship, 1.679.116 Twitter posts related to coronavirus were mined from 23rd January 2020 to 29th June 2020, while stock exchange data were obtained from Yahoo! Finance, for the same period. Following previous research, sentiment analysis was implemented to classify tweets in 3 classes (positive, negative, neutral). Initially, a rule-based dictionary approach model was used in a hand-labelled dataset but its poor performance led to the development of machine learning sentiment analysis models. The sentiment labels were aggregated and converted to sentiment polarity time-series. The relationship between the polarity and stock exchange was initially examined using Granger causality analysis. It was further assessed by comparing the performance of sentiment-enhanced machine learning models to their baseline counterparts, which used only historical value features for the prediction of stock market movement. The results illustrated that the public sentiment for the pandemic does have a predictive effect on the stock exchange. Furthermore, polarity, lagged by 2 days, was an important predictor of stock market movement. Finally, the models that combined sentiment and historical price features outperformed the baseline models, further confirming that sentiment plays an important role in the forecasting of stock exchange. The contribution of this paper attests that the public’s sentiment for the coronavirus has a predictive effect on the UK stock market.

### How to run? 💻🔨

To execute the Python scripts, first the github projects mentioned in the file 'Tweet_hydrator.ipynb' should be downloaded in order to retrieve the original content of the tweets.
</br> Final_notebook.ipynb should be then executed to replicate the results of this analysis. 
</br> 
</br> ➡️ Note that there is no need to wait for most of the operations to be done (like text pre-processing and aggregating the sentiment), or the tweets to be mined, since the relevant files are provided in the data folder. (The hand-labelled train dataset and the aggregated files are provided as the complete 1.6 million twitter file was too big to upload)
