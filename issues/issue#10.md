# ML Code Completeness Checklist
[Papers with Code](https://paperswithcode.com), which hosts the collection of paper implementations in one place, compiled the best practices from various popular research repositories - ML Code Completeness Checklist. ML Code Completeness Checklist is now part of the official NeurIPS 2020 code submission process.

The ML Code Completeness Checklist assesses a code repository and checks a code repository for:
* **Dependencies** — does a repository have information on dependencies or instructions on how to set up the environment?
* **Training scripts** — does a repository contain a way to train/fit the model(s) described in the paper?
* **Evaluation scripts** — does a repository contain a script to calculate the performance of the trained model(s) or run experiments on models?
* **Pretrained models** — does a repository provide free access to pretrained model weights?
* **Results** — does a repository contain a table/plot of main results and a script to reproduce those results?

[Source](https://medium.com/paperswithcode/ml-code-completeness-checklist-e9127b168501)

[paperswithcode, releasing-research-code](https://github.com/paperswithcode/releasing-research-code#ml-code-completeness-checklist)


# Image Matching Benchmark and Challenge
The second Image Matching Challenge: seeking the best end-to-end solutions for 3D image reconstruction announced. The winners going to present the approaches at [Local Features and Beyond workshop](https://image-matching-workshop.github.io) at [CVPR2020](http://cvpr2020.thecvf.com).

Reconstructing 3D objects and buildings from a series of images is a well-known problem in computer vision, known as Structure-from-Motion (SfM). It has diverse applications in photography and cultural heritage preservation and powers many services across Google Maps, such as the 3D models created from StreetView and aerial imagery. 

We hope this benchmark, dataset and challenge helps advance the state of the art in 3D reconstruction with heterogeneous images.


Source: [Google AI](https://ai.googleblog.com/2020/04/announcing-2020-image-matching.html?m=1)

Challenge: [Image Matching Challenge - 2020](https://vision.uvic.ca/image-matching-challenge/)

Paper: [Image Matching across Wide Baselines: From Paper to Practice](https://arxiv.org/abs/2003.01587)

[<p align="center"><img src="https://github.com/Machine-Learning-Tokyo/AI-ML-Newsletter/blob/master/images/3d_reconstruction.gif" width="600"></p>](https://ai.googleblog.com/2020/04/announcing-2020-image-matching.html?m=1)


# Waymo: Automated Data Augmentation
#### Building a new augmentation strategy for lidar point clouds

"Each augmentation operation is associated with a probability and specific parameters. For example, the GroundTruthAugmentor has parameters denoting the probability for sampling vehicles, pedestrians, cyclists, whereas the GlobalTranslateNoise operation has parameters for the distortion magnitude of translation operation on x, y and z coordinates.

To automate the process of finding good augmentation policies for lidar point clouds, we created a new automated data augmentation algorithm - Progressive Population Based Augmentation (PPBA). PPBA builds on our previous Population Based Training (PBT) work, where we train neural nets with evolutionary computation, which uses principles similar to Darwin’s Natural Selection Theory. PPBA learns to optimize augmentation strategies effectively and efficiently by narrowing down the search space at each population iteration and adopting the best parameters discovered in past iterations."

Source: [Waymo](https://blog.waymo.com/2020/04/using-automated-data-augmentation-to.html)

[<p align="center"><img src="https://github.com/Machine-Learning-Tokyo/AI-ML-Newsletter/blob/master/images/waymo.gif" width="600"></p>](https://blog.waymo.com/2020/04/using-automated-data-augmentation-to.html)


# ACM Prize in Computing Awarded to AlphaGo Lead David Silver

David Silver was announced to win the 2019 ACM Prize in Computing for breakthrough advances in computer game-playing using deep reinforcement learning. Silver is a Professor at University College London and a Principal Research Scientist at DeepMind. His most highly publicized achievement was leading the team that developed AlphaGo, that defeated the world champion in the game Go. Silver developed AlphaGo aby combining ideas from deep learning, reinforcement learning, traditional tree-search and large-scale computing. AlphaGo is recognized as a milestone in AI research and was ranked by New Scientist magazine as one of the top 10 discoveries of the last decade.

- From: [source](https://awards.acm.org/about/2019-acm-prize)
- Read more about [AlphaGo](https://deepmind.com/research/case-studies/alphago-the-story-so-far)

<p float="left">
  <img src="https://github.com/Machine-Learning-Tokyo/AI-ML-Newsletter/blob/master/images/silver.png" width="200" />
  <img src="https://github.com/Machine-Learning-Tokyo/AI-ML-Newsletter/blob/master/images/alphago.png" width="600" /> 
</p>
