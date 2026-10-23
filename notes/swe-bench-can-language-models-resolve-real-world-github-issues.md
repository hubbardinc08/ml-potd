# SWE-bench - Can Language Models Resolve Real-World Github Issues

**Date**: 10-23-2026 • [Homebase](../README.md) • #benchmarks

**Link:** https://arxiv.org/html/2310.06770v3

### TL;DR: 

### Problem:   
- Existing code generation benchmarks only include short, self-contained problems that do not reflect real-world software engineering complexity  
- Why is building a good benchmark hard? It requires the tasks to be challenging but also verifiable  
	- We need a challenging, realistic benchmark to evaluate the capabilities of LLMs on tasks requiring <u>multi-file reasoning</u>, <u>long-context understanding</u>, and <u>verification</u>

### Key equations/terms: 

### Design choices + why: 

### Results:   
- All evaluated models perform very poorly: the best model, Claude 2, resolves only 1.96% of issues using BM25 retrieval, and 4.80% with oracle retrieval.  
- Performance degrades as context length increases, indicating models struggle to localize relevant code within large inputs.

### Open questions: 

**Builds on:**   
**Rating:** ⭐️⭐️⭐️

---  
#### Notes for myself:

-
