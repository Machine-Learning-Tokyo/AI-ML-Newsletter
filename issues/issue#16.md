# VLFeat gets an award

- Andrea Vedaldi and Brian Fulkerson receives 2020 ACM SIGMM Test of Time Paper Award for VLFeat.

- VLFeat is one of the earliest open and portable library of computer vision algorithms. The library had been used by most of the Computer Vision researchers before the latest deep learning libraries showed up.

[<p align="center"> <img src="https://github.com/Machine-Learning-Tokyo/AI-ML-Newsletter/blob/master/images/VLFeat.png" width="600" /> </p>](https://www.vlfeat.org/)


- 2020 ACM SIGMM Test of Time Paper Award is going to be presented every year, starting in 2020, to the authors of the paper published a decade ago at an SIGMM sponsored conference. The award recognizes the paper that has had the most impact and influence on the field of Multimedia in terms of research, development, product or ideas, during the intervening years, as selected by a selection committee.


📌 Source: [sigmm.org](http://sigmm.org/Awards/testoftime)


# M2M-100 — multilingual machine translation

- Facebook AI introduced the first multilangual machine translation model — M2M-100

- The model can translate between any pair of 100 languages without relying on English data

- The team open-sourced the model, training and evaluation set up.

[<p align="center"> <img src="https://github.com/Machine-Learning-Tokyo/AI-ML-Newsletter/blob/master/images/M2M-100.png" width="600" /> </p>](https://ai.facebook.com/blog/introducing-many-to-many-multilingual-machine-translation)

📌 Source: [Facebook AI](https://ai.facebook.com/blog/introducing-many-to-many-multilingual-machine-translation)




# TensorSensor

- TensorSensor is a library that clarifies exceptions by augmenting messages and visualizing Python code to indicate the shape of tensor variables.

- TensorSensor works with TensorFlow, PyTorch, Numpy as well as higher-level libraries like Keras and fastai.

```
import tsensor
import numpy as np

W = np.random.rand(764, 100)  # This should be (100, 674) which would rise an exception
b = np.random.rand(100, 1)
X = np.random.rand(200, 764) 

with tsensor.clarify():
    Y = W @ X.T + b
```

[<p align="center"> <img src="https://github.com/Machine-Learning-Tokyo/AI-ML-Newsletter/blob/master/images/tsensor.png" width="600" /> </p>](https://explained.ai/tensor-sensor/index.html)


📌 Source: [Terence Parr](https://twitter.com/the_antlr_guy?s=20) | [explained.ai](https://explained.ai/tensor-sensor/index.html)


# NVIDIA Maxine

NVIDIA introduces Maxine, "a fully accelerated platform for developers to build and deploy AI-powered features in video conferencing services using state-of-the-art models that run in the cloud. Applications based on Maxine can reduce video bandwidth usage down to one-tenth of H.264 using AI video compression." 

[<p align="center"> <img src="https://github.com/Machine-Learning-Tokyo/AI-ML-Newsletter/blob/master/images/nvidiamaxine.png" width="600" /> </p>](https://www.youtube.com/watch?v=eFK7Iy8enqM&feature=emb_title)

📌 Source: [NVIDIA](https://developer.nvidia.com/maxine)

# NeurIPS 2020 Accepted Papers

- 1903 accepted papers, with a 20.1% acceptance rate.
- Find all papers here: [NeurIPS 2020 Accepted Papers](https://neurips.cc/Conferences/2020/AcceptedPapersInitial)

<p align="center"> <img src="https://github.com/Machine-Learning-Tokyo/AI-ML-Newsletter/blob/master/images/neurips1.png" width="800" /> </p>
<p align="center"> <img src="https://github.com/Machine-Learning-Tokyo/AI-ML-Newsletter/blob/master/images/neurips2.png" width="800" /> </p>


📌 Images: [@SergeyI49013776](https://twitter.com/SergeyI49013776/status/1313490160479350784)
