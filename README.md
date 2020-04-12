# Wrangle and Analyze: WeRateDogs

This project is part of the tasks in the Udacity Data Analyst Nanodegree, and aims to practice the skills learned during the course.

[WeRateDogs](https://twitter.com/dog_rates) is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.

The goal of this project is to wrangle WeRateDogs Twitter data to create interesting and trustworthy analyses and visualizations.

The data for these projects were provided in 3 different ways:

- The WeRateDogs Twitter archive `twitter_archive_enhanced.csv`, that was provided from manually by Udacity.
- The tweet image predictions, i.e., what breed of dog (or other object, animal, etc.) is present in each tweet according to a neural network. The file `image_predictions.tsv` is hosted on Udacity's servers URL: https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv.
- The additional information was collected directly from Twitter via API, to increase data for analysis.

The whole project is developed within [Jupyter Notebook](https://jupyter.org/) and the data is imported and worked using the [Pandas library](https://pandas.pydata.org/) of the [Python language ](https://www.python.org/).