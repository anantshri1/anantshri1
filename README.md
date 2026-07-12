# Hi, I'm Anant 👋

My research focuses on **three-dimensional mirror symmetry** — classifying dual pairs in supersymmetric quantum field theories with minimal supersymmetry, an open problem for three decades. My doctoral work developed a systematic framework for constructing these dual pairs, with findings published in *Physical Review D* and the *Journal of High Energy Physics*. 

📄 Find my publications [here](https://inspirehep.net/authors/2931640)

Alongside the PhD, I have been building end-to-end ML engineering skills: agentic workflows, retrieval systems, geometric deep learning, time series forecasting, and domain-adaptive LLM training. The repositories below are the output of that work.

---

## 🛠 Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PostgreSQL Badge](https://img.shields.io/badge/MySQL-4169E1?logo=mysql&logoColor=fff&style=flat)
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
![Keras](https://img.shields.io/badge/-Keras-D00000?style=flat&logo=Keras)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![PyG Badge](https://img.shields.io/badge/PyG-3C2179?logo=pyg&logoColor=fff&style=flat)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189AB4?style=flat-square&logo=python&logoColor=white)
![HuggingFace](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![CatBoost](https://img.shields.io/badge/CatBoost-189AB4?style=flat-square&logo=python&logoColor=white)

**LLMs & Agentic AI**

![LangChain Badge](https://img.shields.io/badge/LangChain-7FC8FF?logo=langchain&logoColor=fff&style=flat)
![LangGraph Badge](https://img.shields.io/badge/LangGraph-7FC8FF?logo=langgraph&logoColor=fff&style=flat)
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-7B2FBE?style=flat-square&logo=python&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square&logo=modelcontextprotocol&logoColor=white)

**MLOps & Deployment**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![LangChain Badge](https://img.shields.io/badge/LangSmith-7FC8FF?logo=langchain&logoColor=fff&style=flat)
![Gradio Badge](https://img.shields.io/badge/Gradio-F97316?logo=gradio&logoColor=fff&style=flat)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## 🚀 Selected Projects

| Project | What it does | Stack |
|---|---|---|
| [**MolPredict Inference API**](https://github.com/anantshri1/homo-lumo-gat) · [API Service](https://homo-lumo-gat.fly.dev/docs)| A GATv2 inference API service for predicting HOMO-LUMO gaps of organic molecules; inference tools additionally deployed as an independent MCP server over SSE. | `PyTorch Geometric`, `FastAPI`, `Docker`, `RDKit`, `MCP` |
| [**Agentic AutoML Platform**](https://github.com/anantshri1/agentic-automl-platform) | LangGraph ReAct agent orchestrating end-to-end tabular ML pipelines via a modular MCP tool server; five-container Docker architecture with MLflow tracking and LangSmith observability | `LangGraph`, `MCP`, `FastAPI`, `Docker`, `MLflow`, `XGBoost`, `CatBoost`, `TensorFlow`, `scikit-learn`, `LangSmith` |
| [**NL-to-SQL Agentic Pipeline**](https://github.com/anantshri1/nl2sql-agentic-pipeline) · [🤗 demo](https://huggingface.co/spaces/anantshri1/nl2sql-agentic-pipeline) | Hybrid BM25 + embedding retrieval with RRF fusion and execution-guided self-correction; 54.5% execution accuracy on BIRD Mini-Dev, 55% token reduction; ablation harness with failure-mode taxonomy | `LangChain`, `Voyage AI`, SQL |
| [**Multi-Agent Symbolic Reasoning**](https://github.com/anantshri1/group-theoretic-agentic-pipeline) · [🤗 demo](https://huggingface.co/spaces/anantshri1/group-theoretic-agentic-pipeline) | Solver → verifier → critic loop with LangGraph conditional edges; SymPy verifier deployed as independent MCP server over SSE | `LangGraph`, `MCP`, `SymPy` |
| [**GDL/RL Agent: Orbit Wars**](https://github.com/anantshri1/gdl_orbitwars) | GATv2 policy network with action masking, differentiable k-NN graph edges, two-stage curriculum; documented four compounding training failures including silent SB3 optimiser bug | `PyTorch Geometric`, PPO, `SB3` |
| **Domain-Adaptive LLM Trilogy** | [RAG](https://github.com/anantshri1/RAG_3dQFT) → [GraphRAG](https://github.com/anantshri1/GraphRAG_3dQFT) → [QLoRA](https://github.com/anantshri1/domain_adapted-LLM_fine-tuning) fine-tuning pipeline over my physics PhD thesis; ontology-driven knowledge graph, 2× retrieval benchmark gain, domain-adapted Qwen2.5-3B ([🤗 adapter](https://huggingface.co/anantshri1/qwen2.5-3b-mirror-symmetry)) on free-tier T4 | QLoRA, `LlamaIndex`, GraphRAG (`NetworkX`, `Pydantic`) |
| **Deep Learning for Time Series Forecasting** | LSTM vs Transformer vs AutoTFT on [BTC/USDT](https://github.com/anantshri1/timeseries_forecasting_btc_prediction) (71k hrs); XGBoost [demand forecasting](https://github.com/anantshri1/timeseries_forecasting_energy-demands) on Grid India data with climate scenario simulation (+2°C/+4°C stress tests) and MLflow tracking | `PyTorch`, `TensorFlow`, `NeuralForecast`, `XGBoost` |
| [**Low-Resource NMT: EN→ML**](https://github.com/anantshri1/low-resource-mt-malayalam) | MarianMT fine-tuned on BPCC + NPTEL Shiksha corpus; BLEU 15.48 → 32.61 (2× gain) on a low-resource pair where general-purpose models fail on technical vocabulary ([🤗 weights](https://huggingface.co/anantshri1/marian-en-ml-bpcc), [🤗 domain-adapted weights](https://huggingface.co/anantshri1/marian-en-ml-shiksha)) | MarianMT, Hugging Face |

---

## 📬 Contact

[![Email](https://img.shields.io/badge/ashri@sissa.it-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:ashri@sissa.it)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anant-shri-518b36130/)
[![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/anantshri1)
[![INSPIRE](https://img.shields.io/badge/Publications-INSPIRE-blue?style=flat-square)](https://inspirehep.net/authors/2931640)
