# GPT-2 and BERT on-device with Swift and CoreML

Large transformers models can now live on the edge: HuggingFace ported OPenAI's GPT-2 to run on-device (using Swift and CoreML on iOS). The GIF below is GPT-2 running locally (no network) on the device!

**Code:** https://github.com/huggingface/swift-coreml-transformers

This repository contains:

**For BERT:**
- A pretrained Google BERT model fine-tuned for Question answering on the SQuAD dataset.
- Swift implementations of the BERT tokenizer (BasicTokenizer and WordpieceTokenizer) and SQuAD dataset parsing utilities. 
- A demo question answering app.

**For GPT-2::**
- A conversion script from Pytorch trained GPT-2 models (see our pytorch-transformers repo) to CoreML models.
- The GPT-2 generation model itself, including decoding strategies (greedy and TopK are currently implemented) and GPT-2 Byte-pair encoder and decoder.
- A neat demo app showcasing on-device text generation.

[<p align="center"><img src="https://github.com/Machine-Learning-Tokyo/AI-ML-Newsletter/blob/master/images/coreml-gpt2.gif" width="800"></p>](https://openai.com/blog/microsoft/?fbclid=IwAR0-YKK0tlUPB8xUNRSUzwOgCaxaBiGWdvJMcmLymJirC31cakknUoGUd-8)

# Microsoft invests $1B in OpenAI 

Microsoft is investing $1 billion in OpenAI to support us building artificial general intelligence (AGI). "We’ll jointly develop new Azure AI supercomputing technologies, and Microsoft will become our exclusive cloud provider—so we’ll be working hard together to further extend Microsoft Azure’s capabilities in large-scale AI systems."

[<p align="center"><img src="https://github.com/Machine-Learning-Tokyo/AI-ML-Newsletter/blob/master/images/ms-openai.png" width="800"></p>](https://openai.com/blog/microsoft/?fbclid=IwAR0-YKK0tlUPB8xUNRSUzwOgCaxaBiGWdvJMcmLymJirC31cakknUoGUd-8)

# pip install pytorch-transformers

PyTorch-Transformers (formely known as pytorch-pretrained-bert) is a library of state-of-the-art pre-trained models for Natural Language Processing (NLP).

The library currently contains PyTorch implementations, pre-trained model weights, usage scripts and conversion utilities for the following models:

- **BERT (Google)** released with the paper BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding by Jacob Devlin, Ming-Wei Chang, Kenton Lee and Kristina Toutanova.
- **GPT (OpenAI)** released with the paper Improving Language Understanding by Generative Pre-Training by Alec Radford, Karthik Narasimhan, Tim Salimans and Ilya Sutskever.
- **GPT-2 (OpenAI)** released with the paper Language Models are Unsupervised Multitask Learners by Alec Radford*, Jeffrey Wu*, Rewon Child, David Luan, Dario Amodei** and Ilya Sutskever**.
- **Transformer-XL (Google/CMU)** released with the paper Transformer-XL: Attentive Language Models Beyond a Fixed-Length Context by Zihang Dai*, Zhilin Yang*, Yiming Yang, Jaime Carbonell, Quoc V. Le, Ruslan Salakhutdinov.
- **XLNet (Google/CMU)** released with the paper ​XLNet: Generalized Autoregressive Pretraining for Language Understanding by Zhilin Yang*, Zihang Dai*, Yiming Yang, Jaime Carbonell, Ruslan Salakhutdinov, Quoc V. Le.
- **XLM (Facebook)** released together with the paper Cross-lingual Language Model Pretraining by Guillaume Lample and Alexis Conneau.

[<p align="center"><img src="https://github.com/Machine-Learning-Tokyo/AI-ML-Newsletter/blob/master/images/pytorchnlp.png" width="600"></p>](https://github.com/huggingface/pytorch-transformers/releases/tag/v1.0.0)

# ICLR 2020 Call for Papers

1st Call for Papers for #ICLR2020. See the full call online, https://iclr.cc/Conferences/2020/CallForPapers Submission deadline Wednesday, 25 September 2019, 6pm East Africa Time

# New fast.ai course: Natural Language Processing
Applications covered include topic modeling, classfication (identifying whether the sentiment of a review is postive or negative), language modeling, and translation. The course teaches a blend of traditional NLP topics (including regex, SVD, naive bayes, tokenization) and recent neural network approaches (including RNNs, seq2seq, attention, and the transformer architecture), as well as addressing urgent ethical issues, such as bias and disinformation. Topics can be watched in any order.
[<p align="center"><img src="https://github.com/Machine-Learning-Tokyo/AI-ML-Newsletter/blob/master/images/fastai1.png" width="600"></p>](https://www.fast.ai/2019/07/08/fastai-nlp/)



# Google ML Summit Tokyo

The Google ML Summit was held in July at Roppongi Hills with talks from Jeff Dean, Laurence Moroney, Paige Bailey, Heiga Zen, ...
[<p align="center"><img src="https://github.com/Machine-Learning-Tokyo/AI-ML-Newsletter/blob/master/images/googlemlsummit.png" width="600"></p>](https://events.withgoogle.com/mlsummit-tokyo-vol3/)
