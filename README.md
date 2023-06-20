# Master Thesis

This repository contains all the code and data used in the Master Thesis "AI-based recommendation system to support employees and IT projects" in which the goal was to propose and develop a recommendation system to assist the assignment process of people-to-project in the IT domain where not only people's experiences are used in the matching, but also their interests.

The system used Word2Vec for word embedding and Word Mover's Distance as distance metric. The similatiries were computed using a weighted approach.

The respository is organized in the following manner:
- [0-rawdata](0-rawdata): datasets used as source data
- [1-preprocessing](1-preprocessing): notebooks used to transform the initial datasets to be ready for the system
- [2-data](2-data): data that is used for training and evaluation
- [3-word-embedding](3-word-embedding): notebook used to train the word embedding model and the model itself
- [4-match_recommend-employee-to-project](4-match_recommend-employee-to-project): notebooks used to find project roles to a person profile
- [5-match_recommend-project-to-employee](5-match_recommend-project-to-employee): notebooks used to find people profiles to a project role
- [6-results](6-results): data outputted from the recommendation system
- [7-visualizations](7-visualizations): notebooks used to visualize the results

