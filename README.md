[//]: # "Image References"

[image1]: https://user-images.githubusercontent.com/10624937/43851024-320ba930-9aff-11e8-8493-ee547c6af349.gif "Trained Agent"
[image2]: https://user-images.githubusercontent.com/10624937/43851646-d899bf20-9b00-11e8-858c-29b5c2c94ccc.png "Crawler"


# Project : Continuous Control

### Introduction

For this project, I have used eh  [Reacher](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#reacher) environment.

![Trained Agent][image1]

In this environment, a double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

The environment is considered solved if mean score of consecutive 100 episodes is 30 or above

### Distributed Training

For this project, there are  two separate versions of the Unity environment available
- The first version contains a single agent.
- The second version contains 20 identical agents, each with its own copy of the environment.  

I have used the second version of agent  having 20 identical agents. I used Deep Deterministic Policy Gradient (DDPG) algorithm for training the agents.

 This project is part of the [Deep Reinforcement Learning Nanodegree](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&uact=8&ved=2ahUKEwigwuKwr4LdAhUMI5AKHTuBCz0QFjAAegQIDBAB&url=https%3A%2F%2Fwww.udacity.com%2Fcourse%2Fdeep-reinforcement-learning-nanodegree--nd893&usg=AOvVaw3OfEe4LlR9h_4vW3TZpE_o) program, from Udacity. You can check my report [here](Report.pdf).



### Install

This project requires **Python 3.5** or higher, the Banana Collector Environment, download the code from this repository and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Torch](https://pytorch.org)
- [UnityAgents](https://github.com/Unity-Technologies/ml-agents)
- [OpenAI Gym](https://gym.openai.com)

### Run

In a terminal or command window, navigate to the top-level project directory `banana-rl/` (that contains this README) and run the following command:

```shell
$ jupyter notebook
```

This will open the Jupyter Notebook software and notebook in your browser which you can use to explore and reproduce the experiments that have been run. 



### License

The contents of this repository are covered under the [MIT License](LICENSE).







