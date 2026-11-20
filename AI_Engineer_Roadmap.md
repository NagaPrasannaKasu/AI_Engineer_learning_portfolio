# My AI Engineer Roadmap — 18 Topics

A personal, evolving roadmap organized into **5 phases and 18 topics**. The goal is to learn the foundations, build practical AI applications, and deploy and evaluate reliable systems.

**Suggested timeline:** 26 weeks (6 months), approximately 4–5 hours per day. The schedule is a guide, not a requirement to master every subject within six months.

## Phase 1 — Programming & Data Foundations

### 1. Python Programming
- [ ] Variables, data types, operators, conditions, loops, functions
- [ ] Lists, tuples, dictionaries, sets, comprehensions
- [ ] Iterators, generators, decorators
- [ ] Object-oriented programming (OOP)
- [ ] Exception handling, file handling, modules, packages
- [ ] Type hints, dataclasses, Pydantic
- [ ] Virtual environments, pip, uv
- [ ] Async programming (`asyncio`, `async/await`)
- [ ] Logging, debugging, unit tests (`pytest`)
- [ ] JSON, CSV, HTTP requests

### 2. Git, GitHub & Developer Tools
- [ ] Git fundamentals, branches, commits, merges
- [ ] GitHub, pull requests, code reviews
- [ ] GitHub Actions (CI/CD basics)
- [ ] VS Code, Jupyter Notebook
- [ ] Linux terminal and Bash commands
- [ ] Environment variables and secrets management
- [ ] Dependency management and code quality tools
- [ ] Claude Code and AI-assisted coding workflows

### 3. SQL & Databases
- [ ] SQL: `SELECT`, `WHERE`, `JOIN`, `GROUP BY`
- [ ] Subqueries, CTEs, window functions
- [ ] Database design and normalization
- [ ] PostgreSQL or MySQL
- [ ] Indexes, transactions, query optimization
- [ ] SQLAlchemy and ORM basics
- [ ] NoSQL concepts: MongoDB and Redis
- [ ] Database migrations

### 4. Data Analysis & Visualization
- [ ] NumPy: arrays, indexing, broadcasting, vectorization
- [ ] Pandas: DataFrames, cleaning, grouping, merging
- [ ] Exploratory data analysis (EDA)
- [ ] Missing values, outliers, feature engineering
- [ ] Matplotlib, Seaborn, Plotly
- [ ] Data storytelling and dashboards
- [ ] Data pipelines: ETL/ELT
- [ ] Data validation and quality checks

## Phase 2 — Mathematics, ML & Deep Learning

### 5. Mathematics for AI/ML
- [ ] Linear algebra: vectors, matrices, tensors
- [ ] Matrix multiplication, eigenvalues, eigenvectors
- [ ] Calculus: derivatives, gradients, chain rule
- [ ] Probability and statistics
- [ ] Distributions and Bayes' theorem
- [ ] Mean, variance, standard deviation
- [ ] Optimization: gradient descent, SGD, Adam
- [ ] Loss functions, regularization, numerical stability

### 6. Machine Learning
- [ ] Supervised, unsupervised, self-supervised learning
- [ ] Regression and classification
- [ ] Linear regression, logistic regression
- [ ] Decision trees, random forests, XGBoost, LightGBM
- [ ] K-means and PCA
- [ ] Feature engineering and preprocessing
- [ ] Train/validation/test splits, cross-validation
- [ ] Overfitting, underfitting, bias–variance tradeoff
- [ ] Accuracy, precision, recall, F1, ROC-AUC
- [ ] Hyperparameter tuning, scikit-learn
- [ ] Model saving and inference pipelines

### 7. Neural Networks & Deep Learning
- [ ] Perceptrons and artificial neural networks
- [ ] Forward propagation and backpropagation
- [ ] Activation functions and loss functions
- [ ] Optimizers and learning-rate schedules
- [ ] PyTorch: tensors, autograd, `nn.Module`
- [ ] Datasets, DataLoaders, training loops
- [ ] CNNs, RNNs, LSTMs, GRUs
- [ ] Embeddings and transfer learning
- [ ] GPU/CUDA fundamentals
- [ ] Mixed precision, batching, checkpoints
- [ ] Experiment tracking

