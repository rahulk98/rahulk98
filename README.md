# Hi, I'm Rahul Krishnan

ML researcher and engineer. I work on LLM inference efficiency and AI safety: KV cache compression, linear probes, and evaluation.

MSc Data Science at the University of Trier (thesis submitted, October 2026). Before that, four years of backend engineering at SAP Labs India.

## Papers

- **A JoLT for the KV Cache: Near-Lossless KV Cache Compression via Joint Rank-Bit Allocation.** Under review at ICLR 2027. [arXiv](https://arxiv.org/abs/2607.12550)
- **Tensor Decomposition of Transformer Key-Value Caches: Spectral Structure and Format Comparison.** Under review at Numerical Linear Algebra with Applications. [arXiv](https://arxiv.org/abs/2609.28029)
- **Glaucoma Detection from Retinal Fundus Images.** ICCSP 2020. [IEEE](https://ieeexplore.ieee.org/document/9182388)

## Projects

- [**JoLT**](https://github.com/rahulk98/JoLT-Master-Thesis) and [**FlashJoLT**](https://github.com/rahulk98/flashjolt): training-free KV cache compression, near-lossless at 2x to 3x across 5 models and 4 families.
- [**Safety probes under KV cache compression**](https://github.com/rahulk98/kv-compression-safety-probes): do safety probes still catch harmful requests when the KV cache is compressed? [Write-up](https://rahulkrishnan.me/kv-compression-safety-probes/)
- [**Detecting unfaithful chain of thought**](https://github.com/rahulk98/cot-unfaithfulness): can linear probes or LLM monitors tell when a model follows a hint without saying so? [Write-up](https://rahulkrishnan.me/cot-hint-probes/)
- [**FEAR**](https://github.com/rahulk98/project-fear): does punishing wrong answers in GRPO teach a model to abstain honestly? It did not; the model gamed the grader instead. [Write-up](https://rahulkrishnan.me/grpo-abstention-dial/)
- [**LENS**](https://github.com/rahulk98/NarrativeSimilarity): SemEval-2026 story similarity with LLM-built story graphs, a GNN, and text embeddings.
- [**Amazon recommender**](https://github.com/rahulk98/Amazon-Product-Recommendation-System): two-tower model with FAISS retrieval, deployed on Azure.
- [**Resume RAG**](https://github.com/rahulk98/Resume-RAG-System): RAG over my resume with LlamaIndex and Gemini, deployed on Cloud Run.

## Tools

Python, PyTorch, Triton, Hugging Face, vLLM, TRL, PyTorch Geometric, Docker, FastAPI, GCP, Azure

## Contact

[rahulkrishnan.me](https://rahulkrishnan.me), [LinkedIn](https://linkedin.com/in/rahulk98), rahulkrishnan1105@gmail.com
