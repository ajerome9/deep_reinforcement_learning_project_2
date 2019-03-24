# Deep Reinforcement Learning Nanodegree - Project 2: Continuous Control

## Project details
The task here is to develop a Reinforcement Learning Agent that can navigate through UnityML's Reacher environment.

#### The environment
The environment consists of 20 double jointed arms and moving targets. If an arm is at its target location, the agent receives a reward of 0.1.

#### State space
The state space is continuous, and is 33 dimensional. The state indicates aspects about where the arm's position, rotation, velocity, and angular velocity.

#### Action space
The agent's action is represented by a vector with 4 numbers. Note that the actions here are continuous values (i.e. not discrete actions). The numbers in the action vector correspond to the torque applied to the arm's joints. Action values must be in the range \[-1, 1\]

#### Episode
The unity ml agent terminates an episode in 1000 time steps. The environment is considered solved when the agent gets an average score of 30 over 100 consecutive episodes.

# Getting Started
#### Package dependencies
The project requires library dependencies such as PyTorch, Numpy and these can installed by following the platform-specific instructions at the below link.
https://github.com/udacity/deep-reinforcement-learning#dependencies

#### ML-Agents toolkit
The project uses an environment provided by Unity ML Agents, and this can be installed by 
1. Downloading the below zip file. Note that here we are solving the 20 agent environment.
[AWS](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Linux_NoVis.zip)

2. Place it in the p2_continuous-control/ folder in the DRLND GitHub repository, and unzip it.


# Training the agent
To run the code in this repository,
1. Open the Continuous_Control.ipynb notebook
2. Start the environment by following the first few cells
3. Sections 2,3 explore the environment, and also look at how a random agent would perform
4. Section 4 trains an agent that uses Deep Deterministic Policy Gradients (DDPG) to learn a policy for this environment. This DDPG agent is based on the Pendulum DDPG agent in the same nanodegree program.

For a description of the DDPG agent, please see Report.pdf
