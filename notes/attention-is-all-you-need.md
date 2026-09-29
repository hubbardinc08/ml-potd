# Attention Is All You Need

**Date**: 09-15-2026 • [Homebase](../README.md) • #nlp #attention #transformer #seq2seq`

**Link:** https://arxiv.org/abs/1706.03762

### TL;DR: 

In the future, to handle long input sequences, they plan to apply self-attention to smaller windows centered around the respective output positions. Additionally, attention-based architectures are able to handle various input media other than text.

#### Problem:   
Current recurrent models require sequential computation, meaning processing each state requires the previous state's result, ultimately preventing parallelization. Although researchers have experimented with attention, these models still require recurrence. 

### Key equations:  
- softmax function for scaled dot-product attention  
- 

### Design choices + why:

The 3 main motivators were   
1. total computational complexity per layer,   
2. amount of computation that can be parallelized,   
3. and the path length between distant dependencies (long range)



### Results:   
- More parallelization  
- 

### Open questions:   
- What are positional encodings?  
- Why exactly is the softmax function designed like that? What motivated the exact scaling factor that they used?

**Builds on:** None

**Rating:** ⭐️⭐️⭐️⭐️

---  
#### Notes for myself:

**Recurrent models:** a class of neural networks that process sequential or time-series data by maintaining a memory of past inputs  
**Encoder-decoder architecture:** inputs are first encoded into tokens that produce a hidden state, then the decoder uses the hidden state to decide the output  
**Self-attention:** attention mechanism that relates different parts of a sequence to compute a representation of that sequence  
**Autoregressive:** the model uses past outputs as inputs to generate new predictions  
**Attention function:** mapping a query and a set of key-value pairs to an output

The two most commonly used attention functions are additive attention and dot-product attention, and in this paper, the transformer uses scaled dot-product attention, where the softmax function is scaled by a scaling factor

**Sequence transduction model:** transforms an input sequence of data into a different output sequence

**BLEU (Bilingual Evaluation Understudy) score:** an automated metric that measures the quality and similarity of machine-translated or AI-generated text against professional human reference translations
