# Hi, I'm Anant 👋

**Theoretical Physicist · Scientific ML Researcher · AI Systems Builder**

I recently completed my PhD in theoretical physics at SISSA, where my research focused on three-dimensional mirror symmetry and dualities in supersymmetric quantum field theories. My doctoral work developed systematic methods for constructing dual pairs in a class of theories that had remained difficult to classify for decades, with findings published in *Physical Review D* and the *Journal of High Energy Physics*. 

📄 Find my publications [here](https://inspirehep.net/authors/2931640)

My interests now lie at the intersection of scientific machine learning, AI for Science, and AI systems engineering. I work on learning scientific dynamics, geometric deep learning, quantum error correction, and machine learning methods for scientific discovery.

I am interested not just in whether a model makes accurate predictions, but in whether it learns the underlying structure of a problem, generalises beyond its training distribution, and produces reliable results.

Alongside research, I build end-to-end AI systems: from model development and evaluation to APIs, containerised services, agentic workflows, and deployment. I enjoy working across the full stack, particularly when the application has a genuinely interesting scientific or technical problem behind it.

---

## 🛠 Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PostgreSQL Badge](https://img.shields.io/badge/SQL-4169E1?logo=mysql&logoColor=fff&style=flat)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=flat-square&logo=mathworks&logoColor=white)
![Wolfram Mathematica Badge](https://img.shields.io/badge/Wolfram%20Mathematica-D10?logo=wolframmathematica&logoColor=fff&style=flat)

**Data Handling**

[![NumPy](https://img.shields.io/badge/NumPy-4DABCF?logo=numpy&logoColor=fff)](#)
[![Matplotlib](https://custom-icon-badges.demolab.com/badge/Matplotlib-71D291?logo=matplotlib&logoColor=fff)](#)
[![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=fff)](#)
[![Seaborn](https://img.shields.io/badge/Seaborn-4EAEAA?logo=python&logoColor=fff)](#)

**ML & Deep Learning**

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![PyG Badge](https://img.shields.io/badge/PyG-3C2179?logo=pyg&logoColor=fff&style=flat)
[![JAX](https://custom-icon-badges.demolab.com/badge/JAX-222827?logo=jax&logoColor=ffffff)](#)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
<!--![XGBoost](https://img.shields.io/badge/XGBoost-189AB4?style=flat-square&logo=python&logoColor=white)
![HuggingFace](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![CatBoost](https://img.shields.io/badge/CatBoost-189AB4?style=flat-square&logo=python&logoColor=white)-->
<!--![Keras](https://img.shields.io/badge/-Keras-D00000?style=flat&logo=Keras)-->

**LLMs & Agentic AI**

![LangChain Badge](https://img.shields.io/badge/LangChain-7FC8FF?logo=langchain&logoColor=fff&style=flat)
![LangGraph Badge](https://img.shields.io/badge/LangGraph-7FC8FF?logo=langgraph&logoColor=fff&style=flat)
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-7B2FBE?style=flat-square&logo=python&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square&logo=modelcontextprotocol&logoColor=white)

**MLOps, Deployment & Tooling**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![LangChain Badge](https://img.shields.io/badge/LangSmith-7FC8FF?logo=langchain&logoColor=fff&style=flat)
![Gradio Badge](https://img.shields.io/badge/Gradio-F97316?logo=gradio&logoColor=fff&style=flat)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
<!--[![Visual Studio Code](https://custom-icon-badges.demolab.com/badge/Visual%20Studio%20Code-0078d7.svg?logo=visualstudiocode&logoColor=white)](#)
[![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?logo=googlecolab&logoColor=fff)](#)
![Jupyter](https://img.shields.io/badge/Jupyter-ffffff?logo=Jupyter)-->


---

## 🚀 Selected Projects

### 🔬 Scientific Machine Learning
Projects exploring how machine learning models represent, approximate, and generalise scientific systems.

[**Spectral Response Fidelity**](https://github.com/anantshri1/ml4ps-response-fidelity) · A JAX/Equinox study investigating whether Fourier Neural Operators learn physically meaningful response functions, rather than merely accurate forward predictions.  Explores Jacobian-supervised training, spectral response fidelity, differentiable quantum dynamics, and out-of-distribution generalisation.

[**Neural Operators for PDEs**](https://github.com/anantshri1/fno-data-efficiency) · An empirical study of how architectural inductive biases influence the data efficiency of neural operators.
* FNO reaches 10% test relative L2 error with approximately 4.1× less training data than a matched-budget U-Net.
* 116.3× faster inference than the finite-difference solver in the documented CPU benchmark.
* Includes multi-seed evaluation, bootstrap confidence intervals, resolution-transfer analysis, and spectral error decomposition.

[**Machine Learning Assisted Quantum Error Correction**](https://github.com/anantshri1/ml-qec) · A streaming GNN decoder for the rotated surface code under circuit-level SI1000 noise, exploring learned decoding strategies and correlated error information. Also extending the framework to color codes and investigating generalisation across code families. *In progress*

### 🧪 AI for Scientific Discovery
Building machine learning models and computational systems that connect scientific problems with practical, usable tools.

[**MolPredict**](https://github.com/anantshri1/homo-lumo-gat) · A molecular property prediction system using GATv2 on the QM9 dataset to predict HOMO-LUMO gaps.
* Test MAE: 0.1712 eV.
* FastAPI inference service with single and batch prediction.
* Dockerised CUDA-enabled deployment and an independent MCP server.
* MC-dropout-based uncertainty estimation.
[Live API documentation](https://homo-lumo-gat.fly.dev/docs)

[**Multi-Agent Symbolic Reasoning**](https://github.com/anantshri1/group-theoretic-agentic-pipeline) · An agentic system for mathematical problem-solving using a solver → verifier → critic architecture. Combines LangGraph orchestration with exact symbolic verification through SymPy, exposed as an independent MCP service. [🤗 demo](https://huggingface.co/spaces/anantshri1/group-theoretic-agentic-pipeline)

### ⚙️ AI Systems & Engineering
Building complete AI applications, with an emphasis on modular architecture, evaluation, observability, and deployment.

[**Agentic AutoML**](https://github.com/anantshri1/agentic-automl-platform) · An end-to-end agentic system for autonomous supervised machine learning.
* LangGraph orchestration and modular MCP tool server.
* FastAPI backend and frontend integration.
* Five-container Docker architecture.
* MLflow experiment tracking and LangSmith observability.

[**NL-to-SQL Agent**](https://github.com/anantshri1/nl2sql-agentic-pipeline) · An agentic natural-language-to-SQL pipeline using hybrid retrieval and execution-guided self-correction.
* 54.5% execution accuracy on BIRD Mini-Dev (36/66).
* Approximately 55% fewer schema prompt tokens compared with full-schema prompting.
* Retrieval ablations, failure-mode analysis, and execution-guided correction.
[🤗 demo](https://huggingface.co/spaces/anantshri1/nl2sql-agentic-pipeline)

### 🧠 Language Models: Adaptation, Evaluation & Safety
Exploring how models can be adapted to specialised domains, evaluated under challenging conditions, and made more reliable.

**Domain-Adaptive LLM Trilogy** · A three-stage exploration of language models for theoretical physics:
* [RAG](https://github.com/anantshri1/RAG_3dQFT) - retrieval over specialised physics knowledge.
* [GraphRAG](https://github.com/anantshri1/GraphRAG_3dQFT) - structured knowledge representations and graph-based retrieval.
* [QLoRA](https://github.com/anantshri1/domain_adapted-LLM_fine-tuning) - domain adaptation of Qwen2.5-3B using a physics-specific instruction dataset.

[**Low-Resource NMT**](https://github.com/anantshri1/low-resource-mt-malayalam) · Fine-tuning MarianMT for English-to-Malayalam translation using BPCC and NPTEL Shiksha data, with an emphasis on technical vocabulary and domain adaptation.

[**Multilingual LLM Safety & Red-Teaming**](https://github.com/anantshri1/lexsi-refusal) · Investigating multilingual prompt injection and refusal robustness, with a particular interest in whether refusal behaviour relies on shared internal computations across languages and whether interventions can generalise to languages unseen during training. *Hackathon - in progress*


### 📈 Additional Work

[**Reinforcement Learning for multi-player strategy games**](https://github.com/anantshri1/gdl_orbitwars) · Graph neural networks and reinforcement learning, exploring GATv2 policies, action masking, differentiable graph construction, and curriculum learning.

**Time Series Forecasting** · LSTM, Transformer, AutoTFT and XGBoost across [BTC/USDT](https://github.com/anantshri1/timeseries_forecasting_btc_prediction) and [Indian electricity-demand forecasting](https://github.com/anantshri1/timeseries_forecasting_energy-demands), including climate stress tests.

<!--
| Project | What it does | Stack |
|---|---|---|
|[**Neural Operators for PDEs**](https://github.com/anantshri1/fno-data-efficiency)|Benchmarking neural operator architectures to study how structural inductive bias influences sample efficiency.|`JAX` (`Equinox`), `Mlflow`|
| [**MolPredict Inference API**](https://github.com/anantshri1/homo-lumo-gat) · [API Service](https://homo-lumo-gat.fly.dev/docs)| A GATv2 inference API service for predicting HOMO-LUMO gaps of organic molecules; inference tools additionally deployed as an independent MCP server over SSE. | `PyTorch Geometric`, `FastAPI`, `Docker`, `RDKit`, `MCP` |
| [**Agentic AutoML Platform**](https://github.com/anantshri1/agentic-automl-platform) | LangGraph ReAct agent orchestrating end-to-end tabular ML pipelines via a modular MCP tool server; five-container Docker architecture with MLflow tracking and LangSmith observability | `LangGraph`, `MCP`, `FastAPI`, `Docker`, `MLflow`, `XGBoost`, `CatBoost`, `TensorFlow`, `scikit-learn`, `LangSmith`, `Mlflow` |
| [**NL-to-SQL Agentic Pipeline**](https://github.com/anantshri1/nl2sql-agentic-pipeline) · [🤗 demo](https://huggingface.co/spaces/anantshri1/nl2sql-agentic-pipeline) | Hybrid BM25 + embedding retrieval with RRF fusion and execution-guided self-correction; 54.5% execution accuracy on BIRD Mini-Dev, 55% token reduction; ablation harness with failure-mode taxonomy | `LangChain`, `Voyage AI`, SQL |
| [**Multi-Agent Symbolic Reasoning**](https://github.com/anantshri1/group-theoretic-agentic-pipeline) · [🤗 demo](https://huggingface.co/spaces/anantshri1/group-theoretic-agentic-pipeline) | Solver → verifier → critic loop with LangGraph conditional edges; SymPy verifier deployed as independent MCP server over SSE | `LangGraph`, `MCP`, `SymPy` |
| [**GDL/RL Agent: Orbit Wars**](https://github.com/anantshri1/gdl_orbitwars) | GATv2 policy network with action masking, differentiable k-NN graph edges, two-stage curriculum; documented four compounding training failures including silent SB3 optimiser bug | `PyTorch Geometric`, PPO, `SB3` |
| **Domain-Adaptive LLM Trilogy** | [RAG](https://github.com/anantshri1/RAG_3dQFT) → [GraphRAG](https://github.com/anantshri1/GraphRAG_3dQFT) → [QLoRA](https://github.com/anantshri1/domain_adapted-LLM_fine-tuning) fine-tuning pipeline over my physics PhD thesis; ontology-driven knowledge graph, 2× retrieval benchmark gain, domain-adapted Qwen2.5-3B ([🤗 adapter](https://huggingface.co/anantshri1/qwen2.5-3b-mirror-symmetry)) on free-tier T4 | QLoRA (`Unsloth`), `LlamaIndex`, GraphRAG (`NetworkX`, `Pydantic`) |
| **Deep Learning for Time Series Forecasting** | LSTM vs Transformer vs AutoTFT on [BTC/USDT](https://github.com/anantshri1/timeseries_forecasting_btc_prediction) (71k hrs); XGBoost [demand forecasting](https://github.com/anantshri1/timeseries_forecasting_energy-demands) on Grid India data with climate scenario simulation (+2°C/+4°C stress tests) and MLflow tracking | `PyTorch`, `TensorFlow`, `NeuralForecast`, `XGBoost`, `MLflow` |
| [**Low-Resource NMT: EN→ML**](https://github.com/anantshri1/low-resource-mt-malayalam) | MarianMT fine-tuned on BPCC + NPTEL Shiksha corpus; BLEU 15.48 → 32.61 (2× gain) on a low-resource pair where general-purpose models fail on technical vocabulary ([🤗 weights](https://huggingface.co/anantshri1/marian-en-ml-bpcc), [🤗 domain-adapted weights](https://huggingface.co/anantshri1/marian-en-ml-shiksha)) | MarianMT, Hugging Face |
-->

---

## 📬 Contact

[![Email](https://img.shields.io/badge/ashri@sissa.it-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:ashri@sissa.it)
[![Email](https://img.shields.io/badge/ashri@sissa.it-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:bookreaderanant@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anant-shri-518b36130/)
[![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/anantshri1)
[![INSPIRE](https://img.shields.io/badge/Publications-INSPIRE-blue?style=flat-square)](https://inspirehep.net/authors/2931640)