## Phase 3 — NLP, Transformers & LLM Fundamentals

### 8. Natural Language Processing (NLP)
- [ ] Text preprocessing and normalization
- [ ] Tokenization, stemming, lemmatization
- [ ] Bag of Words and TF-IDF
- [ ] Word2Vec and GloVe
- [ ] Text classification and sentiment analysis
- [ ] Named Entity Recognition (NER)
- [ ] Semantic similarity and sentence embeddings
- [ ] NLP evaluation metrics
- [ ] spaCy, NLTK, Hugging Face

### 9. Transformers & LLM Architecture
- [ ] Attention, self-attention, multi-head attention
- [ ] Positional encoding and RoPE
- [ ] Transformer encoders and decoders
- [ ] Encoder-only, decoder-only, encoder-decoder models
- [ ] BERT, GPT, T5
- [ ] BPE, WordPiece, SentencePiece tokenization
- [ ] Context windows, tokens, embeddings
- [ ] Pretraining and next-token prediction
- [ ] Instruction tuning and alignment
- [ ] RLHF and DPO (conceptual)
- [ ] Mixture of Experts (MoE)
- [ ] KV cache, attention optimization, quantization

### 10. Generative AI & LLM APIs
- [ ] Generative AI fundamentals and foundation models
- [ ] Open-weight models and model selection
- [ ] OpenAI API
- [ ] Anthropic Claude API and Google Gemini API
- [ ] Chat / responses API patterns
- [ ] System, developer and user instructions
- [ ] Structured outputs and JSON Schema
- [ ] Function calling and tool calling
- [ ] Streaming responses
- [ ] Multimodal APIs: images, audio, vision
- [ ] Rate limits, retries, timeouts
- [ ] Token usage, cost management, prompt caching
- [ ] LLM gateways, provider routing and fallbacks

## Phase 4 — Building AI Applications

### 11. Prompt Engineering & Context Engineering
- [ ] Zero-shot and few-shot prompting
- [ ] Instruction and role design
- [ ] Prompt templates and structured outputs
- [ ] Reasoning-oriented prompting
- [ ] Context engineering and context-window management
- [ ] Conversation history and memory
- [ ] Prompt versioning and testing
- [ ] Prompt injection awareness
- [ ] Iterative generation, critique and refinement loops
- [ ] Human-in-the-loop workflows

### 12. RAG — Retrieval-Augmented Generation
- [ ] RAG architecture and document loading/parsing
- [ ] Text splitting and chunking strategies
- [ ] Embedding models
- [ ] FAISS, Chroma, Qdrant, Pinecone, pgvector
- [ ] Cosine similarity, dot product, indexing
- [ ] Metadata filtering
- [ ] Hybrid search and BM25
- [ ] Reranking and cross-encoders
- [ ] Query rewriting and multi-query retrieval
- [ ] Context assembly and source citations
- [ ] Advanced RAG and multi-hop retrieval
- [ ] RAG evaluation: faithfulness, relevance, recall
- [ ] Retrieval latency, cost and quality optimization
- [ ] Document permissions and access control

### 13. AI Agents & Agentic AI
- [ ] AI agent fundamentals and tool schemas
- [ ] Agent loop: plan → act → observe → repeat
- [ ] State management and agent memory
- [ ] ReAct, planning and reflection
- [ ] LangChain fundamentals
- [ ] LangGraph: state, nodes, edges, checkpoints
- [ ] Workflow orchestration and durable execution
- [ ] Multi-agent systems, handoffs, delegation
- [ ] Model Context Protocol (MCP)
- [ ] MCP clients, servers, tools and resources
- [ ] Human approval, interrupts and recovery
- [ ] Agent evaluation and tracing
- [ ] Retries, termination and failure handling
- [ ] Tool permissions and sandboxing

