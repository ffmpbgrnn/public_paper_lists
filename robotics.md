### -1, 2017
- [Sim2Real View Invariant Visual Servoing by Recurrent Control](http://arxiv.org/abs/1712.07642v1), Fereshteh Sadeghi, Alexander Toshev, Eric Jang, Sergey Levine

Humans are remarkably proficient at controlling their limbs and tools from a
wide range of viewpoints and angles, even in the presence of optical
distortions. In robotics, this ability is referred to as visual servoing:
moving a tool or end-point to a desired location using primarily visual
feedback. In this paper, we study how viewpoint-invariant visual servoing
skills can be learned automatically in a robotic manipulation scenario. To this
end, we train a deep recurrent controller that can automatically determine
which actions move the end-point of a robotic arm to a desired object. The
problem that must be solved by this controller is fundamentally ambiguous:
under severe variation in viewpoint, it may be impossible to determine the
actions in a single feedforward operation. Instead, our visual servoing system
must use its memory of past movements to understand how the actions affect the
robot motion from the current viewpoint, correcting mistakes and gradually
moving closer to the target. This ability is in stark contrast to most visual
servoing methods, which either assume known dynamics or require a calibration
phase. We show how we can learn this recurrent controller using simulated data
and a reinforcement learning objective. We then describe how the resulting
model can be transferred to a real-world robot by disentangling perception from
control and only adapting the visual layers. The adapted model can servo to
previously unseen objects from novel viewpoints on a real-world Kuka IIWA
robotic arm. For supplementary videos, see:
https://fsadeghi.github.io/Sim2RealViewInvariantServo
