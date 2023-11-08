# MLOps Project

**Data:**

**Reference:**  
MASHQA (Multiple Answer Spans Healthcare Question Answering) Research
[Paper](https://people.cs.vt.edu/mingzhu/papers/conf/emnlp2020.pdf) and [GitHub link](https://github.com/mingzhu0527/MASHQA)

The goal of this project is to operationalize a Generative AI model (for example using [LangChain](https://github.com/hwchase17/langchain) on the chosen MLOps platform and answer below: 
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

The various steps performed in this project are:
1. Operationalize an LLM on your platform (exceptions due to cost explained in presentation)
2. outline architecture for #1 in presentation
3. use zero-shot, few-shot, chain-of-thought, and retrieval augmented generation (RAG) prompt engineering
4. use below prompts and copy answers in presentation for each method in #3
5. instruction tune LLM using provided data set
6. outline architecture for #4 in presentation
7. use below prompts with instruction-tuned LLM and copy answers in presentations

Prompts to test your LLM:
- What types of exercise are best for people with asthma?
- How is obsessive-compulsive disorder diagnosed?
- When are you more likely to get a blood clot?
- How should you lift objects to prevent back pain?
- How can you be smart with antibiotics?