### 14. Fine-Tuning & Open Models
- [ ] Hugging Face Hub, Transformers, Datasets
- [ ] Model weights, configurations, tokenizers
- [ ] Open-weight model selection and licensing
- [ ] Fine-tuning vs RAG vs prompting
- [ ] Supervised fine-tuning (SFT)
- [ ] PEFT, LoRA, QLoRA
- [ ] 8-bit and 4-bit quantization
- [ ] Dataset preparation and instruction formatting
- [ ] TRL and PEFT libraries
- [ ] Training, validation, evaluation
- [ ] Catastrophic forgetting
- [ ] Model merging and adapters
- [ ] Ollama, llama.cpp, vLLM
- [ ] Model cards and dataset documentation

## Phase 5 — Production AI Engineering

### 15. Backend Development & AI System Design
- [ ] HTTP and REST APIs
- [ ] FastAPI and Pydantic validation
- [ ] Request/response schemas
- [ ] Authentication, authorization, JWT, OAuth basics
- [ ] Async APIs and background jobs
- [ ] WebSockets and streaming
- [ ] Redis caching
- [ ] Task queues and workers
- [ ] Model serving and inference endpoints
- [ ] API versioning and error handling
- [ ] Load balancing and scalability
- [ ] Latency, throughput and concurrency
- [ ] AI architecture diagrams and design tradeoffs
- [ ] Cost estimation and capacity planning

### 16. Docker, Cloud, CI/CD & Infrastructure
- [ ] Docker images, containers, volumes, Docker Compose
- [ ] Kubernetes fundamentals, deployments, services, autoscaling
- [ ] CI/CD with GitHub Actions
- [ ] Testing, building, deployment pipelines
- [ ] Cloud fundamentals: choose AWS, Azure or GCP first
- [ ] Cloud compute, storage, managed databases
- [ ] Identity and secrets management
- [ ] Infrastructure as Code: Terraform
- [ ] Development, staging and production environments
- [ ] Serverless deployment
- [ ] GPU hosting and inference infrastructure
- [ ] Monitoring and rollback

### 17. MLOps, LLMOps & Observability
- [ ] MLOps vs LLMOps
- [ ] Experiment tracking: MLflow, Weights & Biases
- [ ] Model registries and versioning
- [ ] Dataset versioning with DVC
- [ ] Model validation and evaluation
- [ ] Offline vs online evaluation
- [ ] Golden datasets and regression tests
- [ ] LLM-as-a-judge and limitations
- [ ] Human, RAG and agent evaluation
- [ ] LangSmith, Langfuse, OpenTelemetry
- [ ] Traces, logs and metrics
- [ ] Token, latency and cost monitoring
- [ ] Model drift and data drift
- [ ] Production feedback loops
- [ ] A/B testing and canary deployments
- [ ] Prompt/model versioning
- [ ] Incident response and rollback

### 18. AI Security, Safety & Guardrails
- [ ] AI security fundamentals
- [ ] OWASP Top 10 for LLM applications
- [ ] Direct and indirect prompt injection
- [ ] Jailbreaks and instruction hierarchy
- [ ] Sensitive information leakage
- [ ] PII detection and redaction
- [ ] Input/output validation and content moderation
- [ ] Guardrails and tool-call authorization
- [ ] Agent privilege boundaries
- [ ] RAG document poisoning
- [ ] Data privacy and retention
- [ ] API security and rate limiting
- [ ] Secrets management
- [ ] Supply-chain and model provenance risks
- [ ] Adversarial testing and red teaming
- [ ] Safety evaluation
- [ ] GDPR and EU AI Act awareness

---

## How I Plan to Use This Roadmap

- **Learn:** Study concepts in phase order while revisiting earlier topics as needed.
- **Practice:** Write code and complete hands-on exercises for each major topic.
- **Build:** Create projects combining multiple skills rather than only following tutorials.
- **Evaluate:** Test correctness, reliability, cost and safety of AI applications.
- **Document:** Write a short daily learning journal and publish useful project notes.
- **Improve:** Update the roadmap as tools and my understanding evolve.

**Priority:** Become strong in Python, APIs, RAG, agents, evaluation, FastAPI, Docker and practical deployment. Learn model theory deeply enough to reason about tradeoffs; treat advanced fine-tuning and Kubernetes as stretch topics within six months.

*This is my current personal AI Engineering learning roadmap, informed by research into other roadmaps. It is a working plan that I intend to follow and refine as I learn.*
