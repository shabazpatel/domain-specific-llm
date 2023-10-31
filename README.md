# domain-specific-llm

Building an effective Language Model system involves several crucial steps. To begin with, it requires the utilization of evaluation metrics to benchmark the development and selection of LLMs. Then, it involves engineering the right prompt and utilizing Retrieval Augmented Generation, and fine-tuning with evaluation metrics as the north star. Finally, ensuring the presence of a guardrail is important to prevent any malicious activity and establish a trustworthy and reliable LLM system.

This work presents a comprehensive framework for developing domain-specific Large Language Model (LLM) systems, with a particular focus on aligning with the Islamic worldview. We have presented various approaches, design choices, datasets, prompts, and a thorough evaluation of different trade-offs and methodologies. The aim was to construct systems that accurately represent Islamic teachings while addressing the technical and epistemological challenges associated with the nuances of Islamic knowledge. Further research can improve each of the modules, datasets, and assess the technical limitations and epistemological challenges in more detail.

#### Files and their Descriptions:

Islam100QA.csv: Data for the evaluation of the LLM system.
RAG_system.ipynb: Implementation of retrieval augmented generation with embedchain.
cleaned_hadiths.csv: Dataset used for RAG and the fine-tuning process of GPT-3.5.
llm_evaluation.ipynb: Notebook with evaluation of LLM using metrics such as BERT score and cosine distance score towards the evaluation of engineered prompts.
llm_guardrail_system.ipynb: End-to-end LLM system with guardrail code.
