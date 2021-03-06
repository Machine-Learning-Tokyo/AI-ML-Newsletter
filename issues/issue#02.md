# Yann LeCun, Geoffrey Hinton and Yoshua Bengio win Turing Award

Yann LeCun, Geoffrey Hinton and Yoshua Bengio - three Pioneers in Artificial Intelligence won the Turing Award for their work on neural networks. They will share $1 million for what many consider the Nobel Prize of computing.

[<p align="center"><img src="https://github.com/Machine-Learning-Tokyo/AI-ML-Newsletter/blob/master/images/LeCun_Hinton_Bengio.png" width="600"></p>](https://www.nytimes.com/2019/03/27/technology/turing-award-ai.html)

Source: The New York Times

# NVIDIA introduces Jetson Nano - a small AI computer

NVIDIA announced the Jetson Nano, a small AI computer that delivers 472 GFLOPS of compute performance for running modern AI workloads and is highly power-efficient, consuming only 5 watts. It comes in two versions — the $99 devkit for developers, makers and enthusiasts and the $129 production-ready module for companies looking to create mass-market edge systems. [[Read more]](https://nvidianews.nvidia.com/news/nvidia-announces-jetson-nano-99-tiny-yet-mighty-nvidia-cuda-x-ai-computer-that-runs-all-ai-models?ncid=so-twi-gj-78738&linkId=100000005468164)

<p align="center">
  <img src="https://github.com/Machine-Learning-Tokyo/AI-ML-Newsletter/blob/master/images/nvidia.png" width="600">
</p>


# OpenAI created OpenAI LP, a for-profit company

OpenAI restructured from non-profit to "capped-profit" and explained its decision in a blog post:

*We’ll need to invest billions of dollars in upcoming years into large-scale cloud compute, attracting and retaining talented people, and building AI supercomputers.*


*We want to increase our ability to raise capital while still serving our mission, and no pre-existing legal structure we know of strikes the right balance. Our solution is to create OpenAI LP as a hybrid of a for-profit and nonprofit—which we are calling a “capped-profit” company.*

<p align="center">
  <img src="https://github.com/Machine-Learning-Tokyo/AI-ML-Newsletter/blob/master/images/OpenAILP2.png" width="600">
  <img src="https://github.com/Machine-Learning-Tokyo/AI-ML-Newsletter/blob/master/images/OpenAILP1.png" width="600">
</p>

### [Read more on TC](https://techcrunch.com/2019/03/11/openai-shifts-from-nonprofit-to-capped-profit-to-attract-capital/)

- The company justifies this rather high profit “cap” by saying that if it succeeds in creating a working artificial general intelligence (AGI is a poorly defined concept that is nonetheless perhaps the Holy Grail of current AI research), “we expect to generate orders of magnitude more value than we’d owe to people who invest in or work at OpenAI LP.”

### [Original blog post on OpenAI](https://openai.com/blog/openai-lp/)

# TensorFlow 2.0 Alpha release
The TF 2.0 Alpha release is available now. This is an early version meant to share with users what the TensorFlow 2.0 API will be like, to gather feedback, and to identify and fix issues. Below are some of the key enhancements:

- Eager execution as a central feature of 2.0. It aligns users’ expectations about the programming model better with TensorFlow practice and should make TensorFlow easier to learn and apply.
- Keras tightly integrated with the TensorFlow ecosystem, and has support for Eager execution, tf.data API, tf.distribute.MirroredStrategy for multi-GPU training, TensorBoard visualization, and TF Lite and TF.js conversion.
- Starter list of TF-Hub models loadable in TF 2.0.
- Autograph making it easier to write models with custom control flow ops and getting graph performance with tf.function.

### [Read more: TF 2.0 Roadmap](https://www.tensorflow.org/community/roadmap)

# GauGAN Turns Doodles into Photorealistic Landscapes
NVIDIA Research developed a GAN-based tool that turns rough doodles into photorealistic landscapes. The tool leverages generative adversarial networks to convert segmentation maps into lifelike images.

<p align="center">
  <img src="https://github.com/Machine-Learning-Tokyo/AI-ML-Newsletter/blob/master/images/GauGan.png" width="600">
</p>


# New to Microsoft 365
Nice ML usecase for automatic data entry: You can now take a picture of a printed data table and automatically convert it into a fully editable Excel spreadsheet. Microsoft is rolling out to Android users, coming soon to iOS. 

http://msft.social/kH8GuB

<p align="center">
  <img src="https://github.com/Machine-Learning-Tokyo/AI-ML-Newsletter/blob/master/images/Microsoft.gif">
</p>

# Google open sourced GPipe, an Open Source Library for Efficiently Training Large-scale Neural Network Models
GPipe is a distributed machine learning library that uses synchronous stochastic gradient descent and pipeline parallelism for training, applicable to any DNN that consists of multiple sequential layers. GPipe allows researchers to easily deploy more accelerators to train larger models and to scale the performance without tuning hyperparameters.

https://ai.googleblog.com/2019/03/introducing-gpipe-open-source-library.html

# OpenAI released Activation Atlases

Activation Atlases: a new technique for visualizing what interactions between neurons can represent. Activation atlases build on feature visualization, a technique for studying what the hidden layers of neural networks can represent.

<p align="center">
  <img src="https://github.com/Machine-Learning-Tokyo/AI-ML-Newsletter/blob/master/images/OpenAI.png">
</p>

💻Blog: https://blog.openai.com/introducing-activation-atlases/

📝Paper: https://distill.pub/2019/activation-atlas

🔤Code: https://github.com/tensorflow/lucid/#activation-atlas-notebooks

🗺️Demo: https://distill.pub/2019/activation-atlas/app.html
