# Movie Recommendation System Report

## 1. Introduction

This report is about a system that recommends movies to users based on their previous movie ratings. We used a special technique to find patterns in the data that helped us make these recommendations. 

## 2. Getting the Data Ready

We started by looking at the ratings that users gave to different movies. We only considered movies that had received a rating above 2, and we focused on users who had rated more than 10 movies. Then, we split the data into two parts: one part for training the system and the other for testing how well the recommendations work.

## 3. Finding Patterns in the Data

We used a smart method called FP-growth to look for connections between different movies. This method helped us find out which movies tend to be liked together and which movies are often watched by the same people. We chose this method because it works well with large amounts of data and can find these connections quickly.

## 4. Making Recommendations

For each user in the test set, we picked out some movie suggestions based on the patterns we found earlier. We wanted to see how good these suggestions were, so we used two measures: precision and recall. Precision shows how many of the recommended movies the user actually liked, and recall tells us how many of the user's favorite movies were included in the recommendations.

## Justification for Choosing Our Method

We chose the FP-growth method because it's fast and efficient when working with lots of data. This helped us find interesting connections between movies without taking too much time.

## How We Built the Recommendation System

We started by understanding the data and what it could tell us about users' preferences. Then we used the FP-growth method to find patterns in the data, which helped us make good movie suggestions for users.

## Conclusion

Our system did a good job of suggesting movies that users might like based on their previous ratings. We found that the FP-growth method was effective in quickly finding connections between different movies. For future work, we suggest looking at more ways to make the suggestions even better, like considering other factors that might influence users' movie preferences.

## Recommendations

Based on our findings, we recommend exploring more ways to improve the recommendation system, like taking into account other things that users might like besides just their past movie ratings. We also suggest making the system more adaptable so that it can keep up with changes in users' preferences over time.
