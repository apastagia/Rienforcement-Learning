## Reinforcement Learning

**Reinforcement learning(RL) is a type of machine learning, in which an agent explores an environment to learn how to perform desired tasks by taking actions with good outcomes and avoiding actions with bad outcomes.**

RL model will learn from its experience and over time will be able to identify which actions lead to the best rewards.

**AIM: RL, an agent interacts with an environment with an objective to maximize its total reward.**

**WORKING**
    The agent takes an action based on the environment state and the environment returns the reward and the next state. The agent learns from trial and error, initially taking random actions and over time identifying the actions that lead to long-term rewards.
    
![reinforcement-learning-flow](https://user-images.githubusercontent.com/62986688/112262502-c4840680-8c93-11eb-8474-5c330d03e57f.jpg)
    
## Terms used in Reinforcement Learning

* Agent(): An entity that tries to gain reward by interaction. In practice the agent is a piece of code that implements some policy.

* Environment(): It's a model of the world that is external to the agent. It provides observations and rewards to agent.

* Action(): Actions are the moves taken by an agent within the environment.

* State(): State is a situation returned by the environment after each action taken by the agent.

* Reward(): A feedback returned to the agent from the environment to evaluate the action of the agent.

## Training RL model

* It is an iterative process. The agent explores the environment and builds up experience. The experience collected are used to update the neural network periodically and the updated models are used to create more experiences.
