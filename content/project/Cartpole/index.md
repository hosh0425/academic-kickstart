---
title: "Expected SARSA, DQN, A2C and A3C"
summary: "Expected SARSA, Deep Q-network, A2C and A3C are implemented to solve the Cartpole problem using TensorFlow2"
date: 2020-05-01T17:06:16-07:00
draft: false
---
**Expected SARSA, DQN, A2C and A3C**

<div style="text-align:justify"> Considering the great progress deep reinforcement learning achieved in recent years I have found myself interested in this field. My journey in RL began with enrolling in the RL specialization in Coursera. By completing this course I found a basic knowledge in RL. To get more familiar with RL I followed a course series from Deepmind-UCL.

The following figures show the training phase results of Expected SARSA, Deep Q-Network, Advantage Actor-Critic, and Asynchronous Advantage Actor-Critic. 

I implemented the Expected SARSA and DQN using Keras. For implementing A2C I had to learn TensorFlow 2, so I did it. The A3C implementation is multi-thread while it is far better to be multi processed. 

Now which I am writing these I was not able to implement a multi processed A3C using TF 2. It seems PyTorch provides a good wrapper for python multiprocessing which makes it compatible with NN modules.

It is worth mentioning that all the methods trained on my laptop (Gtx 960M). So It is very time-consuming to let the agent train completely. Or train agents in the BreakOut environment.  </div>
<br>
<div style="text-align:justify">You can find the implementations in <a href="https://github.com/HosseinSheikhi/Cartpole">my Github.</a></div>




{{< figure library="true" src="dqn.png" title="DQN - resultsts for two different network" lightbox="true" >}}
{{< figure library="true" src="sarsa.png" title="Expected SARSA - resultsts for two different network" lightbox="true" >}}
