
# Project 1: Navigation

### Introduction

The goal is to train an agent to navigate (and collect bananas!) in a large, square world. In this project, we include Deep Q-learning and Double Q-learning implementations. 
The backbone of the project is based on dqn implementation of [Udacity DRL course](https://github.com/udacity/deep-reinforcement-learning/tree/master/dqn) .

### Getting Started

Make sure you have the following environments and libraries.

1. Unity ML Agents Banana environment from one of the links below. You can obtain the Windows environments from
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)

2. Python 3 and Pytorch https://pytorch.org/

3. numpy, matplotlib

4. Unity ml agents:https://github.com/Unity-Technologies/ml-agents

5. Make sure the ML Agents Banana environment is places in your project folder, in this project the folder is called `p1_navigation_soln/`

### Instructions

The DQN_Banana.ipynb is the main jupyter notebook file of the project. Please refer to DQN_Banana.ipynb and run the notebook to obtain the result.


The Deep Q-Learning agent is implemented in dqn_agent.py and Double Q-Learning is implemented in dqn_agent_d.py. Based on which file to import in DQN_Banana.ipynb the mentioned algorithms are selected.


```
#agent
#from dqn_agent import Agent 
#double dqn
from dqn_agent_d import Agent 
```

"# dqn-ml-agents" 

Saved weights are stored in ```checkpoint_dqn.pth``` for Deep Q-learning and ```checkpoint_ddqn.pth``` Double Deep Q-learning algorithms.