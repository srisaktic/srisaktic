
# Hi 👋, I'm Sri Sakticharan

I'm an **AI/ML Engineer and Data Science professional** with experience in data analytics, applied machine learning, and NLP, backed by an **M.S. in Data Science from the New York Institute of Technology**.

My professional journey started in data analytics, working with insurance datasets, SQL-based reporting, data validation, and business intelligence. I later expanded into machine learning and NLP, working on document intelligence, text classification, and semantic search.

I enjoy developing **end-to-end ML and Generative AI applications** — from data preprocessing and feature engineering to model development, evaluation, API integration, and deployment. My projects involve Python, Scikit-learn, XGBoost, Hugging Face Transformers, RAG, vector databases, and LLM-powered agents.

I'm particularly interested in building AI systems that go beyond model experimentation and become practical, reliable applications.

📍 **Chennai, India | Open to opportunities in Bengaluru**

---

## 💼 Professional Experience

### 🧠 Machine Learning Engineer Intern (Part-time) | Aionix11
*August 2025 – May 2026*

Contributed to document intelligence and NLP workflows focused on making unstructured business information accessible through machine learning.

- Worked on PDF processing, data preparation, and text classification using Python, PyMuPDF, Pandas, TF-IDF, and Linear SVM.
- Developed semantic retrieval components using Sentence Transformers, vector embeddings, and FAISS.
- Participated in model evaluation, error analysis, and technical discussions with engineering teams.
- Gained exposure to downstream RAG and LLM architectures through collaboration and knowledge-sharing with senior engineers.

### 📊 Associate Software Engineer (Data Analytics) | Hexaware Technologies
*February 2022 – May 2023*

Worked on data analytics and business reporting for a U.S. insurance client, focusing on policy, premium, and plan-related datasets.

- Used SQL Server, Python, and Excel for data extraction, transformation, validation, and reconciliation.
- Worked with Tableau dashboards to analyze policy distribution, premium trends, and business performance metrics.
- Investigated reporting inconsistencies and supported recurring analytical requirements.
- Collaborated with analysts and technical teams to improve data quality and reporting reliability.

---

## 🔥 My Highlight Projects

### 🤖 Finance AI Research Assistant

**Agentic RAG | Financial Research | LLM Tool Calling**

Built an end-to-end AI research application that allows users to explore financial information from SEC 10-K filings of companies such as Apple, Microsoft, and NVIDIA.

The system combines **Voyage embeddings, Qdrant vector search, cross-encoder reranking, and Google Gemini** to retrieve relevant financial information and generate grounded responses.

