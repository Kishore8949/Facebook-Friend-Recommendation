# Facebook-Friend-Recommendation

**Associated with Applied AI Machine Learning Course**


Problem statement:

Given a directed social graph, have to predict missing links to recommend users (Link Prediction in graph)
Data Overview

Taken data from facebook's recruting challenge on kaggle https://www.kaggle.com/c/FacebookRecruiting
data contains two columns source and destination eac edge in graph - Data columns (total 2 columns):
- source_node int64
- destination_node int64
Mapping the problem into supervised learning problem:


Business objectives and constraints:

   No low-latency requirement.
   Probability of prediction is useful to recommend ighest probability links

Performance metric for supervised learning:

   Both precision and recall is important so F1 score is good choice
   Confusion matrix


