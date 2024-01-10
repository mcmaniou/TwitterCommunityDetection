# Community-Detection

## **The Dataset**
The dataset used is a subset of the Twitter network dataset provided
for this project. Because of space and time constrictions, we did
not utilize the entire dataset, an undirected graph of 24616 nodes
and 237787 edges. Each node has the following attributes:
* followers: Number of followers
* following: Number of following
* totaltweets: the total number of tweets the user has posted
from the day he/she registered on Twitter
* lists: the number of lists that the user is subscribed to
* twitterage: the number of days that passed since the regis-
tration of the user
* verified: if the user is verified or not
* party: the political party the user "follows" (right, left, middle
or neutral)


## **The Process**
* Compose 4 first days (graphs) into one.
* Get giant component.
* Implement *5 algorithms to find communitites* **(Louvain, Label Propagation, Balanced Link Density-based Label Propagation, Fast Greedy, Deep Nonlinear Reconstruction)**.
* Find modularity of each one of them.
* Implement *3 algorithms to investigate the three largest communities* **(Louvain, Balanced Link Density-based Label Propagation, Deep Nonlinear Reconstruction)** *based on finding percentages of labels (parties) in each community, average clustering coefficient, density, diameter and average path length*.

* As a main tool for the *visualization* of our graphs we used *Gephi*.
