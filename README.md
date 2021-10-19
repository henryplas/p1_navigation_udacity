[//]: # (Image References)

[image1]: https://user-images.githubusercontent.com/10624937/42135619-d90f2f28-7d12-11e8-8823-82b970a54d7e.gif "Trained Agent"

# Project 1: Navigation

### Introduction


![Trained Agent][image1]

Welcome to my solution to the first project. I intend to walk you through a) how my project works/the details of the design b) the steps neccessary to run my project.

### How to run my solution

(As a quick side note: The environment I coded in was the Udacity project space. I am not sure how this runs off the website.)

This project can be run pretty simply by running each cell (in Navigation.iynb) t should make all the necessary imports to external files and packages enough to function as it runs on my computer. 

By doing the above steps, the program will finish in about 600 episodes depending on the goal reward (I chose 13.5, above the required 13). This will output a checkpoints.pth file which is the weights of the network. 

### How my solution works

I used a similar configuration to the deep q network that was used in a previous challenge. The parameters I changed were as follows: the state space - 37 length array, the action space - 4 (up, down, left, right), and the network nodes/layers - 64 nodes and 2 hidden layers.

