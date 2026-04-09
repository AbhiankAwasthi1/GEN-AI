Introduction to Generative AI Lab Series CSET419.

Project Overview

This is a collection of Python code that implements the laboratory work in the CSET419 Introduction to Generative AI course. The projects concentrate on the real-world implementation of deep learning architectures to generate images, natural language process, and fine-tune models.

 Lab Breakdown

In this lab, we will create artistic outputs with the help of Neural Art.
This module examines how artistic images can be generated with Generative Adversarial Networks (GANs). It covers:
* DCGAN and BigGAN implementation.
* Random sampling of the latent space.
A method to visualize transitions between images by interpolating the latent vectors.

The next two labs (Lab 9 and Lab 10) cover sequence and sequential data generation.
These labs are concerned with modeling and the production of sequential data, i.e. text. Key tasks include:
* Preprocessing text data and creating vocabularies on the word level.
Designing and training Recurrent Neural Networks (RNN) and Long Short-Term Memory (LSTM) networks.
Transformer-based sequence prediction models with positional encoding.
Forming new text sequences out of learned patterns through seed inputs.

Fine-tuning GPT-2 to industry applications Lab 11: Fine-Tuning GPT-2 for Industry Applications.
In this lab, it is shown how to fine-tune pre-trained large language models to particular business domains. It includes:
Fine-tuning GPT-2 as e-commerce Product Review Generator.
GPT-2 Finetuning is a Recipe Instruction Generator in food-tech.
* Comparing the outputs of the domain-specific generated content with the baseline models.
* Perplexity and qualitative assessment of model performance.

In this lab, the model is a Generative Model with Attention.<|human|>In this lab, the model is Generative Model with Attention.
This experiment uses a text generation model using a self-attention mechanism to enhance response coherence. It covers:
* Creating a chatbot with an LSTM Encoder-Decoder structure.
* Adding an attention layer to weight relevant words of the input.
Visualizing the way the model attends to particular items within a sequence in order to produce meaningful replies.

Technical Requirements

To run the notebooks and scripts, the following Python packages are needed:
* torch
* torchvision
* transformers
* datasets
* accelerate
* pytorch-pretrained-biggan

Learning Outcomes

Through these experiments you will be able to:
* Process complex data sets to generate.
* Train and implement generative models.
* Transfer learning to pre-trained transformer models.
* Learn the significance of latent spaces and attention in the contemporary AI.
