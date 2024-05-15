<!---
# MLOps Project


**Data:**
--->
**Reference:**  MASHQA (Multiple Answer Spans Healthcare Question Answering) Research
[Paper](https://people.cs.vt.edu/mingzhu/papers/conf/emnlp2020.pdf) and [GitHub link](https://github.com/mingzhu0527/MASHQA)

**Objective:** 
The goal of this project is to Instruction Tune LLMs (Mistral-7B and GPT-3.5-Turbo) on healthcare data to make a question answering assistant on health related questions.
<!--- operationalize a Generative AI model (for example using [LangChain](https://github.com/hwchase17/langchain) on the chosen MLOps platform and answer below: 
1. Justify choice of platform
2. How team collaborated as a team using CI/CD
3. How team designed experiment pipelines – used any framework? Why?
4. Justify choice of GenAI model
5. How team performed data versioning – if it was not necessary explain why?
6. How team performed model versioning
7. How team executed prompt engineering
8. How team executed instruction tuning
9. Analyze the model results
10. Propose how to monitor model for continuous training
--->

The various steps performed are:
1. Operationalize LLM using Google Colab Pro with a V100 GPU Compute Machine
2. Used zero-shot, few-shot, chain-of-thought, and retrieval augmented generation (RAG) prompt engineering
3. Instruction tuned LLM using provided data set

Prompts to test the LLM:
- What types of exercise are best for people with asthma?
- How is obsessive-compulsive disorder diagnosed?
- When are you more likely to get a blood clot?
- How should you lift objects to prevent back pain?
- How can you be smart with antibiotics?
