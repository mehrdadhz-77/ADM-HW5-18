# Homework 5 - Exploring StackOverflow!
### Repository for ADM group 18 Homework 5

![Alt Text](https://www.linuxadictos.com/wp-content/uploads/stack-overflow-1024x244.jpg.webp)


This repository stored the ADM Homework 5 about implemention on graph based on StackOverFlow dataset that can be found here [here](https://snap.stanford.edu/data/sx-stackoverflow.html), working only on the merged data of ['Answers to questions', 'Comments to questions', 'Comments to answers'] datasets.
To this repository works:
- Mehrdad Hassanzadeh, hassanzadeh.1961575@studenti.uniroma1.it
- Giulio D'Erasmo, derasmo.1859130@studenti.uniroma1.it
- Anthony Giusti, giusti.1992108@studenti.uniroma1.it

In the repository can be found:
* __main.ipynb__:
   > A Jupyter notebook which provides the solutions on:
   - How to merge the given datasets in a self-made weighted directed graph;
   - Implementation of the backend:
      - Functionality 1 - return whether the graph is directed or not, number of users, number of answers/comments, average number of links per user, density degree of the graph, whether the graph is sparse or dense;
      - Functionality 2 - return the value of a given metric (Betweeness, PageRank, ClosenessCentrality ) applied over the complete graph for the given interval of time;
      - Functionality 3 - return the shortest path from node1 to node2 and that pass troughtout a set of specific nodes.
      - Functionality 4 - return the minCut needed to disconnect two users belonging to two different graph
   - Implementation of the frontend:
      - For each functionality we provide a visualitation of the output. 
 


