# Classification of news using summarized news instead of original news.

### Project idea:

1. Evaluating the use of news summaries for classification instead of relying on the original news articles.

2. Investigating the impact of text cleaning techniques on classification performance.
=========================================================================

### Dataset:

A dataset consisting of 2224 news articles and corresponding news summaries obtained from the BBC dataset on Kaggle.

### Process:

*Step 1: Perform pre-processing steps on the dataset.

*Step 2: Generate news summaries using four different functions available in the Sumy library.

*Step 3: Evaluate the quality of the generated summaries using metrics such as Rouge and select the best-performing summary.

*Step 4: Develop a neural network model using the original news articles, the selected best summary, and the pre-processed clean news articles.
