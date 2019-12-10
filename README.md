# Project Details

This environment has two agents that control Tennis rackets to bounce a ball over a net.

* The observation space consists of 8 variables corresponding to the position and velocity of the ball and racket. Each agent receives its own, local observation.
* Two continuous actions are available, corresponding to the movement toward (or away from) the net, and jumping.
* After each episode, we add up the rewards that each agent received (without discounting), to get a score for each agent. This yields 2 (potentially different) scores. We then take the maximum of these two scores.

<img src = "tennis.png"/>

### Installation requirements

- Youhave to clone this project and have it accessible in your Python environment
- Then you have to install the Unity environment as described in the [Getting Started section](https://github.com/udacity/deep-reinforcement-learning/blob/master/p3_collab-compet/README.md) (The Unity ML-agent environment is already configured by Udacity)

- Download the environment from one of the links below.  You need only select the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86_64.zip)

- Finally, unzip the environment archive in the 'project's environment' directory and eventually adjust the path to the UnityEnvironment in the code.

### Train a agent
    
Execute the provided Tennis.ipynb notebook within this git repository.


