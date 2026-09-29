# Adam - A Method for Stochastic Optimization

**Date**: 2026-09-24 • [Homebase](../README.md) • #optimization #theory #deep-learning`

**Link:** https://arxiv.org/abs/1412.6980

### TL;DR: 

### Problem: 

### Key equations/terms: 

### Design choices + why: 

### Results: 

### Open questions: 

**Builds on:**  
**Rating:** ⭐️⭐️⭐️

---  
#### Notes for myself:

**Optimizers** determine how the weights in the model are changed during back propagation

**Momentum** speeds up SGD where downward pointing vectors in the same direction increase in magnitude  
- Vanilla SGD: $W_{t+1} = W_t - \alpha \Delta W_t$ where $\alpha$ is the learning rate and $\Delta W_t$ is the gradient of the loss function with respect to the weight $W$

**Gradient descent with momentum**  
$V_{t+1} = \beta V_t + (1 - \beta) \Delta W_t$ where $V$ represents velocity  
$W_{t+1} = W_t - \alpha V_{t + 1}$  
$\beta = 0.9$ where $\beta$ represents how influential past velocities will be in the current update  
- $\beta = 0$ means vanilla SGD

**Root mean squared propagation**  
- Motivation: RMSProp was introduced to solve the problem with AdaGrad (Adaptive Gradient Algorithm) which was its diminishing learning rate  
-
