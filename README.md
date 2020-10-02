# Fintech Hiring Trends

# Data Preprocessing

We scrapped a few reports related to Fintech and gathered key terms that are associated with Fintech and scrapped jobs from two of the assigned largest banks in US and evaluated hiring trends in these banks.

In continuation of analysis, we further performed data cleansing, feature engineering and exploratory data analysis on a unified dataset collected for 24 US banks.

# Clustering

We created clusters from the list of keywords derived by 3 methods

Word count
TF/IDF
Text Rank

# Feature Engineering

Classifying each job description into different clusters: Each job description is assigned to a suitable cluster based on the count of that cluster. The counter for each cluster increments if any word from that cluster appears in the job description.

Identifying the focused area/fintech under each cluster: Each job description is featured to identify the focused area/fintech under the assigned cluster. For example if Bank of America has Job J1 which is categorized into technology, we would determine the focused area under technology cluster by selecting the maximum count of Fintech words under that cluster.

# Analysis

We analyzed the dataset generated, which provided us a detailed study of the job hiring trends in fintech industry in the USA
