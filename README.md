Step1

There are a total of 194 observations and the data has 7 variables.

The variables are experience,subscribed,hashedmail,played_hours,name,gender,Age. 

The experience shows the level of the individual in the game pro,veteran,amateur

Subscribed:- Whether the individual is subscribed for the newsletter or not .

HashedMail:-It provides the unique hashed code for each main id

Played_hours:-It shows the number of hours each individual has played the game.Decimal type

name:- name of the person.

Gender:-Gender of the person 

Age:- Age of the person.

The Max age of the player is 58 years old.

The minimum age is 9 years.

The average age of players is around 21.14

The maximum number of hours played is 223.1 hours.

The mean is 5.846.

Potential error in the data:

The Number of hours can have outliers as there are values that are very large compared to the average and can skew the data.

Data was collected by a team led by Dr.Frank where they set up servers and players actions are recorded as they navigate through the world.



Step2

Can the age and the amount of time spent playing the game be related to whether he or she subscribes to the newsletter or not?


Step3

The above bar plot shows the percentage of players at every age who have subscribed to the newsletter.Younger players who are between the ages of 16 and 24 have high subscription rates compared to the older age players. We can see that as the age increases the percentage of subscribers also decreases.

The above histogram shows the distribution of player's age in a dataset. The majority of the players fall between the ages 15-25 years. The distribution is centered over the people in younger age and there are fewer individuals in older ages.This shows that the above data is dominated by younger individuals and our model might not work well for older individuals.





Step4

I plan to use the KNN (K-Nearest Neighbors) Classification model to predict whether a player will subscribe to the newsletter based on the age and the number of hours spent playing the game and return and response of `True` or `False` depending upon the prediction KNN is an appropriate model because it's a simple and intuitive classification algorithm.It predicts the class of a new observation by looking at the K nearest neighbors in the dataset.

The main idea in KNN algorithm is that similar players behave similarly meaning that players with roughly same age and same number of hours spent playing the game behave similarly when it come to subscribing for the newsletter.One limitation is that the time played is very large compared to the age so we need to standardize the values.

 A split of 75% training and 25% testing dataset is ideal to evaluate the model's performance. The models's accuracy will be tested using the cross-validation to find the best values of k.The Evaluation metrics such as the accuracy,precision,recall and the confusion matrix will be used






