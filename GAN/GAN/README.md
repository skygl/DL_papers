# Generative Adversarial Networks

<br>

- **Author** : Goodfellow, Ian, Jean Pouget-Abadie, Mehdi Mirza, Bing Xu, David Warde-Farley, Sherjil Ozair, Aaron Courville, and Yoshua Bengio
- **NIPS 2014**
- [paper link](https://arxiv.org/abs/1406.2661)

<br>

<br>

## Abstract

<br>

We propose a new framework for estimating generative models via an adversarial process, in which we simultaneously train two models: a generative model G that captures the data distribution, and a discriminative model D that estimates the probability that a sample came from the training data rather than G. The training procedure for G is to maximize the probability of D making a mistake. This framework corresponds to a minimax two-player game. In the space of arbitrary functions G and D, a unique solution exists, with G recovering the training data distribution and D equal to 1/2 everywhere. In the case where G and D are defined by multilayer perceptrons, the entire system can be trained with backpropagation. There is no need for any Markov chains or unrolled approximate inference networks during either training or generation of samples. Experiments demonstrate the potential of the framework through qualitative and quantitative evaluation of the generated samples.



## Environment



- Python : 3.8.10
- Pytorch : 1.7.1



## Output



**In Training**

![GAN_output](./GAN_training.gif) 



**Output**

![GAN_output](./GAN_output.jpg)
