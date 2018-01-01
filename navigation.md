### -1, 2017
- [Unifying Map and Landmark Based Representations for Visual Navigation](http://arxiv.org/abs/1712.08125v1), Saurabh Gupta, David Fouhey, Sergey Levine, Jitendra Malik

This works presents a formulation for visual navigation that unifies map
based spatial reasoning and path planning, with landmark based robust plan
execution in noisy environments. Our proposed formulation is learned from data
and is thus able to leverage statistical regularities of the world. This allows
it to efficiently navigate in novel environments given only a sparse set of
registered images as input for building representations for space. Our
formulation is based on three key ideas: a learned path planner that outputs
path plans to reach the goal, a feature synthesis engine that predicts features
for locations along the planned path, and a learned goal-driven closed loop
controller that can follow plans given these synthesized features. We test our
approach for goal-driven navigation in simulated real world environments and
report performance gains over competitive baseline approaches.
