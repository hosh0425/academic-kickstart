---
title: "Kinematic Identification Using NN"
summary: "Kinematic Identification of an imperfectly designed differential drive mobile robot "
date: 2020-04-18T17:06:16-07:00
draft: false
---
**Kinematic Identification Using NN**

Problem definition:
<div style="text-align:justify">There is an industrial mobile robot which its casters and also its actuators would set up imprecisely. In one scenario maybe accidentally the actuators and casters are placed symmetric, so the motion model would follow the kinematic model of a perfect designed differential drive mobile robot. For the next scenario, maybe the wheels are not placed parallel, so obviously the robot would not follow the kinematic model of an perfect designed differential drive mobile robot.</div>
<br>
<div style="text-align:justify"> I have designed a multi layer perceptron neural network and also a recursive neural network.
Both of them trained by data collected from simulator. Results shows that multi layer perceptron fits better on predicting motion model. cause the NN has just one hidden layer it does not cause delay in our calculations.
I have created a bag of pre-trained NN including 16 pre-trained NN on different setup of robots. At the phase, the commanded velocities to the robot will feed to all these pretrained NNs, and the estimated position of robot would be an average of the prediction of all predicted NNs.</div>   
<br>
The bellow figure shows the results:
{{< figure library="true" src="kin1.png" title="Kinematic Identification Using NN" lightbox="true" >}}

<br>




{{< youtube 0oFz3s1fMCM >}}
