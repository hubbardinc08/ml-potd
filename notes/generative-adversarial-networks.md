# Generative Adversarial Networks

**Date**: 09-22-2026 • [Homebase](../README.md) • #field-tag

**Link:** https://arxiv.org/abs/1406.2661

### TL;DR:   
The majority of research focus at the time of this paper's publication was on deep learning for discriminative models because linear units were difficult to apply to the generative context and compute MLE. This paper introduces a new generative model estimation procedure (*adversarial nets*) 

### Problem: 

### Key equations/terms: 

### Design choices + why: 

### Results: 

### Open questions: 

**Builds on:** None  
**Rating:** ⭐️⭐️⭐️

---  
#### Notes for myself:

**Discriminative models:** models that give a prediction based on an input (classification)  
**Generative models:** models that produce new input-like data 

**Maximum likelihood estimation (MLE):** a statistical method used to find the best-fitting parameters for a model by choosing the values that make the observed data most probable

**The design of *adversarial nets***:  
- generative model vs discriminative (adversary) model  
	- generative: counterfeiters   
	- discriminative (police): learns to determine whether a sample is from the model distribution (fake) or the data distribution (real)


**Minimax algorithm:** a decision-making algorithm where opposing players select moves optimally; one player tries to maximize the score while the other tries to minimize it.  
- **Advantages:**   
	- works well for deterministic games with clear states/actions/outcomes  
	- very simple decision model  
	- can be widely applied to 2-player adversarial games  
- **Disadvantages:**   
	- computationally expensive  
	- not scalable to games with larger states  
	- requires concrete game progressions without randomness
