### -1, 2017
- [Improving Generalization Performance by Switching from Adam to SGD](http://arxiv.org/abs/1712.07628v1), Nitish Shirish Keskar, Richard Socher

Despite superior training outcomes, adaptive optimization methods such as
Adam, Adagrad or RMSprop have been found to generalize poorly compared to
Stochastic gradient descent (SGD). These methods tend to perform well in the
initial portion of training but are outperformed by SGD at later stages of
training. We investigate a hybrid strategy that begins training with an
adaptive method and switches to SGD when appropriate. Concretely, we propose
SWATS, a simple strategy which switches from Adam to SGD when a triggering
condition is satisfied. The condition we propose relates to the projection of
Adam steps on the gradient subspace. By design, the monitoring process for this
condition adds very little overhead and does not increase the number of
hyperparameters in the optimizer. We report experiments on several standard
benchmarks such as: ResNet, SENet, DenseNet and PyramidNet for the CIFAR-10 and
CIFAR-100 data sets, ResNet on the tiny-ImageNet data set and language modeling
with recurrent networks on the PTB and WT2 data sets. The results show that our
strategy is capable of closing the generalization gap between SGD and Adam on a
majority of the tasks.


