---
title: "DQN vs Expected SARSA"
summary: "Deep Q-network and expected SARSA are implemented in Keras to solve the Cartpole problem"
date: 2020-05-01T17:06:16-07:00
draft: false
---
**Deep Q-Network and Expected SARSA**

<div style="text-align:justify">My bachelor thesis was a model-based RL problem while, this project is my first implementation of a model-free RL problem.
I implemented DQN by an epsilon-greedy policy. The expected SARSA used a softmax as its policy by a function approximator same as DQN. Also, in both implementations the memory replay procedure is used. For the Cartpole-v0 both are able to learn to never loose.</div>
<br>
<div style="text-align:justify">The below figures show the output of both implementations for 35000 steps. You can find the implementations in <a href="https://gitlab.com/hosh/master/-/blob/master/Cartpole-DQN/Cartpole.py">my Gitlab.</a></div>




{{< figure library="true" src="DQN.png" title="DQN" lightbox="true" >}}
{{< figure library="true" src="sarsa.png" title="Expected SARSA" lightbox="true" >}}
