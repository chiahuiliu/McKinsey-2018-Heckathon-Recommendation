# McKinsey-2018-Heckathon-Recommendation
This is the repo for 2018 McKinsey Hackathon on Mar. 10
For the original competition website, please check [McKinsey Analytics Online Hackathon](https://datahack.analyticsvidhya.com/contest/mckinsey-analytics-online-hackathon-recommendation/?utm_source=sendinblue&utm_campaign=McKinsey_Hackathon__Recommendation_Design_Go_live&utm_medium=email)

## Project Introduction
To come up with a machine learning/deep learning algorithm to help solve the real-world problem.

## Problem Statement
Your client is a fast-growing mobile platform, for hosting coding challenges. They have a unique business model, where they crowdsource problems from various creators(authors). These authors create the problem and release it on the client's platform. The users then select the challenges they want to solve. The authors make money based on the level of difficulty of their problems and how many users take up their challenge.
 
The client, on the other hand makes money when the users can find challenges of their interest and continue to stay on the platform. Till date, the client has relied on its domain expertise, user interface and experience with user behaviour to suggest the problems a user might be interested in. You have now been appointed as the data scientist who needs to come up with the algorithm to keep the users engaged on the platform.
The client has provided you with history of last 10 challenges the user has solved, and you need to predict which might be the next 3 challenges the user might be interested to solve. Apply your data science skills to help the client make a big mark in their user engagements/revenue.

## Data Description
for data desciption, there are three files:
 1. `train.csv`:  It contains the set of 13 challenges that were attempted by the same user in a sequence.
 2. `challenge_data.csv`: Contains attributes related to each challenge
 3. `test.csv`: Contains the first 10 challenges solved by a new user set (not in train) in the test set. We need to predict 
 
## Work Flow
To propose the solution, I used `KMeans` clusters by clustering users into 3 groups, and using the classification results to recommend/predict user's next three possible challenges.

`Input`: train.csv and challenge.csv

`Process`: KMeans cluster

`Output`: a csv file corresponding with user id and their next three challenge prediction results


## To Dos
- [ ] Change different ways to do the prediction. e.g. consine similarity