🔗 [Live Demo](https://finance-ai-ui-vercel.vercel.app/)

**Highlights:**
- Built a document ingestion and retrieval pipeline with section-aware chunking, embeddings, vector search, and reranking.
- Integrated Gemini-powered tool calling for document retrieval, stock information, financial calculations, and news.
- Investigated retrieval failures and improved contextual relevance through chunking strategies and reranking.
- Added grounding instructions and evaluation checks to reduce unsupported LLM responses.
- Built a FastAPI backend and React frontend with Docker and GitHub Actions CI/CD.

**Tech Stack:** Python, FastAPI, Google Gemini, Voyage AI, Qdrant, Cross-Encoder, React, Docker, GitHub Actions, Vercel

---

### 🔐 Multimodal Phishing Detection — PhishGuard AI

**Deep Learning | NLP | Computer Vision | Multimodal Fusion**

Developed a multimodal phishing detection application that analyzes **email text, URLs, and images** using specialized machine learning and deep learning models.

The system combines predictions from individual modalities through weighted fusion to generate a final phishing classification.

🔗 [Live Demo](https://phishguard-ai-tau-one.vercel.app/)

**Model Architecture:**

- **Email Classification:** Fine-tuned BERT combined with TF-IDF and Linear SVM for contextual and lexical phishing detection.
- **URL Classification:** Fine-tuned BERT (`bert-base-uncased`) combined with Logistic Regression using structural URL features.
- **Image Classification:** CNN ensemble consisting of ResNet50, EfficientNet-B0, and DenseNet121.
- **Multimodal Fusion:** Weighted combination of email, URL, and image predictions, with weight normalization when modalities are unavailable.

**Why these models?**

- **BERT:** Captures contextual patterns in phishing language and URL representations.
- **TF-IDF + SVM:** Provides an efficient lexical classification approach that complements transformer-based predictions.
- **Logistic Regression:** Uses structural URL features to complement contextual URL classification.
- **CNN Ensemble:** Combines different convolutional architectures to capture visual patterns in phishing-related images.
- **Weighted Fusion:** Integrates signals across modalities for more comprehensive phishing detection.

**Highlights:**
- Developed and evaluated multiple ML and deep learning models across three modalities.
- Integrated predictions through a weighted multimodal inference workflow.
- Built an interactive React frontend and FastAPI backend.
- Deployed the frontend on Vercel and backend on Google Cloud Run.
- Explored federated learning and homomorphic encryption as privacy-preserving ML research directions.

**Tech Stack:** Python, PyTorch, Scikit-learn, Hugging Face Transformers, BERT, ResNet50, EfficientNet-B0, DenseNet121, FastAPI, React, TypeScript, Vercel, Google Cloud Run

---

### 🚗 Used Car Price Prediction — BMW

**Regression | Feature Engineering | Model Deployment**

Developed an end-to-end machine learning application to estimate used BMW car prices using vehicle specifications and historical pricing data.

Compared multiple regression approaches, including Linear Regression, Random Forest, and XGBoost, with XGBoost selected for the final prediction pipeline.

🔗 [Live Demo](https://bmw-price-predictor-rhbypw6b6qntxdt9cszde8.streamlit.app/)

**Highlights:**
- Performed exploratory data analysis, preprocessing, and feature engineering.
- Trained and evaluated regression models using metrics such as R² and MAE.
- Developed a prediction service using FastAPI and an interactive Streamlit interface.
- Containerized the application using Docker and initially deployed it on AWS EC2.
- Later moved the public demo to Streamlit Community Cloud after the AWS free-tier period ended.

**Tech Stack:** Python, Pandas, NumPy, Scikit-learn, XGBoost, FastAPI, Docker, Streamlit, AWS EC2

---

## 🛠️ Technical Skills

**Programming & Data:**  
Python, Java, SQL, MySQL, PostgreSQL, Pandas, NumPy, R

**Machine Learning & Data Science:**  
Scikit-learn, XGBoost, Regression, Classification, Random Forest, Feature Engineering, Model Evaluation, Matplotlib, Seaborn

**Deep Learning & NLP:**  
TensorFlow, Keras, PyTorch, Hugging Face Transformers, BERT, NLP, CNNs, TF-IDF, Sentence Transformers, FAISS

**Generative AI & Agentic AI:**  
RAG, Google Gemini, Voyage Embeddings, Qdrant, Cross-Encoder Reranking, Tool-Calling Agents, Prompt Engineering

**Backend & API Development:**  
FastAPI, Flask, REST APIs, Spring Boot

**MLOps & Deployment:**  
Docker, AWS EC2, AWS S3, GitHub Actions, CI/CD, MLflow, SHAP, Streamlit, Git

**Databases & Tools:**  
SQL Server, PostgreSQL, MySQL, MongoDB, Redis, Elasticsearch, Qdrant, JIRA, Postman

---

## 🧰 Tech Stack (Quick View)

<p align="left">
  <img src="https://skillicons.dev/icons?i=python,java,pytorch,tensorflow,sklearn,fastapi,flask,docker,aws,react,postgres,mongodb,git,github" />
</p>

---

## 🌱 Currently Exploring & Learning

- **Generative AI & Agentic Systems** — RAG, LLM tool calling, retrieval evaluation, and grounded generation.
- **Applied Machine Learning** — Model experimentation, feature engineering, evaluation, and explainability.
- **MLOps** — Model versioning, experiment tracking, automated testing, and deployment workflows.
- **AI Application Engineering** — FastAPI, Docker, cloud deployment, and scalable inference architecture.
- **Deep Learning & NLP** — Transformers, embeddings, fine-tuning, and multimodal ML.

---

## 💬 Ask Me About

Python, SQL, Machine Learning, XGBoost, NLP, Deep Learning, RAG, LLM Applications, FastAPI, Docker, AWS, Semantic Search, and Model Deployment.

---

## 🎓 Education

**Master of Science in Data Science**  
New York Institute of Technology, New York  
*September 2023 – May 2025*

**Bachelor of Engineering in Electronics and Communication Engineering**  
KCG College of Technology, Chennai  
*August 2018 – May 2022*

---

## 📫 How to Reach Me

- 📧 **Email:** [sri.sakticharan.kumar@gmail.com](mailto:sri.sakticharan.kumar@gmail.com)
- 💻 **GitHub:** [github.com/srisaktic](https://github.com/srisaktic)
- 💼 **LinkedIn:** [linkedin.com/in/sri-sakticharan](https://www.linkedin.com/in/sri-sakticharan/)
- 🌐 **Portfolio:** [saktiportfolious.netlify.app](https://saktiportfolious.netlify.app/)

---

⭐ *Interested in Machine Learning, Data Science, Generative AI, NLP, and building intelligent applications that solve real-world problems.*
