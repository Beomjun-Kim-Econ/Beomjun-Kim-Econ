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

## Monetary Policy Surprise & News Sentiment Analysis  · [Presentation (KO)](https://drive.google.com/file/d/1tT8k7YFXMzhjjQb0YTIFPWJyjXqrI8Ge/view?usp=drive_link)

* **Description**
  A one-week pilot, exploratory event-study time-series analysis testing whether unexpected monetary policy shocks are associated with next-day changes in stock market volatility, and whether Korean news headline sentiment moderates that response.

  Using Bank of Korea MPB surprise events as quasi-exogenous shocks, the project constructs an event-window panel and standardizes headline sentiment relative to a pre-event baseline to quantify abnormal news tone around the events.

* **Tech Stack**

  * Event-Study Design & Time-Series Regression
  * OLS with HAC (Newey–West) Standard Errors
  * NLP Sentiment Scoring (eKoNLPy + Mecab)
  * Regression Diagnostics (VIF, residual checks)

* **Role & Contribution**

  * Designed a heterogeneous-effects specification using interaction terms (Surprise × Low/High News) to test regime-dependent volatility responses
  * Built a Korean finance-domain headline sentiment pipeline (BigKinds sampling → Mecab tokenization → eKoNLPy lexicon scoring), including domain-specific lexicon adjustments
  * Engineered an event-window panel dataset (D-28 to D+7), defining a pre-event baseline (D-28 to D-7) and excluding the immediate pre-event window (D-6 to D-1) to reduce contamination
  * Implemented HAC-robust inference to account for autocorrelation and documented scope limitations (small number of surprise events) for transparent interpretation




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
