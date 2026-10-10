# Denoising Diffusion Probabilistic Models

**Date**: 09-30-2026 • [Homebase](../README.md) • #generative #diffusion #deep-learning

**Link:** https://arxiv.org/abs/2006.11239

### TL;DR:   
- There were no demonstrations in the past that diffusion models could generate high quality image samples

### Problem: 

### Key equations/terms: 

### Design choices + why: 


### Results:   
- Showed that diffusion models can create high quality image samples  
- Found connections among diffusion models and variational inference  
- Diffusion models may be useful for data compression 

### Open questions: 

**Builds on:** None  
**Rating:** ⭐️⭐️⭐️⭐️

---  
#### Notes for myself:

**How the overall process works:**  
- A clear image $(x_0)$ undergoes a series of noising steps $(x_i)$ where small bits of noise are added to each pixel until the final image is completely static $(x_T)$  
- We want to train a model that can reverse these steps, specifically the model weights transitioning each image stage to the previous, such that we can generate a high-quality image from static.



[DDPM.pdf](../assets/ddpm.pdf)
