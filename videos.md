### -1, 2017
- [On the Integration of Optical Flow and Action Recognition](http://arxiv.org/abs/1712.08416v1), Laura Sevilla-Lara, Yiyi Liao, Fatma Guney, Varun Jampani, Andreas Geiger, Michael J. Black

Most of the top performing action recognition methods use optical flow as a
"black box" input. Here we take a deeper look at the combination of flow and
action recognition, and investigate why optical flow is helpful, what makes a
flow method good for action recognition, and how we can make it better. In
particular, we investigate the impact of different flow algorithms and input
transformations to better understand how these affect a state-of-the-art action
recognition method. Furthermore, we fine tune two neural-network flow methods
end-to-end on the most widely used action recognition dataset (UCF101). Based
on these experiments, we make the following five observations: 1) optical flow
is useful for action recognition because it is invariant to appearance, 2)
optical flow methods are optimized to minimize end-point-error (EPE), but the
EPE of current methods is not well correlated with action recognition
performance, 3) for the flow methods tested, accuracy at boundaries and at
small displacements is most correlated with action recognition performance, 4)
training optical flow to minimize classification error instead of minimizing
EPE improves recognition performance, and 5) optical flow learned for the task
of action recognition differs from traditional optical flow especially inside
the human body and at the boundary of the body. These observations may
encourage optical flow researchers to look beyond EPE as a goal and guide
action recognition researchers to seek better motion cues, leading to a tighter
integration of the optical flow and action recognition communities.

- [SLAC: A Sparsely Labeled Dataset for Action Classification and  Localization](http://arxiv.org/abs/1712.09374v1), Hang Zhao, Zhicheng Yan, Heng Wang, Lorenzo Torresani, Antonio Torralba

This paper describes a procedure for the creation of large-scale video
datasets for action classification and localization from unconstrained,
realistic web data. The scalability of the proposed procedure is demonstrated
by building a novel video benchmark, named SLAC (Sparsely Labeled ACtions),
consisting of over 520K untrimmed videos and 1.75M clip annotations spanning
200 action categories. Using our proposed framework, annotating a clip takes
merely 8.8 seconds on average. This represents a saving in labeling time of
over 95% compared to the traditional procedure of manual trimming and
localization of actions. Our approach dramatically reduces the amount of human
labeling by automatically identifying hard clips, i.e., clips that contain
coherent actions but lead to prediction disagreement between action
classifiers. A human annotator can disambiguate whether such a clip truly
contains the hypothesized action in a handful of seconds, thus generating
labels for highly informative samples at little cost. We show that our
large-scale dataset can be used to effectively pre-train action recognition
models, significantly improving final metrics on smaller-scale benchmarks after
fine-tuning. On Kinetics, UCF-101 and HMDB-51, models pre-trained on SLAC
outperform baselines trained from scratch, by 2.0%, 20.1% and 35.4% in top-1
accuracy, respectively when RGB input is used. Furthermore, we introduce a
simple procedure that leverages the sparse labels in SLAC to pre-train action
localization models. On THUMOS14 and ActivityNet-v1.3, our localization model
improves the mAP of baseline model by 8.6% and 2.5%, respectively.

- [Detect-and-Track: Efficient Pose Estimation in Videos](http://arxiv.org/abs/1712.09184v1), Rohit Girdhar, Georgia Gkioxari, Lorenzo Torresani, Manohar Paluri, Du Tran

This paper addresses the problem of estimating and tracking human body
keypoints in complex, multi-person video. We propose an extremely lightweight
yet highly effective approach that builds upon the latest advancements in human
detection and video understanding. Our method operates in two-stages: keypoint
estimation in frames or short clips, followed by lightweight tracking to
generate keypoint predictions linked over the entire video. For frame-level
pose estimation we experiment with Mask R-CNN, as well as our own proposed 3D
extension of this model, which leverages temporal information over small clips
to generate more robust frame predictions. We conduct extensive ablative
experiments on the newly released multi-person video pose estimation benchmark,
PoseTrack, to validate various design choices of our model. Our approach
achieves an accuracy of 55.2% on the validation and 51.8% on the test set using
the Multi-Object Tracking Accuracy (MOTA) metric, and achieves state of the art
performance on the ICCV 2017 PoseTrack keypoint tracking challenge.
