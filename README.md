# Hi 👋, I'm Sri Sakticharan

I'm an **AI/ML Engineer and Backend Software Engineer** with 2+ years of professional experience, backed by an M.S. in Data Science from the New York Institute of Technology.

I build and deploy end-to-end machine learning and LLM/RAG systems — from data preprocessing and feature engineering through model training, evaluation, explainability, and production deployment — using Python, XGBoost, Scikit-learn, Hugging Face Transformers, and agentic tool-calling. On the backend side, I develop REST APIs and services using FastAPI, Flask, and Spring Boot, and deploy everything with Docker, AWS, MLflow, and CI/CD pipelines.

My academic background in Data Science introduced me to deep learning and NLP, where I worked on projects involving BERT, traditional ML (TF-IDF/SVM), CNN ensembles, and multimodal fusion architectures — with a focus on empirically selecting the right model per component rather than defaulting to the most complex option.

I enjoy working across the full lifecycle of a project: understanding a business problem, building the model or system, and deploying and monitoring the solution that solves it.

---

## 🔥 My Highlight Projects

- 🤖 **Finance AI Research Assistant** — agentic RAG system for financial research over SEC 10-K filings (Apple, Microsoft, Nvidia), combining Voyage embeddings, Qdrant vector search, cross-encoder reranking, and a Gemini-powered tool-calling agent with 5 tools (filing search, live market data, calculators, news) behind a FastAPI backend.
  🔗 [Live Demo](https://finance-ai-ui-vercel.vercel.app/)

  **Highlights:**
  - Diagnosed and fixed a multi-layer retrieval-quality failure via section-aware chunking and reranking.
  - Fixed an LLM hallucination bug (agent fabricating unsourced facts) through prompt-level grounding constraints.
  - Deployed end-to-end with Docker, automated testing, and GitHub Actions CI/CD that gates deployment on passing tests — FastAPI backend on Render, React frontend on Vercel, entirely on free-tier infrastructure ($0/month).

- 🔐 **Multimodal Phishing Detection** — end-to-end system combining TF-IDF + SVM for email/text classification, a BERT (bert-base-uncased) classifier for URL analysis, and a CNN ensemble (ResNet50 + EfficientNet-B0 + DenseNet121) for image classification, served behind a single Flask inference endpoint. Ensemble fusion via soft/hard voting improved F1 score by ~12% over single-model baselines. Each modality's model was selected empirically — testing multiple candidates and choosing the one that scored best *and* fused most reliably with the other modalities.
  🔗 [Live Demo](https://phishguard-ai-tau-one.vercel.app/)

  **Why these models:**
  - **BERT** (text) — phishing language relies on contextual social-engineering cues that keyword/TF-IDF methods miss; pretrained contextual embeddings transfer well on a relatively small phishing dataset.
  - **TF-IDF + SVM** (email/text) — a lightweight, fast baseline that complements BERT's contextual signal with straightforward lexical/keyword-based detection.
  - **ResNet50 + EfficientNet + DenseNet** (images) — three architecturally different CNN backbones (residual connections, compound scaling, dense feature reuse) reduce correlated errors in the voting ensemble more than using three variants of one architecture.
  - **Multimodal fusion** — phishing attacks vary in vector (text, URL, or visual impersonation); combining all three catches attacks a single-modality model would miss, driving the F1 improvement.
  - Also explored federated learning (Flower) and homomorphic encryption for privacy-preserving training.

- 🚗 **Used Car Price Prediction (BMW)** — regression pipeline (Random Forest, XGBoost) achieving ~90% R², deployed with FastAPI + Streamlit, containerized with Docker, hosted on AWS EC2 with a CI/CD workflow for automated updates.
  🔗 [Live Demo](https://bmw-price-predictor-rhbypw6b6qntxdt9cszde8.streamlit.app/)

---

## 🛠️ Technical Skills

**Languages:**
Python, Java, SQL, MySQL, PostgreSQL, R

**Backend Development:**
FastAPI, Flask, Spring Boot, REST APIs

**AI & Machine Learning:**
Scikit-learn, XGBoost, TensorFlow, Keras, Hugging Face Transformers, BERT, NLP, CNNs, Linear/Logistic Regression, Random Forest, Decision Tree

**LLM & Agentic AI:**
RAG, Google Gemini, Voyage Embeddings, Qdrant, Cross-Encoder Reranking, Tool-Calling Agents, Prompt Engineering

**MLOps & Monitoring:**
MLflow, SHAP, joblib, Streamlit

**Cloud & Deployment:**
AWS (EC2, Lambda, S3), Docker, OpenShift

**Databases & Caching:**
PostgreSQL, MySQL, MongoDB, Redis, Elasticsearch, Qdrant

**DevOps & Tools:**
Jenkins, GitHub Actions, CI/CD, SonarQube, JUnit, Mockito, Git, JIRA, Postman

---

## 🧰 Tech Stack (Quick View)

<p align="left">
  <img src="https://skillicons.dev/icons?i=java,python,fastapi,flask,spring,react,docker,aws,postgres,mongodb,redis" />
</p>

---

## 🌱 Currently working on

- Agentic RAG / LLM systems (FastAPI, Gemini, Qdrant)
- Production ML pipelines (FastAPI, Docker, AWS)
- Backend services (Spring Boot, FastAPI)
- Model deployment, monitoring, and explainability (MLflow, SHAP)

---

## 💬 Ask me about

Python, Java, Machine Learning, XGBoost, LLMs/RAG, FastAPI, Spring Boot, AWS, Docker, REST APIs

---

## 📫 How to reach me

- Email: sri.sakticharan.kumar@gmail.com
- GitHub: https://github.com/srisaktic
- LinkedIn: https://www.linkedin.com/in/sri-sakticharan/
