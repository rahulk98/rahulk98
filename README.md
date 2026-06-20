# Hi, I'm Rahul Krishnan

**MSc Data Science at Universitat Trier. Previously four years of backend engineering at SAP Labs India. I build ML systems end to end, from training and experimentation to production deployment.**

## About

I work across the full ML stack: training and experimentation, evaluation, and production deployment. I am finishing my MSc Data Science at Universitat Trier (grade 1.5) after four years of backend engineering at SAP Labs India. My current focus is LLM efficiency and evaluation: KV cache compression, calibration and selective abstention, chain-of-thought faithfulness, and neuro-symbolic methods. I care about reproducible results, so I lean on multi-seed evaluation, ablations, and honest reporting of what did not work.

## Currently

- MSc Data Science at Universitat Trier, 85 credits completed, grade 1.5, expected completion September 2026.
- MSc thesis on KV cache compression for LLM inference under Prof. Dr. Volker Schulz, submission June to July 2026. Early results show substantially lower reconstruction error than current published methods at the same compression ratio. Paper in preparation, technique details withheld until publication.
- Student Assistant for Numerical Optimization under Prof. Schulz, summer 2026.
- Independent research on LLM calibration, chain-of-thought faithfulness, and neuro-symbolic narrative modeling (see Featured Projects below).
- Learning German (currently B1.1).

## Featured Projects

<a href="https://github.com/rahulk98/project-fear">
  <img src="https://github-readme-stats-henna-seven-72.vercel.app/api/pin/?username=rahulk98&repo=project-fear&theme=tokyonight" alt="Project FEAR" />
</a>

Does punishing wrong answers more heavily than rewarding correct ones make a model better calibrated and more willing to abstain when it is uncertain? I built a complete GRPO training and calibration-evaluation pipeline on Qwen 2.5 1.5B and 3B, then swept seven reward conditions across six reasoning benchmarks. The empirical answer was no, and the explanation became the contribution. Finding O: under GRPO with within-group z-score advantage normalization, the entire reward design collapses to a single abstention-threshold dial, so per-question calibration cannot improve. Confirmed at 3B scale with a normalization ablation and a cross-task transfer test.

<a href="https://github.com/rahulk98/cot-unfaithfulness">
  <img src="https://github-readme-stats-henna-seven-72.vercel.app/api/pin/?username=rahulk98&repo=cot-unfaithfulness&theme=tokyonight" alt="Reflective CoT Faithfulness Study" />
</a>

Does a reflect-and-revise step make chain-of-thought reasoning more faithful, or does it mainly make rationalizations more convincing? This study extends the counterfactual simulatability setup from Turpin et al. 2023 to reflective chain of thought, across 13 BIG-Bench Hard categories and 650 instances on Gemini 2.5 Flash Lite and LLaMA 3.2 3B. Reflective CoT cut average bias susceptibility by about 7 percentage points versus standard CoT, but did not remove systematic unfaithfulness.

<a href="https://github.com/rahulk98/NarrativeSimilarity">
  <img src="https://github-readme-stats-henna-seven-72.vercel.app/api/pin/?username=rahulk98&repo=NarrativeSimilarity&theme=tokyonight" alt="LENS neuro-symbolic narrative similarity" />
</a>

LENS, my system for SemEval-2026 Task 4 (Narrative Story Similarity). An LLM decomposes each story into themes, actions, and outcomes, a heterogeneous GNN learns a graph embedding from that structure, and an additive fusion combines it with a text embedding so the final similarity score stays interpretable per modality. 72.5% pairwise accuracy and 95% cross-lingual precision across five languages.

<a href="https://github.com/rahulk98/Amazon-Product-Recommendation-System">
  <img src="https://github-readme-stats-henna-seven-72.vercel.app/api/pin/?username=rahulk98&repo=Amazon-Product-Recommendation-System&theme=tokyonight" alt="Amazon Recommender System" />
</a>

Two-Tower MLP + FAISS retrieval on the Amazon Electronics Reviews 2023 dataset. NDCG@10 = 0.334 (+9.5% over the collaborative filtering baseline), sub-100ms inference latency on CPU, deployed on Azure Container Apps.

<a href="https://github.com/rahulk98/Resume-RAG-System">
  <img src="https://github-readme-stats-henna-seven-72.vercel.app/api/pin/?username=rahulk98&repo=Resume-RAG-System&theme=tokyonight" alt="Resume RAG System" />
</a>

LlamaIndex + Google Gemini 2.5 Flash RAG over my resume and personal documents. FastAPI backend, containerized with Docker, deployed on Google Cloud Run. Live at rahul-krishnan.is-a.dev.

More projects: [Sentiment Analysis with BERT](https://github.com/rahulk98/Sentiment-Analysis-with-BERT-Model) (fine-tuned BERT on 10k+ YouTube comments, F1 = 0.82, served via Flask + Docker with a GitHub Actions CI/CD pipeline) and [Risk-Averse Optimization case studies](https://github.com/rahulk98/Research-Case-Studies_Risk-Averse-Optimization) (CVaR-based nonlinear optimization, robust SVM, and wine-fermentation MPC, where the CVaR MPC controller held constraint violations at 0% against a baseline that violated on every trajectory).

## GitHub Stats

<p align="center">
  <img height="180em" src="https://github-readme-stats-henna-seven-72.vercel.app/api?username=rahulk98&show_icons=true&theme=tokyonight&count_private=true&hide_border=true" alt="Rahul's GitHub stats" />
  <img height="180em" src="https://github-readme-stats-henna-seven-72.vercel.app/api/top-langs/?username=rahulk98&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages" />
</p>

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=flat&logo=mathworks&logoColor=white)

**ML & Deep Learning**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![PyTorch Geometric](https://img.shields.io/badge/PyG-3C2179?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat&logo=huggingface&logoColor=black)
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-5A2EFA?style=flat&logoColor=white)

**LLM & RL**

![PEFT / LoRA](https://img.shields.io/badge/PEFT%20%2F%20LoRA-FFD21E?style=flat&logo=huggingface&logoColor=black)
![GRPO / RLVR](https://img.shields.io/badge/GRPO%20%2F%20RLVR-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google%20Gemini-8E75B2?style=flat&logo=googlegemini&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat&logo=ollama&logoColor=white)

**MLOps & Deployment**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat&logo=googlecloud&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)

**Data & Databases**

![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![SAP HANA](https://img.shields.io/badge/SAP%20HANA-0FAAFF?style=flat&logo=sap&logoColor=white)

## Connect

- Portfolio: [rahul-krishnan.is-a.dev](https://rahul-krishnan.is-a.dev)
- LinkedIn: [linkedin.com/in/rahulk98](https://linkedin.com/in/rahulk98)
- Email: rahulkrishnan1105@gmail.com
</content>
</invoke>
