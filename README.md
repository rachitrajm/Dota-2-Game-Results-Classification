# Dota-2-Game-Results-Classification

#### Dataset Description:

This data is taken from UCI Machine Learning Repository.

Each row of the dataset is a single game with the following features (in the order in the vector):

1. Team won the game (1 or -1)

2. Cluster ID (related to location)

3. Game mode (eg All Pick)

4. Game type (eg. Ranked)

5. - end: Each element is an indicator for a hero. Value of 1 indicates that a player from team '1' played as that hero and '-1' for the other team. Hero can be selected by only one player each game. This means that each row has five '1' and five '-1' values.

#### Algorithms:

1. Logistic Regression (Applied Grid Search to get best parameters for this algo).

2. Decision tree

3. Naive Bayes

4. AdaBoost Classification

#### The best result was obtained from Logistic Regression with an accuracy of 59.78%.
