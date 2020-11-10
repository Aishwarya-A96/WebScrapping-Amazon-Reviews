# WebScrapping-Amazon-Reviews
Amazon Reviews are webscrapped from url and sentiment is predicted for amazon reviews
Amazon Reviews link: https://www.amazon.in/Amazon-FireTV-Stick-4K-Alexa-Voice-Remote-Streaming-Player/product-reviews/B079QQZZJK/ref=cm_cr_dp_d_show_all_btm?ie=UTF8&reviewerType=all_reviews
From the above mentioned link user reviews are web scrapped and reviews are loaded in dataframe.Reviews are preprocessed and stopword are removed to get cleaned reviews
Sentiment is predicted using TEXTBLOB and I fitted Logistic Regression, Gaussian Naive Bayes, Multinomial Naive Bayes and Support Vector Machine to give prediction on class whether its positive or neutral or negative class
Out of all classification models we found better accuracy using Naive Bayes Gaussian classifier and achieved accuracy upto 74%

