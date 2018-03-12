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
 1. ```train.csv```:  It contains the set of 13 challenges that were attempted by the same user in a sequence.
    The variables and its corresponding definitions are listed as follows:
    user_sequence: Unique ID for the sequence
    user_id: User ID
    challenge_sequence: Challenge sequence number (1-13)
    challenge: Challenge ID
    
 2. ```challenge_data.csv```: Contains attributes related to each challenge
    Variables & its corresponding explanations
    challenge_ID: Challenge ID
    programming_language: Programming language for the challenge
    challenge_series_ID: Series for the given challenge
    total_submissions: Total submissions by all users
    publish_date: Publishing date for the challenge
    author_ID: Author ID
    author_gender: Author gender
    author_org_ID: Organization ID for author
    category_id: Type of challenge
    
 3. ```test.csv```: Contains the first 10 challenges solved by a new user set (not in train) in the test set. We need to predict the next 3 sequence of challenges for these users.
    Var
