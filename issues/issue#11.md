# GameGAN: NVIDIA recreates PAC-MAN

GameGAN, a generative adversarial network trained on 50,000 PAC-MAN episodes, produces a fully functional version of the dot-munching classic without an underlying game engine.

- [Read more: NVIDIA Blog](https://blogs.nvidia.com/blog/2020/05/22/gamegan-research-pacman-anniversary/)

[<p align="center"><img src="https://github.com/Machine-Learning-Tokyo/AI-ML-Newsletter/blob/master/images/nvidia_pacman.gif" width="600"></p>](https://blogs.nvidia.com/blog/2020/05/22/gamegan-research-pacman-anniversary/)


# ACL 2020 announced accepted papers

The 2020 Annual Conference of the Association for Computational Linguistics (ACL) announced this year's accepted papers. 571 Long Papers and 208 Short Papers out of 3,088 submissions were accepted, an acceptance rate of 25.2 % this year. Originally scheduled to be held in Seattle, USA, ACL 2020 will be a virtual conference held online from July 5 to 10, due to COVID-19. [Source](https://syncedreview.com/2020/05/20/acl-2020-announces-its-779-accepted-papers/) 

- See ACL list of [accepted papers](https://acl2020.org/program/accepted/).

[<p align="center"><img src="https://github.com/Machine-Learning-Tokyo/AI-ML-Newsletter/blob/master/images/acl.png" width="600"></p>](https://acl2020.org/program/accepted/)


# NVIDIA released a new GPU: A100
NVIDIA unveiled a new GPU at GTC 2020 Keynote: NVIDIA GTX A100. A100 is the world's first 5 petaflops system that packages the power of an entire data center into a unified platform for AI training, inference, and analytics. NVIDIA GTX A100 has:

- 40GB of VRAM
- 6912 FP32 CUDA cores
- 54.2 Billion transistors
- INT8 OPs (624 TOPs) which is the first time we see this in NVIDIA GPUs.


[<img src="https://github.com/Machine-Learning-Tokyo/AI-ML-Newsletter/blob/master/images/nvidia-dgx-a100-2.png" width="430"/> ](https://www.nvidia.com/en-us/data-center/a100/)
[<img src="https://github.com/Machine-Learning-Tokyo/AI-ML-Newsletter/blob/master/images/nvidia-dgx-a100-1.png" width="430"/> ](https://www.nvidia.com/en-us/data-center/a100/)



[Source](https://www.nvidia.com/en-us/data-center/a100/) | [GTC 2020 Keynote](https://www.youtube.com/watch?v=bOf2S7OzFEg&list=PLZHnYvH1qtOZ2BSwG4CHmKSVHxC2lyIPL&index=2&t=0s&linkId=100000012351818)

# Hugging Face models' performance visualization
[Hugging Face](https://huggingface.co) and [Weights & Biases](https://www.wandb.com) published a python notebook on how to visualize s psrticular Hugging Face model performance. You can compare hyperparameters, output metrics, and system stats like GPU utilization across your models.

W&B is like GitHub for machine learning models— save machine learning experiments to your private, hosted dashboard. Experiment quickly with the confidence that all the versions of your models are saved for you, no matter where you're running your scripts.

[<p align="center"><img src="https://github.com/Machine-Learning-Tokyo/AI-ML-Newsletter/blob/master/images/hugging_face_wandb.gif" width="600"></p>](https://www.wandb.com)

[Step-by-step guide](https://app.wandb.ai/jxmorris12/huggingface-demo/reports/A-Step-by-Step-Guide-to-Tracking-Hugging-Face-Model-Performance--VmlldzoxMDE2MTU) | [Google Colab notebook](https://colab.research.google.com/drive/1NEiqNPhiouu2pPwDAVeFoN4-vTYMz9F8?usp=sharing#scrollTo=DKpiNY516JUf)


# The Big Bad NLP Database
The Big Bad NLP Database contains more than 400 NLP related datasets spanning multiple languages and different tasks. It is managed by [Quantum Stat](https://quantumstat.com). If you are working and NLP tasks and are seeking for datasets you may want to check it out.

[<p align="center"><img src="https://github.com/Machine-Learning-Tokyo/AI-ML-Newsletter/blob/master/images/big_bad_nlp_db.png" width="600"></p>](https://datasets.quantumstat.com)


[The Big Bad NLP Database](https://datasets.quantumstat.com) | [Quantum Stat](https://quantumstat.com)


# OSS release of pytorch-pfn-extras

The Tokyo-based AI Startup Preferred Networks released pytorch-pfn-extras, an open-source library that supports research and development in deep learning using PyTorch. The new library is part of PFN’s ongoing effort to strengthen its ties with the PyTorch developer community as well as Optuna™, the open-source hyperparameter optimization framework for machine learning, which recently joined the PyTorch Ecosystem.

Source: [PFN](https://preferred.jp/en/news/pr20200512/)


# Keras's new website has been launched
Keras is an API designed for human beings, not machines. Keras follows best practices for reducing cognitive load: it offers consistent & simple APIs, it minimizes the number of user actions required for common use cases, and it provides clear & actionable error messages. It also has extensive documentation and developer guides.

Now, Keras has a new website, which includes a 100% refreshed list of developer guides and code examples.

[<p align="center"><img src="https://github.com/Machine-Learning-Tokyo/AI-ML-Newsletter/blob/master/images/keras.png" width="600"></p>](https://keras.io)


- [keras.io](https://keras.io)
- [Source: Francois Chollet](https://twitter.com/fchollet/status/1258789849030463488?s=20)


# Reinforcement Learning with Augmented Data

UC Berkeley, BAIR released **RAD – Reinforcement Learning with Augmented Data** (Michael Laskin, Kimin Lee*, Adam Stooke, Lerrel Pinto, Pieter Abbeel, Aravind Srinivas).

"We perform the first extensive study of image augmentation in the RL setting and show, surprisingly, that simple RL algorithms with augmented data achieve state-of-the-art results for data-efficiency on DeepMind control and test-time generalization on OpenAI ProcGen environments."

- [Source: UC Berkeley – RAD](https://mishalaskin.github.io/rad/)

[<p align="center"><img src="https://github.com/Machine-Learning-Tokyo/AI-ML-Newsletter/blob/master/images/rad.png" width="600"></p>](https://mishalaskin.github.io/rad/)


# CNN Explainer

CNN Explainer is an interactive visualization tool to learn, interpret and visualize CNN networks. It runs a pre-trained CNN in the browser. The CNN Explainer was created by Jay Wang, Robert Turko, Omar Shaikh, Haekyu Park, Nilaksh Das, Fred Hohman, Minsuk Kahng, and Polo Chau, which was the result of a research collaboration between Georgia Tech and Oregon State.

- [Live Demo](https://poloclub.github.io/cnn-explainer/) | [Video](https://www.youtube.com/watch?v=HnWIHWFbuUQ&feature=emb_logo) | [Code](https://github.com/poloclub/cnn-explainer) | [Paper](https://arxiv.org/abs/2004.15004)

[<p align="center"><img src="https://github.com/Machine-Learning-Tokyo/AI-ML-Newsletter/blob/master/images/cnn_explainer.gif" width="400"></p>](https://poloclub.github.io/cnn-explainer/)
