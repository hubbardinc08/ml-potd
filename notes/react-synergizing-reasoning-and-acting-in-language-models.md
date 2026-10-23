# ReAct - Synergizing Reasoning and Acting in Language Models

**Date**: 10-23-2026 • [Homebase](../README.md) • #nlp #llm #agents #reasoning #prompting

**Link:** https://research.google/blog/react-synergizing-reasoning-and-acting-in-language-models/

### TL;DR:   
- CoT prompting: model is not grounded in the external world, uses its own learned representations to generate reasoning - cannot explore/reason or update its knowledge  
- Pre-trained LLMs that map text context to text actions do not reason abstractly or maintain a working memory for long-horizon tasks  
- ReAct proposes a combination of reasoning and acting (Reason + Act = ReAct) which can solve language reasoning and decision making tasks  
	- Action: interact with the external world and produce results that the model can observe  
	- Reasoning: doesn't change the external world, but helps the model organize information and update the model with information to help future reasoning and acting

### Problem:  
- Reasoning-only LLM lacks external information --> prevents LLM from learning new stuff  
- Acting-only LLM lacks ability to make key decisions and think abstractly

### Key equations/terms: 

### Design choices + why:   
<img src="../assets/pasted-image-20261023021318.png" width="427" alt="Pasted image 20261023021318">  
- The reasoning-acting loop that ReAct utilizes

<img src="../assets/pasted-image-20261023021601.png" width="457" alt="Pasted image 20261023021601">  
- Example of ReAct in comparison with reason-only and act-only

### Results:   
- ReAct leads to superior performance with interpretable decision traces  
-  "We plan to further extend this line of research and leverage the strong potential of the language model for tackling broader embodied tasks, via approaches like massive multitask training and coupling ReAct with equally strong reward models."

### Open questions: 

**Builds on:**   
**Rating:** ⭐️⭐️⭐️⭐️

---  
#### Notes for myself:
