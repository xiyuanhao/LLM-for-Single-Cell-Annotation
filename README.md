
# 📚 Large Language Models for Single-Cell Annotation

This repository provides a curated collection of recent research works exploring the application of **Large Language Models (LLMs)** in **single-cell RNA sequencing (scRNA-seq) analysis**, with a primary focus on **cell type annotation**, **reasoning**, **agentic systems**, and **foundation models**.

Recent advances show that LLMs are no longer limited to auxiliary text-processing roles. Instead, they increasingly function as **biological reasoning engines**, **autonomous agents**, and **general-purpose foundation models**, bridging biological knowledge, structured omics data, and decision-making pipelines.

---

## 🔍 Scope and Motivation

Single-cell RNA-seq analysis faces several fundamental challenges:

- High annotation cost and reliance on expert-curated references  
- Limited generalization to rare, unseen, or novel cell types  
- Poor interpretability of purely data-driven models  
- Fragmented analysis pipelines requiring extensive manual intervention  

Large language models offer new opportunities by incorporating:

- Structured and unstructured biological knowledge  
- Reasoning and abstraction capabilities  
- Zero-shot and few-shot generalization  
- Agent-based interaction with tools and databases  

This repository organizes existing work according to **methodological paradigms**, rather than chronology.

---

## 🧩 Methodological Taxonomy

### 🔧 LLM-as-a-Tool

These works treat LLMs as **external reasoning or validation modules**, typically applied on top of conventional scRNA-seq pipelines. LLMs are prompted with marker genes, expression summaries, or candidate labels to perform **post-hoc annotation, verification, or consensus refinement**.

**Key characteristics**
- Prompt-based interaction  
- No or minimal model training  
- Cost-aware inference  
- Strong reliance on prior biological knowledge encoded in LLMs  

**Representative works**
- Assessing GPT-4 for Cell Type Annotation in Single-Cell RNA-seq Analysis  
- Large Language Model Consensus Substantially Improves the Cell Type Annotation Accuracy for scRNA-seq Data  
- Reference-Free and Cost-Effective Automated Cell Type Annotation with GPT-4 in Single-Cell RNA-seq Analysis  

---

### 🧬 LLM-Derived Embeddings

This line of work leverages LLMs to generate **semantic embeddings** that align transcriptomic patterns with biological concepts, enabling higher-level reasoning across molecular and phenotypic spaces.

**Core ideas**
- Mapping gene expression to semantic representations  
- Cross-domain alignment between language and omics data  
- Supporting disease- or vulnerability-specific analysis  

**Representative works**
- Bridging Large Language Models and Single-Cell Transcriptomics in Dissecting Selective Motor Neuron Vulnerability  

---

### 🧠 Training Language / Foundation Models

These approaches focus on **training or pretraining language models directly on biological or single-cell data**, aiming to build **cell-level or gene-level foundation models**.

**Typical contributions**
- Domain-specific tokenization (genes, pathways, cell states)  
- Large-scale pretraining on scRNA-seq corpora  
- Improved robustness and generalization  

**Representative works**
- Scaling Large Language Models for Next-Generation Single-Cell Analysis  
- Celler: A Genomic Language Model for Long-Tailed Single-Cell Annotation  
- Cell-o1: Training LLMs to Solve Single-Cell Reasoning Puzzles with Reinforcement Learning  
- CELLPLM: Pre-training of Cell Language Models Beyond Single Cells  
- CellReasoner: A Reasoning-Enhanced Large Language Model for Cell Type Annotation  

---

### 🤖 LLM Agent and Agentic Systems

Agent-based approaches elevate LLMs from passive predictors to **autonomous decision-makers** capable of multi-step reasoning, tool usage, and interaction with external resources such as ontologies and databases.

**Common features**
- Iterative reasoning and decision loops  
- Tool calling and memory mechanisms  
- Interpretable decision traces  
- Reduced dependence on curated references  

**Representative works**
- CASSIA: A Multi-Agent Large Language Model for Reference-Free, Interpretable, and Automated Cell Annotation  
- CellTypeAgent: Trustworthy Cell Type Annotation with Large Language Models  
- DeepSeq: High-Throughput Single-Cell RNA Sequencing Data Labeling via Web Search-Augmented Agentic Generative AI  
- scAgent: Universal Single-Cell Annotation via a LLM Agent  
- An Agentic AI Framework for Ingestion and Standardization of Single-Cell RNA-seq Data Analysis  

---

### 🧪 Benchmark and Evaluation

These studies critically assess whether LLMs genuinely **understand cell biology**, rather than memorizing surface-level correlations, by introducing systematic benchmarks and evaluation protocols.

**Evaluation dimensions**
- Biological consistency  
- Robustness to noise  
- Zero-shot generalization  
- Faithfulness and interpretability  

**Representative works**
- CELLVERSE: Do Large Language Models Really Understand Cell Biology?  
- Single-Cell Omics Arena: A Benchmark Study for Large Language Models on Cell Type Annotation Using Single-Cell Data  

---

### 🔍 Post-hoc Enhancement Methods

Instead of replacing existing models, these approaches focus on **refining or regularizing predictions** using uncertainty measures, graph constraints, or consensus-based refinement.

**Representative works**
- GRIT: Graph-Regularized Logit Refinement for Zero-Shot Cell Type Annotation  

---

### 🧠 Transformer-Based and Multimodal Models

These methods adapt Transformer architectures to model **cell–gene relationships**, emphasizing scalability, interpretability, and attention-based reasoning.

**Representative works**
- LangCell: Language-Cell Pre-training for Cell Identity Understanding  
- Transformer for One-Stop Interpretable Cell Type Annotation  
- scSwinTNet: A Cell Type Annotation Method for Large-Scale Single-Cell RNA-seq Data Based on Shifted Window Attention  

---

### 🧬 Foundation Models for scRNA-seq

These works aim to build **general-purpose pretrained models** for single-cell data, supporting diverse downstream tasks and modalities.

**Representative works**
- scBERT: A Large-Scale Pretrained Deep Language Model for Cell Type Annotation of Single-Cell RNA-seq Data  
- scGPT: Toward Building a Foundation Model for Single-Cell Multi-Omics Using Generative AI  
- Assessing Parameter-Efficient Methods for Pretrained Language Models in Annotating scRNA-seq Data  

---

## 🚀 Future Directions

Promising research directions include:

- Reinforcement learning for adaptive annotation and reasoning  
- Multi-agent collaboration across biological scales  
- Unified modeling of cells, genes, and biological text  
- Trustworthy and interpretable agentic pipelines  
- Integration with wet-lab and clinical workflows  

---

## 📌 Contribution

Contributions are welcome.  
Please feel free to submit pull requests to add new papers, refine categorization, or improve descriptions.
