# Project 3 (Deep Reinforcement Learning - Play Tennis)
---
[Andreas Windisch, Mar. 2019](https://www.linkedin.com/in/andreas-windisch-physics/)

This notebook contains the documentation for Project 3 of the [Deep Reinforcement Learning Nanodegree](https://www.udacity.com/course/deep-reinforcement-learning-nanodegree--nd893). Feel free to play with this code as you please. Also, in case you have any questions or comments, or simply want to contact me, use the link to my LinkedIn profile above, or write me directly using [andreas.windisch@yahoo.com](andreas.windisch@yahoo.com). Have fun exploring this nice project! :-)

### 0. Synopsis

In this project, we will train Agents to play tennis. 

#### Action Space
There are two actions for an Agent, related to the movement relative to the net, and the possibility to jump.

#### Observation Space
The observation space consists of 8 variables corresponding to position and velocity of the ball and racket.

#### Rewards
A reward of +0.1 is given to an Agent if it hits the ball over the net. If the ball hits the floor, or is hit out of bounds, a negative reward of -0.01 is given. This encourages the Agents to keep the ball in play as long as possible.

#### Goal
The training of the Agents is over, once an average score of +0.5 over 100 consecutive episodes is obtained, after taking the maximum score of the two Agents.

### 1. Files in this repository

* README.md - This file
* Report.md - A report containg the details of the implementation 
* Tennis.ipynb - A Jupyter Notebook containing the main code for training the Agents 
* model.py - The Neural Network used for training the Actor and the Critic (PyTorch)
* agent.py - Definitions for the Agent and its actions
* checkpoint_actor.pth  - The saved status of the actor network
* checkpoint_critic.pth - The saved status of the critic network
* score.png - A plot of the score over the training episodes

### 2. Running the code
The code is this repository requires numpy, PyTorch, Unity ML Agents and Jupyter. Make sure that those are installed. Then, just clone the repository and open the Notebook 'Tennis.ipynb'. Follow the instructions in the notebook to train the Agents.
