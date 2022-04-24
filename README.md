# Welcome to UFC-Betting

## About

This is a Mini-project for CS1015 (Introduction to Data Science and Artificial Intelligence) which focuses on predicting outcomes for UFC fights and proposing betting strategy to maximise profit. We have divided the UFC matchups in terms of the weightclasses and chose to focus on the top 3 most popular weightclass: Lightweight, Middleweight and Heavyweight:


1. [Exploratory Data Analysis](https://github.com/jiarong12/UFC-Betting#:~:text=1%20hour%20ago-,UFC%20Betting%20Exploratory%20Data%20Analysis.ipynb,-Rename%20EDA%201015)
2. [Analysis of Lightweight Data](https://github.com/jiarong12/UFC-Betting/blob/main/UFC%20Betting%20Lightweight.ipynb)
3. [Analysis of Heavyweight Data](https://github.com/jiarong12/UFC-Betting/blob/main/UFC%20Betting%20Heavyweight.ipynb)
4. [Analysis of Middleweight Data](https://github.com/jiarong12/UFC-Betting#:~:text=UFC%20Betting%20Middleweight.ipynb)
  
## Contributors

- @jiarong12 - Data preparation and cleaning, and Kelly Criterion Model
- @oliverlowcy -  Logistic regression and decision tree
- @sleepreap - Exploratory analysis and data driven insights


## Problem Definition
-Are we able to correctly predict the outcome of the match? (whether Blue or Red fighter would win)

-Which model would be best to predict it?

-How much should one bet on the match given the predictions?

-Given the proliferation of online sports betting, people are also losing more. As such, we seek to address these problems mentioned above and provide appropriate betting strategies.


## Motivation
When it comes to betting, we are always influenced by our emotions. Some of us may be tempted by greed, while some of us may be daunted by the thought of losing everything. These emotions will get in the way of our decision making skills and potentially may cause us to lose more than we should or win a lot lesser than deserved. So we have decided to use machine learning to maximise our profits

## Models Used

1. Sci-kit Learn Logistic Regression
2. Sci-kit Learn Decision Tree

## Conclusion

- Physical Attributes such as height, weight, and reach have a low linear correlation value with their win records.
- The odds assigned to individual fighters have higher linear correlation with the actual outcome of the fight.
- Both decision tree and logistic regression are able return around 60% prediction accuracy of the match outcomes, allowing us to achieve a profit from sports betting using kelly criterion.

- The decision tree of depth 5 has better classification accuracy compared to the decision tree of depth 3. However, the tree with depth 5 has problems with overfitting, resulting in the lost of all the capital.

- Logistic Regression returns better predictions and probability than than Decision Tree in our project.
- Kelly Criterion will generate a net profit if overfitting/underfitting does not occur.

## What did we learn from this project?

- Higher classification accuracy may not guarantee a better outcome. 

- Choice of machine learning model is important - Select based on the intended outcome and the characteristics of the model to account for potential problems such as overfitting/underfitting

- Kelly Criterion is a good guideline on proportion to bet and generally guarantees a net profit if the machine learning model used is reliable. However, the profit at the end may not be maximised and the risk involved may not be well tolerated by everyone, thus we introduced a modified strategy with Take Profit and Stop-Loss to accommodate for both low and high risk takers.


## References
- <https://careerfoundry.com/en/blog/data-analytics/what-is-logistic-regression/>
- <https://www.nbcnews.com/news/us-news/sports-betting-skyrocketed-pandemic-experts-warn-ticking-time-bomb-n1266518>
- <https://www.geeksforgeeks.org/ml-logistic-regression-v-s-decision-tree-classification/>
- <https://www.forbes.com/sites/forbestechcouncil/2021/02/25/not-just-a-game-online-sports-betting-and-the-rise-of-corrosive-technology/?sh=2fe66e9f70ec>
- <https://www.azcentral.com/story/money/business/consumers/2022/01/25/arizona-sports-betting-statistics-for-november-show-gambling-losses/9213659002/>


