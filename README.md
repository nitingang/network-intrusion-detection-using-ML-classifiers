# Network-Intrusion-Detection-Using-ML-Classifiers
Network Intrusion is an attack from outside the organization and Intrusion Detection
is a type of security management system for computers and networks. An ID system
gathers and analyze the information from various area within a network or a
computer to identify possible security breaches. In this paper, I have performed some
machine learning techniques to identify Network Intrusion on KDD’99 dataset which
is publicly available. All techniques are applied to 10% of KDD’99 original and
filtered dataset. The data is filtered by me to remove the duplicates.
I have performed mainly three ML techniques : NaiveBase, J48 decision tree
and Support Vector Machine. After getting the results of each classifiers I have
performed some Ensemble techniques to get the better results than that of individual
classifiers. I have performed Majority Voting(basic ensemble technique) and Stack
Generalization to get the better results.
After these tasks I have also done an expertiment with Nueral Network like I
have taken the outputs of individual classifiers and put them into a neural network to
achieve some better results, its like ensembling only but the thing is I used a Neural
Network to combine the results.
Finally I got to know that individually J48 and SVM are giving the good
results compared to NaiveBase. If I talk about Ensembling, Stack Generalization and
Neural Netwrok are far better than Majority voting.
- I have performed all the task with the help of WEKA.
- http://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html
