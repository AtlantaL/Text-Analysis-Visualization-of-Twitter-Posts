# Text Analysis and Visualization of Twitter Posts

**Authors:** Atlanta Liu, Jenny (So Youn) Kim

**Date:** Winter 2020

Visual comparison of physical activity and sleep disorder tweets across Canada. This is the final project for an advanced visualization course in the health data science program at the University of Calgary. The full report is provided as a pdf, with higher res images available in the folder.

### Definition

Physical activity tweets involved any self-reported posts regarding one's engagement with physical exercise. Sleep disorders is any self-reports of insomnia or other major sleep issues. 

### Project Breakdown

This project is separated into multiple phases. The first phase involved exploring the distribution for each tweet type across the provinces in Canada. The second phase involved implementing a supervised and unsupervised learning component to the project. For the supervised learning, we trained both a Naive Bayes and Random Forest binary classifier to predict if the tweets were self-reported. For the unsupervised learning component, we utilized natural language processing (NLP) to build multiple bigrams in R and visualized their text network. 

To see if our findings could be further strengthened via data triangulation, we pulled data from other platforms (Google Trends & Reddit). Even though we only had three months of data to work with, we looked to see if there were any temporal relations self-reported tweet counts and relevant search topics in Google. Multiple subreddit posts were mined and used for visual comparison to twitter posts in bigrams. 

Finally, we plotted a barplot dendrogram to visualize the results of Latent Dirichlet allocation (LDA). LDA is a natural language processing technique that falls into the topic modelling category. This allows us to discover relationships between a large set of words to see if there is a hidden semantic structure behind it (i.e. do the words fall into discrete topics?).


