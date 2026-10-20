# Embedding Retrieval Benchmark

A comparison of embedding models on retrieval across finance, legal contracts, technical support, and medical literature. The study includes hosted models, open models, and a lexical retrieval baseline.

Published studies: [embedding models](https://aimultiple.com/embedding-models) and [open-source embedding models](https://aimultiple.com/open-source-embedding-models).

The evaluation uses 200 questions and 341,040 passages. Each question searches the corpus for its own domain. Models share the same questions and recorded relevance labels, while model-specific query and document instructions are preserved.

The main measures are nDCG@10 and Recall@10. They describe the ordering and coverage of recorded relevant passages within the first ten retrieved results. Results are reported for individual domains and across the complete test set.

The relevance labels do not exhaustively judge every passage a model might retrieve. The article explains that limitation, uncertainty estimates, and the cost comparison. This study uses a different corpus and protocol from the earlier product-review embedding benchmark.

The benchmark implementation was developed for AIMultiple and belongs to AIMultiple. This repository is a documentation summary. Source code and benchmark datasets are not distributed here.
