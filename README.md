## Project Title
#### Website_Viral_Prediction

## Problem Statement
Crawl news & information websites & anticipate the likelihood of its virality


The following method uses Random Forest Regressor to estimate the number of shares of the website, which is closely related to the likelihood of the article getting viral.

Starting from a base_url, the web crawler crawls and extracts all the links and features from webpage in a BFS fashion. It is then fed to Random Forest Regressor.

#### Dataset used: UCI Online News Popularity Data Set
