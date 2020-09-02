# TensorFlow Lite Micro support on the ESP32
Tensorflow team announced TensorFlow Lite Micro support for the ESP32 chipset. 

- the ESP32 is a Wi-Fi/BT/BLE enabled MCU (micro-controller) that is widely used by hobbyists and makers to build cool and interesting projects that sense or modify real world data/object

- it is commonly deployed in smart home appliances like light bulbs, switches, refrigerators, and air conditioners to provide connectivity.  

[<p align="center"><img src="https://github.com/Machine-Learning-Tokyo/AI-ML-Newsletter/blob/master/images/tflite_esp32.gif" width="600" /></p>](https://blog.tensorflow.org/2020/08/announcing-tensorflow-lite-micro-esp32.html?m=1)

📌 Source: [Tensorflow Blog](https://blog.tensorflow.org/2020/08/announcing-tensorflow-lite-micro-esp32.html?m=1)

# TF-Coder
Google Research introduced a TF-Coder — a tool that writes tricky TensorFlow expressions for you.

- it helps you to write tensor manipulations in TensorFlow. 

- simply provide an input/output example of the desired behavior, and leave the rest to TF-Coder!

<p> <img src="https://github.com/Machine-Learning-Tokyo/AI-ML-Newsletter/blob/master/images/tf-coder.png"/> </p>

- try it out on [Google Colab notebook](https://colab.research.google.com/github/google-research/tensorflow-coder/blob/master/TF-Coder_Colab.ipynb?linkId=98162088)  

📌 Source: [Google Research](https://blog.tensorflow.org/2020/08/introducing-tensorflow-coder-tool.html?linkId=98162087)

---

# Objax: a new high-level JAX API

- Objax is a new high-level JAX API with a PyTorch-like interface. It pursues the quest for the simplest design and code that’s as easy as possible to extend without sacrificing performance.

- [David Berthelot](https://twitter.com/D_Berthelot_ML) is the creator of Objax, and he says that the Objax is purely object oriented (while other frameworks are not really) and Objax's philosophy is a simplicity and performance.

- Objax is meant to be owned by the community. The code simplicity itself is meant to have non CS experts feel comfortable contributing. This design is for researchers and students.



📌 Source: [Objax](https://github.com/google/objax) | [objax.readthedocs.io](https://objax.readthedocs.io/en/latest/index.html)


---

# Apple's AI/ML residency program

- Apple has announced an AI/ML residency program. The program invites experts in various fields to apply their expertise to build revolutionary machine learning empowered products and experiences.

- The year-long program will welcome residents with STEM graduate degrees or equivalent industry experience and niche expertise — like design, linguistics, neuroscience, or psychology. 

- The program aims to invest in the resident’s technical and theoretical machine learning development, and help advance their professional careers.

📌 Source: [Apple Machine Learning Research](https://machinelearning.apple.com/updates/introducing-aiml-residency-program)

---
 
# Semantic MapNet

- The first audio-visual platform for embodied AI. With this new platform, researchers can train AI agents in 3D environments with highly realistic acoustics. 
- Facebook AI releases a Semantic MapNet — a new framework for building top-down semantic maps and spatio-semantic memories (“mental maps”) from egocentric observations. 

- This new research enables agents to learn and reason about how to navigate to objects seen during a tour (e.g., find the table) or answer questions about the space (e.g., how many chairs are in the house?).

<p align="center">
  <img src="https://github.com/Machine-Learning-Tokyo/AI-ML-Newsletter/blob/master/images/smnet-3.gif" width="500" />
  <img src="https://github.com/Machine-Learning-Tokyo/AI-ML-Newsletter/blob/master/images/smnet-1.gif" width="500" />
</p>

📌 Source: [Facebook AI](https://ai.facebook.com/blog/new-milestones-in-embodied-ai#)

---

# Danfo.js: a Pandas-like Library in JavaScript

- Danfo.js is an open-source JavaScript library that provides high-performance, intuitive, and easy-to-use data structures for manipulating and processing structured data. Danfo.js is heavily inspired by the Python Pandas library and provides a similar interface/API. This means that users familiar with the Pandas API and know JavaScript can easily pick it up.

- One of the main goals of Danfo.js is to bring data processing, machine learning and AI tools to JavaScript developers. Open-source libraries like Numpy and Pandas revolutionise the ease of manipulating data in Python and lots of tools were built around them, thus driving the bubbling ecosystem of ML in Python.

[<p align="center"><img src="https://github.com/Machine-Learning-Tokyo/AI-ML-Newsletter/blob/master/images/Danfo_JS.gif" width="600" /></p>](https://blog.tensorflow.org/2020/08/introducing-danfo-js-pandas-like-library-in-javascript.html?linkId=98080391)

📌 Source: [TensorFlow Blog](https://blog.tensorflow.org/2020/08/introducing-danfo-js-pandas-like-library-in-javascript.html?linkId=98080391)

---

# ECCV 2020 Conference
16th European conference on Computer Vision (ECCV 2020) is taking place, fully online, between 23 and 28 August, 2020.

[<p align="center"><img src="https://github.com/Machine-Learning-Tokyo/AI-ML-Newsletter/blob/master/images/ECCV2020.png" width="600" /></p>](https://eccv2020.eu)


**ECCV 2020 Awards:**
- Koenderink Award: 
  - [“Improving the Fisher Kernel for Large-Scale Image Classification” by Florent Perronnin, Jorge Sánchez and Thomas Mensink](https://lear.inrialpes.fr/pubs/2010/PSM10/PSM10_0766.pdf)
  - [“Brief: Binary robust independent elementary features” by Michael Calonder, Vincent Lepetit, Christoph Strecha, and Pascal Fua](https://www.cs.ubc.ca/~lowe/525/papers/calonder_eccv10.pdf)

- PAMI Mark Everingham Prize:
  - [“Multiple Datasets” by Antonio Torralba](https://groups.csail.mit.edu/vision/torralbalab/)
  - [“COLMAP SFM and MVS software library” by Johannes Schönberger](https://colmap.github.io)
  
- ECCV’20 Best Demo:
  - [“Inter-Homines” by Rita Cucchiara, Matteo Fabbri, and Simone Calderara, University of Modena and Reggio Emilia, Italy](https://arxiv.org/pdf/2007.10243.pdf)
  
- ECCV’20 Best Paper Honorable Mention:
  - [“Towards Streaming Image Understanding” by Mengtian Li, Yu-Xiong Wang, Deva Ramanan](https://arxiv.org/abs/2005.10420)
  - [“NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis” by Ben Mildenhall, Pratul P. Srinivasan, Matthew Tancik, Jonathan T. Barron, Ravi Ramamoorthi, Ren Ng](https://arxiv.org/abs/2003.08934)
  
- ECCV’20 Best Paper:
  - [“RAFT: Recurrent All-Pairs Field Transforms for Optical Flow” by Zachary Teed, Jia Deng](https://arxiv.org/abs/2003.12039)
  

---

# Model Card Toolkit for Easier Model Transparency Reporting
- Machine learning (ML) model transparency is important across a wide variety of domains that impact peoples’ lives, from healthcare to personal finance to employment.

[<p align="center"><img src="https://github.com/Machine-Learning-Tokyo/AI-ML-Newsletter/blob/master/images/ModelCardToolkit.jpg" width="600" /></p>](https://ai.googleblog.com/2020/07/introducing-model-card-toolkit-for.html)

- Google has released a toolkit which it hopes will bring some transparency to AI models.

- Model Card Toolkit aims to step in and facilitate AI model transparency reporting for developers, regulators, and downstream users.


📌 Source: [Google AI Blog](https://ai.googleblog.com/2020/07/introducing-model-card-toolkit-for.html) | [AI News]( https://artificialintelligence-news.com/2020/07/28/musk-predicts-ai-superior-humans-five-years/)

---

# Real World Reinforcement Learning (RWRL) simulation suite
- Existing RL benchmarks do not capture many of the challenges found in applied systems and products. Introducing the Real-World RL(RWRL) simulation suite, developed to accelerate research on these challenges

[<p align="center"><img src="https://github.com/Machine-Learning-Tokyo/AI-ML-Newsletter/blob/master/images/RWRL_Overview.gif" width="600" /></p>](https://ai.googleblog.com/2020/08/a-simulation-suite-for-tackling-applied.html)


- The RWRL suite is a set of simulated tasks inspired by applied reinforcement learning challenges, the goal of which is to enable fast algorithmic iterations for both researchers and practitioners, without having to run slow, expensive experiments on real-systems. 

- RWRL supports a subset of the DeepMind Control Suite domains, but the goal is to broaden the suite to support an even more diverse domain set.

📌 Source: [Google AI Blog](https://ai.googleblog.com/2020/08/a-simulation-suite-for-tackling-applied.html) | [DeepMind's tweet](https://twitter.com/DeepMind/status/1293607821859336195?s=20)

---

# Google offers career certificates equivalent to 4-year degree

- Google announced three new online certificate programs in data analytics, project management and user experience design. Google says that the certificates are the equivalent to a four-year degree and classes will be taught by Google employees themselves.

- The courses will be offered by Coursera. The courses will take about six months to complete and the certificates will be “remarkably affordable” compared to a traditional four-year university.

- Scholarships will be offered to those who qualify for financial aid.


[<p align="center"><img src="https://github.com/Machine-Learning-Tokyo/AI-ML-Newsletter/blob/master/images/google_certificates.png" width="600" /></p>](https://twitter.com/Google/status/1282677217307369474?s=20)



📌 Source: [www.click2houston.com](https://www.click2houston.com/news/national/2020/07/14/google-will-offer-career-certificates-equivalent-to-4-year-degrees-in-data-analytics-project-management/) | [Tweet](https://twitter.com/Google/status/1282677217307369474?s=20)


