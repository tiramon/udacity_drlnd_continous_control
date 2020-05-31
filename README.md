# Project: Continous Control
This project is about training a deep reinforcment learning agent how to move a double jointed arm to target locations.

## About the environment

In this environment, a double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

The task is episodic, and in order to solve the environment, your agent must get an average score of +30 over 100 consecutive episodes.

## Setting up the environment

### Download environment

The Environment can be downloaded at

* Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux.zip)
* Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher.app.zip)
* Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86.zip)
* Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86_64.zip)

### Install dependencies
Dependencies needed to get the programm running are gathered in the requirements.txt to install those execute the command:

```bash
 pip install requirements.txt
```

I had problems to install torch==0.4.0 so if you execute 

```bash
pip install torch==0.4.0 -f https://download.pytorch.org/whl/torch_stable.html 
```

before the command above it should work as expected

## Run Agent

## Files