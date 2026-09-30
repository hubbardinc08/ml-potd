# RT-1 Robotics Transformer for Real-World Control at Scale

**Date**: 09-27-2026 • [Homebase](../README.md) • #robotics #transformer #embodied-ai

**Link:** [https://arxiv.org/abs/2212.06817](https://arxiv.org/abs/2212.06817)

### TL;DR:   
Before this paper, end-to-end robotic learning typically involved training on specially curated task-specific data, which is similar to supervised learning in other fields. However, the issue is that obtaining such data requires complex operations and is not super efficient. Thus, this research paper explores if it is possible for a robotic learning model trained on general robotics scenarios to perform zero-shot and situation-specific tasks.

### Problem:   
building large multi-task models are difficult:  
- limited breadth of real-world tasks  
- cannot generalize to new tasks  
- lower performance on new tasks

the Transformer architecture is good for multi-task learning, but it alone is not efficient enough to be run in real time, which is a necessity for robotic controllers

### Key equations/terms: 

### Design choices + why:   
- the dataset used for training must combine both **scale** and **breadth** - they used a dataset gathered over the course of 17 months with robots executing over 700 different tasks  
- robotic controllers require a Transformer architecture efficient enough for real-time computation --> developed the RT-1 that encodes multi-modal inputs and outputs into token representations

### Results: 


### Remaining Problems  
- RT-1 is still an imitation learning method --> the performance may not be able to surpass that of the robotics in the training data  
- RT-1 is still unable to perform tasks that have not been presented in training

### Open questions: 

**Builds on:** [Attention Is All You Need](attention-is-all-you-need.md)

**Rating:** ⭐️⭐️⭐️

---  
#### Notes for myself:
