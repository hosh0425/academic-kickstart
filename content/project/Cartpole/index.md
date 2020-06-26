---
title: "Expected SARSA, DQN, A2C and A3C"
summary: "Expected SARSA, Deep Q-network, A2C and A3C are implemented to solve the Cartpole problem using TensorFlow2"
date: 2020-05-01T17:06:16-07:00
draft: false
---
**Expected SARSA, DQN, A2C and A3C**

<div style="text-align:justify"> My journey in Reinforcement Learning started by enrolling the coursera specialization on RL. This specialization familiraized me with basic approaches in RL.
I implemented DQN by an epsilon-greedy policy. The expected SARSA used a softmax as its policy by a function approximator same as DQN. Also, in both implementations the memory replay procedure is used. For the Cartpole-v0 both are able to learn to never loose.</div>
<br>
<div style="text-align:justify">The below figures show the output of both implementations for 35000 steps. You can find the implementations in <a href="https://gitlab.com/hosh/master/-/tree/master/Cartpole-DQN">my Gitlab.</a></div>




{{< figure library="true" src="DQN.png" title="DQN" lightbox="true" >}}
{{< figure library="true" src="sarsa.png" title="Expected SARSA" lightbox="true" >}}
