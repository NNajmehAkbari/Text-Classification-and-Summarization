# Classification news using summarized instead of original news.
In this project I worked on two different topics. 

The first is what happens if we use summary text instead of the main text for classification? 
And the second is how much text cleaning affects classification.

I used a database of news prepared by the BBC from the kaggle website.

First I did pre-processing.

Then I used four different functions in the Sumy package to summarize the news. (all functions create an extractive summary)

Then I checked the results using Rouge() and selected the best summary.

In the end, I created the neural network model for main news, news summary and clean news.

