# Drone-Reinforcement

A reinforcement learning algorithm is a type of machine learning method that uses trial and error techniques to learn how to perform a task. Through rewards and punishments, the drone is able to build up a model of the environment and develop strategies to achieve a set goal. This type of algorithm is used in autonomous drones to allow them to learn how to navigate and interact with the world. 

The current study employs adding heuristics to a drone controller for it to be able to navigate an environment and reach its target in the most efficient route. 

<h2> Heuristics Control </h2>

We can work out that in order for the drone to remain stationary, provided the drone is at rest to begin with, we must set T1 = T2 and T1 + T2 = mg.

In order to move the drone in the vertical plane we must keep the condition that T1 = T2 to avoid any torque on the drone, however, we adjust the thrust from each propeller by a factor ⍷. If we consider Teq= 0.5 mg, then we can say that T1 = T2 = Teq + ⍷. This adjustment gives a resultant force of Fy = 2⍷, now independent of the weight.

This means we can directly control the vertical motion of the drone to reach a specified coordinate, making epsilon positive to accelerate upwards, and negative to accelerate downwards
