# Sparse Autoencoders Find Highly Interpretable Features in Language Models

**Date**: 10-25-2026 • [Homebase](../README.md) • #interpretability #mech-interp #sparse-autoencoders #nlp #llm

**Link:** https://arxiv.org/abs/2309.08600

### TL;DR:   
- When there are more features than neurons in a neural network, the network must use superposition to represent all of the features, thus leading to polysemanticity  
	- This makes neural networks difficult to interpret in a human-parsable manner  
- The paper introduces a method (sparse autoencoders) to resolve superposition using a scalable and unsupervised method

### Problem: 

### Key equations/terms:   
**What makes superposition possible?**  
- A key example: say that we want to represent A, B, and C using vectors in $\mathbb{R}^2$. We could say  
$$A = \begin{bmatrix} 1  \\  0  \end{bmatrix}, B = \begin{bmatrix} 0  \\  1  \end{bmatrix}, C = \begin{bmatrix} 1  \\  1  \end{bmatrix}$$  
- Then 


### Design choices + why: 

### Results: 

### Open questions: 


**Builds on:** [Attention Is All You Need](attention-is-all-you-need.md)  
**Rating:** ⭐️⭐️⭐️

---  
#### Notes for myself:

**Polysemanticity:** the phenomenon where neurons activate in multiple, semantically distinct contexts, which prevents us from identifying explanations for what neural networks (specifically the neurons) are actually doing

**Superposition:** when there are more features than neurons in a neural network, so one neuron may represent multiple features
