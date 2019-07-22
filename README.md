# A-B_test_for_ecommerce_website

This repository contains a project I completed as part of Udacity's Data Analyst Nanodegree Program.

The goal of this project is to run through the results of an A/B test and determine if the new website/landing page is better then the old one. These types of exercises are conducted every day in large corporations such as facebook, amazon, and many other websites to improve user engagement, retention and any other metric.

In the first section of the notebook, I do a quick analysis of the csv file which contains the test results. In Part II, I establish my null and alternative hypothesis and conduct a two-sided t-test for difference of means (or difference in conversion rates). This is done using the bootstrap method. These results are then compared to the ones you can obtain using the built-in python libraries. Finally, we also investigate this problem from a logistic regression approach and come to the same conclusions. An extra variable for 'the user's country' is added and investigated to see if that has any effect on the conversion rates.


Included files:
1. ab_data.csv    this file contains the a/b test results, file was given by Udacity
2. countries.csv  this file contains the user's country of origin

How to use:

If you are interested in the project, you may simple click the 'A_B_testing_clean_version...' file and the Jupyter notebook file should open on github.

License:
You may freely use any part of my work/code
