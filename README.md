# RoboND-DeepLearningArm-Project

## Introduction
The Deep reinforcement learning is poised to revolutionize the field of AI and represents a step towards to solve problems of how agents can learn to take the best  actions to get maximum, efficient results based on cumulative reward function/program. The theory of reinforcement learning provides a normative account, deeply rooted in psychological and neuroscientific  perspectives on animal behaviors, of how agent may optimize their learning and control of an environment. To train, agent must derive efficient representations of the environment from high-dimensional sensory inputs, and use these to generalize past experience to new situations. Remarkably, humans and other animals seem to solve this problem through a harmonious combination of reinforcement learning and hierarchical sensory processing systems, the former evidenced by a wealth of neural data revealing notable parallels between the phasic signals emitted by dopaminergic neurons and temporal difference reinforcement learning algorithms. In this Robotic Arm project, agent will learn based on the same principle, save the past learning experiences, resulting in achieving great results over the time.

## Agent Challenge: 
#### 1. Have any part of the robot arm touch the object of interest, with at least a 90 percent accuracy. 
#### 2. Have only the gripper base of the robot arm touch the object, with at least a 80 percent accuracy.

## Reward Functions
Reward Functions in Reinforcement learning is all about positive and negative rewards (punishment or pain) and let robot learning to choose the actions which yield the best cumulative reward. To find these actions, it’s useful to first think about the most valuable states in our current Robot Arm environment. On a Robot Arm or Robot Gripper base  touch the object is the most valuable, that is the state which is most rewarding, and the states when robot Arm touch are more valuable than states that are untouch or not touched.
