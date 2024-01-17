# Pacman-RL-Project
# CustomReflexAgent, BetterReflexAgent, and QLearningAgent

This repository contains custom implementations of three agents for the Pac-Man game: CustomReflexAgent, BetterReflexAgent, and QLearningAgent. 
These agents have been developed in the `multiagents.py` file. These agents have been created and built on top of the Berkeley's for PACMAN automation using Reinforcement Learning and the following github repository has been used https://github.com/pspanoudakis/Berkeley-Pacman-Projects.
Please refer the Readme file of the above repository for a detailed decription of Project0, Project1 and Project2 

Agents
(Execute the following commands using the pacman.py file in Project2)

CustomReflexAgent

The `CustomReflexAgent` is a reflex agent that makes decisions based on a simple evaluation function. 
It considers factors such as the distance to the nearest ghost and proximity to food to make decisions. 
To execute the agent, you can use the following command:

"python pacman.py -p CustomReflexAgent"

BetterReflexAgent
The BetterReflexAgent is an enhanced reflex agent that considers both the distance to the nearest food and the distance to the nearest ghost. 
It aims to maximize the distance to the nearest ghost while also prioritizing positions closer to food. 
To run the agent, use:

"python pacman.py -p BetterReflexAgent"

QLearningAgent
The QLearningAgent is a Q-learning-based agent that learns to make decisions through reinforcement learning. 
It updates its Q-values based on rewards received from the environment. 
To utilize the agent, run:

"python pacman.py -p QLearningAgent"

Usage
To execute and check the performance of any agent, use the python pacman.py -p [AgentName] command. For example, to run the CustomReflexAgent, use:

"python pacman.py -p CustomReflexAgent"

Feel free to experiment with different agents and observe their behavior in the Pac-Man game environment.
