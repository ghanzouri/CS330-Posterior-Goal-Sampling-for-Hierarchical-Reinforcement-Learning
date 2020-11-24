# CS330 Posterior Goal Sampling for Hierarchical Reinforcement Learning

![RL](utilities/RL_image.jpeg)   ![PyTorch](utilities/PyTorch-logo-2.jpg)

Original Github repository : [Deep Reinforcement Learning Algorithms with PyTorch](https://github.com/p-christ/Deep-Reinforcement-Learning-Algorithms-with-PyTorch).

This work was done as a class project for CS 330 : Deep Multi-Task and Meta Learning. It is a replication of Hierarchical-DQN (h-DQN), (*Hierarchical Deep Reinforcement Learning: Integrating Temporal Abstraction and Intrinsic Motivation* <sub><sup> ([Kulkarni et al. 2016](https://arxiv.org/pdf/1604.06057.pdf)) </sup></sub>) on the *Long Corridor Game* environment.

## **Modifications**
The work was done on the h-DQN algorithm and provided a modified version that includes a Hierarchical-Ensemble DQN RL for efficient high-level policy learning. The code is present in agents/hierarchical_agents/bh_agents.py.

We also included a new function pick_actions2() in agents/DQN_agents/DQN.py that allows goal sampling among all Q heads functions.

## **Execution**

```commandline
python results/Long_Corridor.py
``` 

### Usage ###
The repository's high-level structure is:
 
    ├── agents                    
        ├── DQN_agents         
        ├── actor_critic_agents   
        ├── hierarchical_agents
        └── policy_gradient_agents
    ├── environments   
    ├── exploration_strategies
    ├── results             
        └── data_and_graphs        
    ├── tests
    ├── utilities             
        └── data structures   


