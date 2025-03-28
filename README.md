# Awesome GraphRAG

A list of papers for Graph Retrieval-Augmented Generation (GraphRAG).

## Contents

- [Surveys and Roadmaps](#surveys-and-roadmaps)
- [GraphRAG Frameworks](#graphrag-frameworks)
- [Retrievers](#retrievers)
- [Graph-Enhanced Reasoning](#graph-enhanced-reasoning)
- [Applications](#applications)

## Surveys and Roadmaps

- Graph Retrieval-Augmented Generation: A Survey [[paper]](https://arxiv.org/pdf/2408.08921)
- Retrieval-Augmented Generation with Graphs (GraphRAG) [[paper]](https://arxiv.org/pdf/2501.00309v2)
- Unifying Large Language Models and Knowledge Graphs: A Roadmap [[paper]](https://arxiv.org/pdf/2306.08302v3)
- A Survey of Graph Retrieval-Augmented Generation for Customized Large Language Models [[paper]](https://arxiv.org/pdf/2501.13958)
- RAG vs. GraphRAG: A Systematic Evaluation and Key Insights [[paper]](https://arxiv.org/pdf/2502.11371)

## GraphRAG Frameworks

- GraphRAG [[paper]](https://arxiv.org/pdf/2404.16130) [[code]](https://github.com/microsoft/graphrag) - Propose a framework that retrieves knowledge from private corpus, build knowledge graph, generate communities to generate comprehensive and diverse answers.
- HippoRAG [[paper]](https://arxiv.org/pdf/2405.14831) [[code]](https://github.com/OSU-NLP-Group/HippoRAG)- NeurIPS '24: HippoRAG inspired by the hippocampal indexing theory of human long-term memory to enable deeper and more efficient knowledge integration over new experiences.
- HippoRAG 2 [[paper]](https://arxiv.org/pdf/2502.14802) [[code]](https://github.com/OSU-NLP-Group/HippoRAG)- HippoRAG 2 enhances the original HippoRAG framework by implementing deeper passage integration and more effective online utilization of large language models (LLMs).
- LightRAG [[paper]](https://arxiv.org/pdf/2410.05779) [[code]](https://github.com/HKUDS/LightRAG)- Introduces lightweight, high-speed graph rag implementations.
- LEGO-GraphRAG [[paper]](https://arxiv.org/pdf/2411.05844) [[code]](https://github.com/gzy02/LEGO-GraphRAG) - Modularizing graph-based retrieval with interconnected modules: subgraph-extraction, path-filtering, and path-refinement.
- SimGRAG [[paper]](https://arxiv.org/pdf/2412.15272) [[code]](https://github.com/YZ-Cai/SimGRAG) - Retrieves "similar subgraphs" in knowledge graphs, focusing on matching and reusing analogous structures.
- HybridRAG [[paper]](https://arxiv.org/pdf/2408.04948) [[code]](https://github.com/nvidia/workbench-example-hybrid-rag) - Integrates graph-based and vector-based retrieval methods.
- GNN-RAG [[paper]](https://arxiv.org/pdf/2405.20139) [[code]](https://github.com/cmavro/GNN-RAG)- EMNLP '23: Uses Graph Neural Networks to improve graph-based retrieval.

## Retrievers

- G-Retriever [[paper]](https://arxiv.org/pdf/2402.07630) - Enhances Prize-Collecting Steiner Tree algorithm for subgraph extraction.
- Subgraph Retrieval for Multi-hop KB QA [[paper]](https://www.aclweb.org/anthology/ACL-22) - Retrieves relevant paths from topic entities.
- PullNet [[paper]](https://arxiv.org/abs/1904.09286) - EMNLP '19: Iterative retrieval from structured and unstructured sources.
- Patent Phrase Similarity Retrieval  - Retrieves graph structures to infer phrase relationships.
- Graph-based Reranking [[paper]](https://arxiv.org/pdf/2405.18414) - Improves RAG by leveraging graph connectivity in reranking.

## Graph-Enhanced Reasoning

- KG-GPT [[paper]](https://arxiv.org/abs/recent) - EMNLP '23: General framework for knowledge graph reasoning.
- Think-on-Graph 2.0 [[paper]](https://arxiv.org/abs/recent) - Deep and interpretable LLM reasoning with KG retrieval.
- StructGPT [[paper]](https://arxiv.org/abs/recent) - Framework for reasoning over structured data.
- KagNet [[paper]](https://arxiv.org/abs/1909.02151) - EMNLP '19: Knowledge-aware graph networks for commonsense reasoning.
- QA-GNN [[paper]](https://arxiv.org/abs/recent) - NAACL '23: LLM reasoning with knowledge graphs.
- Graph Chain-of-Thought [[paper]](https://arxiv.org/abs/recent) - Augments LLMs by reasoning on graphs.

## Applications

- KAG [[paper]](https://arxiv.org/pdf/2409.13731) - Boosting LLMs in professional domains via knowledge augmented generation.
- KG-Rank [[paper]](https://arxiv.org/abs/recent) - Enhancing medical QA with knowledge graphs.
