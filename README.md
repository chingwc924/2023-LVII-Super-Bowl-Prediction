# 2023 LVII Super Bowl Prediction
## Inroduction
The Super Bowl, the pinnacle of American football, is the most-watched television event in the United States. Every year, millions of fans eagerly anticipate the showdown between the two best teams from the NFL's AFC and NFC conferences. With a rich history spanning over 50 years, the Super Bowl provides a treasure trove of data that can be harnessed to predict the outcome of future games.

One approach to predicting the Super Bowl winner is by utilizing machine learning techniques. Machine learning is a field of artificial intelligence that involves training algorithms to learn from historical data and make predictions or decisions. By analyzing vast amounts of data from past Super Bowls, such as team performance statistics, player statistics, weather conditions, and other relevant factors, machine learning algorithms can identify patterns and trends that may influence the outcome of the game.

In this study, we will delve into the historical data of past Super Bowls, including game results, team statistics, and other relevant variables, to develop a predictive model using machine learning techniques. We will explore various algorithms, such as logistic regression, decision trees, and random forests, to identify the most accurate and reliable method for predicting the winner of the upcoming LVII Super Bowl. By leveraging the power of machine learning, we aim to provide valuable insights and predictions for football enthusiasts and bettors alike, as they eagerly anticipate the outcome of this highly anticipated event.

***Fun Facts about SuperBowl***

・Teams that score first in the Super Bowl have won the game 68% of the time.

・The team that rushes for more yards in the Super Bowl historically wins.

・Teams that allowed fewer points per game during the regular season have won the last seven Super Bowl games.

## Prediction

<img width="1470" alt="Screenshot 2023-04-13 at 4 09 25 PM" src="https://user-images.githubusercontent.com/129904878/231902193-cd511c57-6681-4bb9-9076-6cd48e5deb23.png">

<img width="1468" alt="Screenshot 2023-04-13 at 4 09 54 PM" src="https://user-images.githubusercontent.com/129904878/231902215-153b5ef7-21c5-47b0-ba04-1c2e12109768.png">

Using linear regression to predict the final score, taking Team1Score as the dependent variables, others as independent variables.

***R-Squared: 50%     MAPE: 0.14***

![image](https://user-images.githubusercontent.com/129904878/231902258-b3d74cbd-541b-41f4-917c-cd76f2996552.png)

![image](https://user-images.githubusercontent.com/129904878/231902273-0bbb88cb-a03d-4f1e-ba38-94b7325296fc.png)

Using decision tree as a classifier to determine which factor can best differentiate between winner and loser. (based on entropy)

![Unknown](https://user-images.githubusercontent.com/129904878/231902790-200e64f5-62c9-4f28-9aaf-c5c8b6f8b3eb.png)

## Final Result
<img width="1470" alt="Screenshot 2023-04-13 at 4 13 01 PM" src="https://user-images.githubusercontent.com/129904878/231902495-60c1de52-72a6-4d21-8245-9a636c720cd6.png">






