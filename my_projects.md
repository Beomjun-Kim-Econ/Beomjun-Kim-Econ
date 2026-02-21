# Data Analysis
## Credit Risk Prediction & Data Leakage Analysis · [Presentation (KO)](https://drive.google.com/file/d/1z9__440qEtHpcwM_USZb8urkWqzhLxYj/view?usp=sharing)

- **Description**  
  A research-focused project on credit risk prediction using real-world tabular data, with an emphasis on identifying, categorizing, and empirically validating different forms of data leakage in machine learning pipelines.

  Beyond conventional train–test leakage in tabular data, the project extends the analysis to semantic data leakage in natural language processing, demonstrating how meaning-level similarity between samples can inflate evaluation performance.

- **Tech Stack**  
  - Statistical Machine Learning  
  - CatBoost, Logistic Regression, Linear SVM  
  - Sentence-BERT embeddings  
  - FAISS (HNSW) for scalable similarity search  

- **Role & Contribution**  
  - Proposed the core research idea of semantic data leakage beyond exact-duplicate leakage  
  - Designed and conducted experiments to detect leakage using cosine similarity between sentence embeddings  
  - Built an experimental pipeline combining Sentence-BERT and FAISS to identify semantically overlapping train–test samples  
  - Analyzed performance degradation after leakage-aware data filtering, highlighting robustness and reproducibility issues

---

## Monetary Policy Surprise & News Sentiment Analysis  · [Presentation (KO)](https://drive.google.com/file/d/1gQQZPU531Op5OcjRbDsSlpCqWzKtzsvA/view?usp=drive_link)

- **Description**  
  An event-study–based time-series analysis examining how unexpected monetary policy decisions affect stock market volatility, incorporating news headline sentiment as a moderating factor.

- **Tech Stack**  
  - Time-Series Analysis & OLS with HAC (Newey–West) Standard Errors  
  - NLP (eKoNLPy)
  - Statistical Inference

- **Role & Contribution**  
  - Led the research design and structured an event-study framework using unexpected monetary policy shocks  
  - Built a Korean news sentiment pipeline using eKoNLPy with domain-specific lexicon adjustments  
  - Constructed event-window–based panel data (D-28 to D+7) and examined heterogeneous effects through interaction terms  
  - Applied robust standard errors to account for autocorrelation and conducted OLS diagnostic checks  



# Applied AI
## Korean Language Question Generation System · [GitHub Repository](https://github.com/kimdappi/KFL-AQGen-AI)

- **Description**  
  An LLM-based system for automatically generating Korean language learning questions, focusing on level-adaptive problem generation and structured outputs.

- **Tech Stack**  
  - LLM  
  - Agentic RAG  

- **Role & Contribution**  
  - Identified key user pain points through requirement analysis  
  - Secured external project funding (₩1,000,000) through a startup-support–oriented program  
  - Designed and structured core system functionalities  

---

## XAI Project: Medical Sleep Data Analysis·  [Presentation (KO)](https://drive.google.com/file/d/1gQQZPU531Op5OcjRbDsSlpCqWzKtzsvA/view?usp=sharing) · [GitHub Repository](https://github.com/ezzyoung/bitamintimeseries)

- **Description**  
  An analytical project applying various machine learning and deep learning models to large-scale medical sleep data, with a focus on model interpretability (XAI).

- **Tasks**  
  - Sleep stage classification  
  - Sleep disorder detection  
  - Sleep pattern clustering  

- **Tech Stack**  
  - Machine Learning / Deep Learning  
  - Large-scale open-source sleep datasets  
  - Explainable AI (XAI) techniques  

- **Role & Contribution**  
  - Designed data preprocessing and analysis pipelines  
  - Developed data utilization strategies based on problem formulation  
  - Implemented lightweight, on-device–deployable tree-based models, considering the constraints of physiological data
