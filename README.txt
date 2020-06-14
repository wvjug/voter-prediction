One important question that a political campaign faces is "how can we cost effectively get more people to vote for us?" That is, how can one get more people to vote for them in a manner that is effective and, at the same time, resourceful? Effective as in a strategy that appeals to the most amount of people as possible so as to vote for them. Resourceful as in a strategy with the least amount of cost as possible.  To address these two-parts of the question, we analyzed data from the 2016 U.S. election.  By solely using the context of the 2016 U.S. election data to approach the question, we have essentially reduced the scope of the problem under two fundamental assumptions: 

1) For a strategy to be effective, a political campaign should focus on available data that indicate which means have generally helped political campaigns convince the most amount of people in the past.  In the case of the 2016 U.S. election data, the only available data for the means that political campaign can use is media consumption.

2) For a strategy to be resourceful, a political campaign should focus on reaching out to people who will not vote because they are easier to convince than people who will vote.  

Thus, the focus of our project is two-fold: 1) figuring out which media consumption is the most significant in getting people to vote  2) building a prediction model of those who will not vote.

By figuring out which media consumption is most effective in convincing the most amount of people to vote, political campaigns could benefit in using more of that particular media consumption.  And, by building a model to predict those who will not vote, political campaigns could benefit by specifically targeting them.

## Dataset description

The dataset was taken from a large-scale interview study from the American National Election Study (ANES). The initial dataset consists of 3,649 observations and 204 variables. It was sampled using Stratified Probability sampling to improve how well it represents the US population. The types of variables includes voting behavior, political involvement, political alignment, media consumption and demographics. The output variable is a 2-level factor indicating whether an individual voted in the 2016 presidential elections.  

For the purposes of this study, we only accounted for predictor variables relating to media consumption. The data analyzed in this study is a subset of the 11 media-related predictor variables and the output variable.

## Methodology

The models were trained using the caret and randomForest packages on R. To narrow down the final models shown in the code, we trained multiple models. Afterwards, we compared the accuracy of these models and selected the best one.