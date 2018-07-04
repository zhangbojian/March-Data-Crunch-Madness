# march-data-crunch-madness
Deloitte March Data Crunch Madness

AN OPTIMIZED MACHINE LEARNING MODEL FOR PREDICTING 2018 MARCH MADNESS MATCH-UP PROBABILITIES

Team name: Fantastic Four

Team member: Beiya Xue; Bojian Zhang; Shu Yang; Yunjian Wei

Introduction

The National Collegiate Athletic Association (NCAA) Men's Basketball Tournament is informally referred to as "March Madness". With 68 college basketball teams competing in a single-elimination tournament, March Madness is played every spring in the US to determine the national championship of the major college basketball teams. Based on Kaggle’s Machine Learning Mania(https://www.kaggle.com/c/mens-machine-learning-competition-2018#evaluation ), competitors of 2018 Deloitte March Data Crunch Madness predict the probability that a team wins any given game in the 2018 Tournament. Logloss is used as evaluation. Extensive historical data to jump-start the modeling process is gived. Competitors are encouraged to incorporate their own sources of data.

Highlights of Our Project

One of the highlight of our project is the new variable, academic performance. We believed that the academic performance of a team will have a positive effect on the winning posibility. Another one is the project's philosophy, less is more. We tried to use as less variables as possible to explain the impact of each competition and build as simple model as possible to predict the results of 2018 NCAA(National Collegiate Athletic Association). Besides, we got the lowest logloss, 0.5478. Finally, we won the first prize of this year's competition and compared with the result on Kaggle, we are actually the fourth among more than 900 teams. Check the website (https://www.kaggle.com/c/mens-machine-learning-competition-2018/leaderboard) to see the results of the other analysts on Kaggle.

Data description

Data scource

the offical given historical data APR (http link) delete several years that some schools' academic performance can not be found

Data size

Variable type

Methodology

Feature selection

PCA

LASO regression

Coefficient of variation

Machine learning

RandomForestClassifier

Logistic regression

MLPClassifier
