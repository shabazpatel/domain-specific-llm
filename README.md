# Domain-Specific LLM

Constructing an effective Language Model system entails a journey through several crucial phases. Initially, it demands the employment of robust evaluation metrics to benchmark the strides in development and selection of LLMs. Following suit, the venture dives into the art of engineering the precise prompt, harnessing the power of Retrieval Augmented Generation, and fine-tuning, with the evaluation metrics shining as the guiding star. The final leg of the journey underscores the imperative of guardrails, a shield against malicious endeavors, anchoring the trustworthiness and reliability of the LLM system.

This narrative unfolds a comprehensive framework dedicated to nurturing domain-specific Large Language Model (LLM) systems, with a spotlight on harmonizing with the Islamic worldview. A kaleidoscope of approaches, design choices, datasets, prompts, and a meticulous evaluation of diverse trade-offs and methodologies are presented. The compass was set towards fabricating systems that resonate authentically with Islamic teachings, while gracefully navigating the technical and epistemological rapids associated with the depths of Islamic knowledge. The horizon beckons for further explorations to refine the modules, datasets, and delve deeper into the technical and epistemological realms, unearthing a richer understanding and potential enhancements.

#### Files and Their Descriptions:

- `Islam100QA.csv`: The crucible for evaluating the mettle of the LLM system.
- `RAG_system.ipynb`: The canvas where the Retrieval Augmented Generation with embedchain comes to life.
- `cleaned_hadiths.csv`: The dataset, the lifeblood for RAG and the fine-tuning odyssey of GPT-3.5.
- `llm_evaluation.ipynb`: The crucible where the LLM is put under the lens, employing metrics such as BERT score and cosine distance score to evaluate the engineered prompts.
- `llm_guardrail_system.ipynb`: The realm where the end-to-end LLM system with guardrail code blossoms.
