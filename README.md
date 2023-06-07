# Can-Collector-Reinforcement-Learning
This repository contains an implementation of a reinforcement learning project that trains an agent to collect cans in an environment. The agent navigates through different locations and performs actions to pick up and drop off cans.

Project Overview
The goal of this project is to develop an intelligent agent capable of efficiently collecting cans in a given environment. The agent uses the Q-learning algorithm, a popular reinforcement learning technique, to learn an optimal policy that maximizes its reward over time.

The project includes the following components:

Environment: An abstract base class representing the environment. It defines the methods and behaviors expected from the environment, such as retrieving applicable actions and applying actions to transition to a new state.

Can_Collector: A concrete class that implements the Environment interface and represents the specific can collector problem. It includes the initial state, available actions, and reward calculations based on the agent's actions.

q_learning: The Q-learning algorithm implementation, which takes an environment and performs Q-learning until no more actions can be taken. It updates the Q-values based on rewards and the maximum Q-value of the next state.

simulate: A helper function to train the agent using the Q-learning algorithm for a fixed number of iterations or a specific time duration.

visualize_path: A function that visualizes the agent's path and the associated costs on a map using the Folium library.


Results
The training process will be displayed in the console, showing the actions taken by the agent and the associated rewards. Additionally, a map visualization will be generated, illustrating the agent's path and the costs associated with each action.
