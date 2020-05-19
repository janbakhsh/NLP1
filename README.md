# Objective
Finding top ngrams that would represent short news texts  
This notebook is still in progress of completion, however, at this stage represents few different approaches to the problem.  
Cell outputs that contain confidential informations are cleared, but the comments throughout the notebook clarify the objective of each cell.

The goal of this notebook is to search for top words (ngrams) of interest that can be associated to each news entry in column "HEADLINE_ALERT_TEXT",  
and at the same time attempting to cluster/topic model the docs in that column using different methods such as Non Negative Matrix Factorization   
Why 4 topics?
My assumption was that if the entries in HEADLINE_ALERT_TEXT column are associated with only 4 unique entries in EVENT_TYPE column,
then I can ask the same from my model in terms of clustering the news entries.  

# Data
Due to confidentiality of the content of the dataset such as dates, news articles, country of origin ... the dataset is excluded from this repository
