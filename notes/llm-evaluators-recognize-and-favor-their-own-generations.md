# LLM Evaluators Recognize and Favor Their Own Generations

**Date**: 10-23-2026 • [Homebase](../README.md) • #nlp #llm #evaluation #bias

**Link:** https://arxiv.org/html/2404.13076v1

### TL;DR:   
- LLMs show **self-preference bias** where they rate their own generations higher than equally good outputs from other sources ("equally good" based on human benchmark)  
- If LLMs can actually recognize their own outputs, then this prompts us to reconsider the reliability of LLM-based evaluation

### Key equations/terms:   
**Self-preference:** LLM favors its own outputs over texts from other LLMs and humans  
**Self-recognition**: LLM can distinguish its own outputs from texts from other LLMs or humans

### Main findings  
1. Frontier LLMs disproportionately favor their own summaries than other LLMs and humans  
2. LLMs without fine-tuning show non-trivial self-recognition  
3. Fine-tuning leads to near-perfect self-recognition  
4. Self-preference strength is linearly related to self-recognition (basically if the LLM is able to recognize that the work shown is their own, they are more likely to rank it highly)

### Results:   
- "We provide initial evidence towards the hypothesis that LLMs prefer their own generations because they recognize themselves."

### Open questions:   
- In an adversarial setting, if the adversarial LLM can recognize its similarities with the LLM defender, then it can produce results that align with the defender LLM  
	- For example, an optimizer LLM can specifically focus on producing long-winded, convoluted texts if the reward LLM prefers such outputs and ranks them highly

**Builds on:** [Judging LLM-as-a-Judge with MT-Bench and Chatbot Arena](judging-llm-as-a-judge-with-mt-bench-and-chatbot-arena.md)  
**Rating:** ⭐️⭐️⭐️

---  
#### Notes for myself:
