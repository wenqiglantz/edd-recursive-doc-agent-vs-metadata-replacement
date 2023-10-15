# Evaluation Driven Development for Multi Document RAG Pipeline
Applying Evaluation Driven Development (EDD) to aid in the design decision of RAG pipelines. Specifically, this repo demonstrates how to use EDD to decide which of these two strategies perform best for a multi document RAG pipeline:

* Recursive retriever + document agent
* Metadata replacement + node sentence window

See Colab notebook edd_recursive_doc_agent_metadata_replacement for detailed implementation.

Check out my Medium blog post for details. [Evaluation Driven Development, the Swiss Army Knife for RAG Pipelines](https://levelup.gitconnected.com/evaluation-driven-development-the-swiss-army-knife-for-rag-pipelines-dba24218d47e?sk=6cb81d764cd44a0cf117fe475725bc1d).

# Evaluation Driven Development for Multi Document RAG Pipeline with GPT-3.5 and Zephyr-7b
This notebook demonstrates how to use EDD to decide which of the two LLMs perform best for a multi document RAG pipeline for Metadata replacement + node sentence window:

* gpt-3.5-turbo
* zephyr-7b-alpha

See Colab notebook edd_zephyr_7b_gpt3_5_metadata_replacement_multi_doc for detailed implementation.

Check out my Medium blog post for details. [Exploring zephyr-7b-alpha Through the Lens of Evaluation Driven Development](https://levelup.gitconnected.com/exploring-zephyr-7b-alpha-through-the-lens-of-evaluation-driven-development-faf69e9d9ec7?sk=e51badfbb15c11e3ef919f2790b9480d).

