### -1, 2017
- [Adversarial Patch](http://arxiv.org/abs/1712.09665v1), Tom B. Brown, Dandelion Mané, Aurko Roy, Martín Abadi, Justin Gilmer

We present a method to create universal, robust, targeted adversarial image
patches in the real world. The patches are universal because they can be used
to attack any scene, robust because they work under a wide variety of
transformations, and targeted because they can cause a classifier to output any
target class. These adversarial patches can be printed, added to any scene,
photographed, and presented to image classifiers; even when the patches are
small, they cause the classifiers to ignore the other items in the scene and
report a chosen target class.

- [Note on Attacking Object Detectors with Adversarial Stickers](http://arxiv.org/abs/1712.08062v1), Kevin Eykholt, Ivan Evtimov, Earlence Fernandes, Bo Li, Dawn Song, Tadayoshi Kohno, Amir Rahmati, Atul Prakash, Florian Tramer

Deep learning has proven to be a powerful tool for computer vision and has
seen widespread adoption for numerous tasks. However, deep learning algorithms
are known to be vulnerable to adversarial examples. These adversarial inputs
are created such that, when provided to a deep learning algorithm, they are
very likely to be mislabeled. This can be problematic when deep learning is
used to assist in safety critical decisions. Recent research has shown that
classifiers can be attacked by physical adversarial examples under various
physical conditions. Given the fact that state-of-the-art objection detection
algorithms are harder to be fooled by the same set of adversarial examples,
here we show that these detectors can also be attacked by physical adversarial
examples. In this note, we briefly show both static and dynamic test results.
We design an algorithm that produces physical adversarial inputs, which can
fool the YOLO object detector and can also attack Faster-RCNN with relatively
high success rate based on transferability. Furthermore, our algorithm can
compress the size of the adversarial inputs to stickers that, when attached to
the targeted object, result in the detector either mislabeling or not detecting
the object a high percentage of the time. This note provides a small set of
results. Our upcoming paper will contain a thorough evaluation on other object
detectors, and will present the algorithm.


