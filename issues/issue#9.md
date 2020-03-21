
# NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis
Ben Mildenhall, Pratul P. Srinivasan, Matthew Tancik, Jonathan T. Barron, Ravi Ramamoorthi, Ren Ng

[Paper](https://arxiv.org/abs/2003.08934) | [Website](http://www.matthewtancik.com/nerf)

**- From the orignal abstract:**

NeRF achieves state-of-the-art results for synthesizing novel views of complex scenes by optimizing an underlying continuous volumetric scene function using a sparse set of input views. The algorithm represents a scene using a fully-connected (non-convolutional) deep network, whose input is a single continuous 5D coordinate and whose output is the volume density and view-dependent emitted radiance at that spatial location. Views are synthesized by querying 5D coordinates along camera rays and classic volume rendering techniques are used to project the output colors and densities into an image. Because volume rendering is naturally differentiable, the only input required to optimize the representation is a set of images with known camera poses. The researchers describe how to effectively optimize neural radiance fields to render photorealistic novel views of scenes with complicated geometry and appearance, and demonstrate results that outperform prior work on neural rendering and view synthesis. 

[<p align="center"><img src="https://github.com/Machine-Learning-Tokyo/AI-ML-Newsletter/blob/master/images/fullmagnolia_200k_rgb.gif" width="400"></p>](http://www.matthewtancik.com/nerf)


# Google announced TensorFlow Developer Certificate
- helps developers ML to showcase their ML proficiency
- helps companies hire ML developers to solve challenging problems
- this certificate program requires an understanding of building basic TensorFlow models using Computer Vision, Sequence modeling, and Natural Language Processing
- by passing the exam you will receive an official TensorFlow Developer Certificate and badge to showcase your skill set and can share on LinkedIn or other social networks   
- Source: [TensorFlow Blog](https://blog.tensorflow.org/2020/03/introducing-tensorflow-developer-certificate.html)

[<p align="center"><img src="https://github.com/Machine-Learning-Tokyo/AI-ML-Newsletter/blob/master/images/tf_certified_developer.png" width="200"></p>](https://blog.tensorflow.org/2020/03/introducing-tensorflow-developer-certificate.html)

# Google announced a new neural-network library: Neural Tangents
- easy-to-use, open-source neural network library
- provides researchers with an opportunity of building an (in)finite widths versions of neural networks simultaneously
- Source: [Google AI Blog](https://ai.googleblog.com/2020/03/fast-and-easy-infinitely-wide-networks.html?m=1) 
  
[<p align="center"><img src="https://github.com/Machine-Learning-Tokyo/AI-ML-Newsletter/blob/master/images/google_neural_tangent.gif" width="600"></p>](https://ai.googleblog.com/2020/03/fast-and-easy-infinitely-wide-networks.html?m=1)
  


# Researchers from Microsoft have created AI ethics checklist with nearly 50 engineers from a dozen tech companies
- Source: [Venture Beat](https://venturebeat.com/2020/03/10/microsoft-researchers-create-ai-ethics-checklist-with-ml-practitioners-from-a-dozen-tech-companies/)



# ICLR 2020 as a fully virtual conference due to the coronavirus spreading

Due to growing concerns about COVID-19, ICLR2020 will cancel its physical conference this year, instead shifting to a fully virtual conference. We were very excited to hold ICLR in Addis Ababa, and it is disappointing that we will not all be able to come together in person in April. This unfortunate event does give us the opportunity to innovate on how to host an effective remote conference. The organizing committees are now working to create a virtual conference that will be valuable and engaging for both presenters and attendees. 

Source: [ICLR 2020](https://iclr.cc/Conferences/2020/virtual)

[<p align="center"><img src="https://github.com/Machine-Learning-Tokyo/AI-ML-Newsletter/blob/master/images/iclr2020.png" width="600"></p>](https://iclr.cc/Conferences/2020/virtual)


# Google announced TensorFlow Quantum: An Open Source Library for Quantum Machine Learning  
Google announced the release of TensorFlow Quantum ([TFQ](https://www.tensorflow.org/quantum)), in collaboration with [University of Waterloo](https://uwaterloo.ca), [X](https://x.company), and [Volkswagen](https://www.volkswagenag.com/en/news/2018/06/volkswagen-tests-quantum-computing-in-battery-research.html#) an open-source library for the rapid prototyping of quantum ML models.
- TFQ provides the tools to bring the quantum computing and machine learning research communities together
    - to control and and model natural and artificial quantum systems
    - for example, Noisy Intermediate Scale Quantum (NISQ) processors with ~50-100 qubits
- TFQ integrates [Cirq](https://ai.googleblog.com/2018/07/announcing-cirq-open-source-framework.html) and TensorFlow:
    - offers high-level abstractions for the design and implementation of both discriminative generative quantum-classical models  

    - offers high-level abstractions for the design and implementation of both discriminative generative quantum-classical models
- Source: [Google AI Blog](https://ai.googleblog.com/2020/03/announcing-tensorflow-quantum-open.html)

