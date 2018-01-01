### -1, 2017
- [SuperPoint: Self-Supervised Interest Point Detection and Description](http://arxiv.org/abs/1712.07629v2), Daniel DeTone, Tomasz Malisiewicz, Andrew Rabinovich

This paper presents a self-supervised framework for training interest point
detectors and descriptors suitable for a large number of multiple-view geometry
problems in computer vision. As opposed to patch-based neural networks, our
fully-convolutional model operates on full-sized images and jointly computes
pixel-level interest point locations and associated descriptors in one forward
pass. We introduce Homographic Adaptation, a multi-scale, multi-homography
approach for boosting interest point detection accuracy and performing
cross-domain adaptation (e.g., synthetic-to-real). Our model, when trained on
the MS-COCO generic image dataset using Homographic Adaptation, is able to
repeatedly detect a much richer set of interest points than the initial
pre-adapted deep model and any other traditional corner detector. The final
system gives rise to strong interest point repeatability on the HPatches
dataset and outperforms traditional descriptors such as ORB and SIFT on point
matching accuracy and on the task of homography estimation.
