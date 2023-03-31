# Kaggle-BOT-Detection

N.B: The data is too lag to be updted. Here is the link to my dataset

https://www.kaggle.com/datasets/shriyashjagtap/kaggle-bot-account-detection

About Dataset
The data in question was generated using the Faker library and is not authentic real-world data. In recent years, there have been numerous reports suggesting the presence of bot voting practices that have resulted in manipulated outcomes within data science competitions. As a result of this, the idea for creating a simulated dataset arose. Although this is the first time that this dataset has been created, it is open to feedback and constructive criticism in order to improve its overall quality and significance.

NAME: The name of the individual.
GENDER: The gender of the individual, either male or female.
EMAIL_ID: The email address of the individual.
IS_GLOGIN: A boolean indicating whether the individual used Google login to register or not.
FOLLOWER_COUNT: The number of followers the individual has.
FOLLOWING_COUNT: The number of individuals the individual is following.
DATASET_COUNT: The number of datasets the individual has created.
CODE_COUNT: The number of notebooks the individual has created.
DISCUSSION_COUNT: The number of discussions the individual has participated in.
AVG_NB_READ_TIME_MIN: The average time spent reading notebooks in minutes.
REGISTRATION_IPV4: The IP address used to register.
REGISTRATION_LOCATION: The location from where the individual registered.
TOTAL_VOTES_GAVE_NB: The total number of votes the individual has given to notebooks.
TOTAL_VOTES_GAVE_DS: The total number of votes the individual has given to datasets.
TOTAL_VOTES_GAVE_DC: The total number of votes the individual has given to discussion comments.
ISBOT: A boolean indicating whether the individual is a bot or not.


Analysing the data

This is to detect BOT account following on kaggle
The data contains information about account following and its followers. Also contained in the data set is the number post each followers has on its account. Which is the discussion count
The data set was imported using pandas then it was checked for Null values and then the null values were dropped.
Further analysis was done using the Follower count. This helped to determine which accounts are BOT based on the number of following the account has which in this analysis is between range 0-10
