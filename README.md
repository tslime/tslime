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


## 🧠 Selected Projects

### 🤖 AI & Machine Learning
- **Neural Network from Scratch** — Minimal deep learning framework implementing backpropagation, gradient descent, and activation functions using NumPy.  
  🔗 Repo: [tslime/NeuralNetworkModel](https://github.com/tslime/NeuralNetworkModel)

- **BPE Tokenizer (Python & C++)** — Custom subword tokenizer using Byte Pair Encoding with heap-based pair frequency tracking and hash table indexing.  
  🔗 Repo: [tslime/BPEAlgorithm](https://github.com/tslime/BPEAlgorithm)

- **VectorDB (C++)** — Vector database built from scratch using Hierarchical Navigable Small World (HNSW) graphs. Features index-based design, custom heaps, and efficient nearest-neighbor search.  
  🔗 Repo: [tslime/VectorDB](https://github.com/tslime/VectorDB)

- **Phi-2 Fine-Tuning Suite** — Framework for fine-tuning small language models using synthetic datasets, LoRA, and 4-bit quantization on multi-GPU systems.  
  🔗 Repo: [tslime/Phi2FineTuningSuite](#)

---

### ⚙️ Systems & Performance Engineering
- **SIMD Matrix Algorithm (x86_64)** — NASM + SSE/AVX optimized matrix operations with loop unrolling, memory alignment, and RDTSC benchmarking.  
  🔗 Repo: [tslime/SIMDMatrixAlgorithm](https://github.com/tslime/SIMDMatrixAlgorithm)

- **Redis Clone (C)** — Minimalist Redis-compatible server built from scratch with custom TCP networking, RESP parser, and multi-client concurrency.  
  🔗 Repo: [tslime/vRedisClone](https://github.com/tslime/vRedisClone)

- **Socket Programming Analysis** — Cross-language networking study (C, C++, Java, Python) using concurrency models such as epoll, fork, NIO, and asyncio.  
  🔗 Repo: [tslime/NetworkProgramming](https://github.com/tslime/NetworkProgramming)

- **ROSKernel (Microkernel)** — Custom x86 microkernel with bootloader, GDT setup, protected mode transition, and early paging/IDT initialization.  
  🔗 Repo: [tslime/ROSKernel](#)

---

### 🔒 Security & Infrastructure
- **Secure Inference Gateway** — FastAPI-based secure gateway for serving local AI models (Ollama). Supports API-key authentication, model discovery, centralized logging, and compliance-ready configuration.  
  🔗 Repo: [tslime/SecureInferenceGateway](https://github.com/tslime/SecureInferenceGateway)

- **Data Provenance Tracker** — Lightweight tool to log, hash, and audit data transformations for integrity and reproducibility. Supports SHA-256, timestamping, and JSONL-based provenance chains.  
  🔗 Repo: [tslime/Datatracker](https://github.com/tslime/Datatracker)

---

### 🧠 Simulation & Control Systems
- **PID Controller Simulator (C++)** — Real-time closed-loop feedback system visualized with Gnuplot. Demonstrates proportional, integral, and derivative tuning and system stability.  
  🔗 Repo: [tslime/PIDControllerSimulator](https://github.com/tslime/PIDControllerSimulator)

- **Flight Recorder / Telemetry (C++)** — Aircraft telemetry simulator with binary packet serialization, CRC-16 validation, and live altitude/velocity plotting via Gnuplot.  
  🔗 Repo: [tslime/FlightRecorder](https://github.com/tslime/FlightRecorder)

---

### 🧩 Core Algorithms & Data Structures
- **Special Data Structures** — Experimental implementations of advanced structures (custom hash tables, max-heaps for BPE, HNSW indexes).  
  🔗 Repo: [tslime/SpecialDataStructures](https://github.com/tslime/SpecialDataStructures)

- **Fundamental Algorithms** — Core computer-science algorithms implemented across multiple languages for clarity and benchmarking.  
  🔗 Repo: [tslime/FundamentalAlgorithms](https://github.com/tslime/FundamentalAlgorithms)



## Tech

**Languages:** C, C++, Python, Java, Rust  
**Systems Programming:** x86_64 NASM (SIMD, SSE), socket programming (epoll, NIO, asyncio), Redis protocol (RESP), compilers/parsers, OS-level tools, embedded & robotics  
**Machine Learning:** Neural networks, ML algorithms (regression, SVM, trees, clustering), deep learning, synthetic data pipelines, LoRA, 4-bit quantization, PyTorch, TensorFlow  
**Full Stack Web:** Node.js, Express, PostgreSQL, MySQL, HTML/CSS, JS/TS (React, Node.js, Express), API REST, PHP, ASP.NET, Spring Boot  
**Infra & DevOps:** MLFlow, Docker, Kubernetes, Terraform, DVC, AWS/Azure, GitHub, CI/CD  
**Tools:** Git, GitHub, LaTeX, CircleCI  
**OS:** Linux, Windows, MacOS  




