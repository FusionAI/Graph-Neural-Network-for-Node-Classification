# Graph-Neural-Network-for-Node-Classification

### Objective

The task is to classify whether the GitHub user is a web or a machine learning developer. This target feature was derived from the job title of each user.

### Dataset description

A large social network of GitHub developers which was collected from the public API in June 2019. Nodes are developers who have starred at least 10 repositories and edges are mutual follower relationships between them. The vertex features are extracted based on the location, repositories starred, employer and e-mail address. It contains 37700 edges, and the maximum length of a feature vector for a certain node is 4005. The number of web developers in the network are 27961 and number of Machine learning developers are 9739. 

### Graph Visualizaton

This network graph shows the interaction between the nodes i.e., GitHub developers.

![image](https://user-images.githubusercontent.com/60337704/174717142-5fd4e394-8244-4840-a0e7-e0782b03e3f2.png)

### Results:

The model works pretty well with the test dataset as we get the accuracy of <b> 83.71% </b> , which is higher than that with normal CNN.
