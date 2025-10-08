# Taha Slime

**Software & Systems Engineer / ML Systems • Full Stack• Low & High Level**

Montreal, QC · [CV Projects](#selected-projects) · taha.slime@gmail.com

I build fast, reliable systems end‑to‑end. From C/epoll servers and x86_64 assembly to Python ML training and model deployment.

## Highlights
- Fine‑tuning compact LLMs (Phi‑2) with LoRA + 4‑bit; REST integration
- BPE tokenizer in Python & C++ (max‑heap + custom hash table, benchmarks)
- Vector database from scratch (L2/cosine, simple APIs, RAG hooks)
- Cross‑language socket programming (C/C++ `epoll`, Java NIO, Python `asyncio`, Node.js)
- SIMD float calculator in x86_64 (NASM, SSE; manual parsing/formatting)
- Redis‑compatible key‑value store in C (RESP parser, `epoll`, open‑addressing hash table)


## What I Build
- Fast backend infra (Redis clone, tokenizer engine, vector DB)
- From-scratch implementations (hash tables, epoll servers, RESP parser, BPE)
- End-to-end ML pipelines (LoRA, tokenization, deployment)
- Cross-language low-level systems (C, C++, Python, NASM, Java, Node.js)


## Selected Projects
- **Neural Network from Scratch** — minimal DL framework + training loop  
  Repo: https://github.com/tslime/NeuralNetworkModel
- **BPE Tokenizer (Python & C++)** — subword tokenizer with heap + hash table  
  Repo: https://github.com/tslime/BPEAlgorithm
- **Socket Programming Analysis** — concurrency & networking across 4 languages  
  Repo: https://github.com/tslime/NetworkProgramming
- **Redis Clone in C** — minimalist Redis‑compatible server  
  Repo: https://github.com/tslime/vRedisClone
- **SIMD Float Calculator (x86_64)** — NASM + SSE, ASCII/float I/O  
  Repo: https://github.com/tslime/LowLevelProgramming/tree/main/Assemblycaclulator

- **Vector DB** — A vector database built from scratch in C++ using Hierarchical Navigable Small World (HNSW) graphs. Features index-based design (no pointers), custom heaps, and efficient nearest-neighbor search.  
  Repo: https://github.com/tslime/VectorDB

## More Projects

- **FlightRecorder/Telemetrie** — C++17 telemetry logger and visualizer simulating an aircraft black box.
Features binary packet serialization, CRC16 validation, and real-time altitude/velocity plotting via Gnuplot, with upcoming support for compression and live streaming.
Repo: https://github.com/tslime/FlightRecorder

- **Secure Inference Gateway** — Secure, API-key protected gateway for serving local AI models via HTTP, designed for internal networks and sensitive environments. Features dynamic model discovery, centralized logging, and easy integration with Ollama for on-premise LLM deployment. Suitable for defense and mission-critical systems with extensible authentication and compliance options.  
  Repo: https://github.com/tslime/SecureInferenceGateway
  
- **Data Provenance Tracker** — Lightweight tool to track, log, and hash file transformations for data integrity, auditability, and reproducibility (supports SHA-256, timestamping, JSONL logs, and optional timeline plotting).  
  Repo: https://github.com/tslime/Datatracker

- **Fundamental Algorithms** — core CS algorithms across languages  
  Repo: https://github.com/tslime/FundamentalAlgorithms

- **Special Data Structures** — Experimental and advanced structures built from scratch (custom hash tables, HNSW index for vector search, max-heaps for BPE, etc.).  
  Repo: https://github.com/tslime/SpecialDataStructures


## Tech

**Languages**: C, C++, Python, Java  
**Systems Programming**: x86_64 NASM (SIMD, SSE), socket programming (epoll, NIO, asyncio), Redis protocol (RESP), compilers/parsers, OS-level tools, embedded & robotics  
**Machine Learning**: Neural networks, ML algorithms (regression, SVM, trees, clustering), deep learning, synthetic data pipelines, LoRA, 4-bit quantization, PyTorch, TensorFlow  
**Backend & Full Stack**: Node.js, Express, REST APIs, PostgreSQL, MySQL, React  
**Infra & DevOps**: Linux, Docker, Kubernetes  
**Tools**: Git, GitHub, LaTeX, CircleCI  


