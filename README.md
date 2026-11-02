### Hi, I'm Jiawei (Leo) Liu

MS Applied Data Science student at the University of Chicago, graduating December 2026. I build data pipelines and
machine learning systems, and I like results that can be traced back to the data and code that produced them.

**Focus:** data engineering · ML pipelines and MLOps · NLP · forecasting

#### Projects

| Project | What it does | Built with |
|---|---|---|
| [athletes-mlops-pipeline](https://github.com/Leo37257/athletes-mlops-pipeline) | One Airflow DAG takes 423K CrossFit athlete records from a DVC-tracked file through dbt, Feast and MLflow to an Evidently drift report. Every training run records the exact data and code versions behind it. | Airflow, dbt, DuckDB, Feast, MLflow, DVC, Evidently, Docker |
| [F1-Pit-Stop-Prediction](https://github.com/Leo37257/F1-Pit-Stop-Prediction) | Team lead. Predicts whether a driver pits on the next lap: AutoML training, a FastAPI service with a race dashboard ([live demo](https://f1-pit-predictor-6u64.onrender.com/)), and drift monitoring. Macro-F1 0.801. | FLAML, MLflow, FastAPI, React, Airflow, Evidently |
| [NLP_AI_news_sentiment](https://github.com/Leo37257/NLP_AI_news_sentiment) | Which industries does AI news cover, and how positively? BERTopic on 115K articles (topic coherence 0.163 → 0.228 NPMI against TF-IDF + K-Means) and a fine-tuned RoBERTa sentiment model (82.3% test accuracy). | BERTopic, RoBERTa, spaCy, PyTorch |
| [us-natural-gas-demand-forecasting](https://github.com/Leo37257/us-natural-gas-demand-forecasting) | Re-tests a course project's model ranking with rolling-origin cross-validation. The model that won the single holdout drops to second. | R, forecast |
| [nyc-yellow-taxi-analytics](https://github.com/Leo37257/nyc-yellow-taxi-analytics) | 58.9M taxi trips joined with hourly weather on GCP Dataproc, then fare regression (RMSE 3.667 → 2.141) and tip-rate classification. | PySpark, Spark MLlib, GCP Dataproc |

#### Experience

- **Power Kiosk** (UChicago capstone, 2026 –) · building the Rate Agent of a multi-agent system that writes daily
  market briefings for energy brokers. Client project, so the code is private.
- **NeuroMuse**, generative AI music startup (Software Engineer Intern, summer 2026) · ingestion pipelines for a 1M+
  item music dataset drawn from 30 sources, and a DynamoDB index audit that cut write cost on AWS.
- **Capgemini**, Shanghai (Data Scientist Intern, summer 2025) · extracting automotive parts from car-review text with
  open-source LLMs.

#### Tools

Python · SQL · R · PySpark · dbt · Airflow · DuckDB · PyTorch · Hugging Face · scikit-learn · MLflow · Docker · FastAPI ·
GCP · AWS

#### Education

MS Applied Data Science, University of Chicago (Dec 2026) · BSc Mathematics & Business, University of Edinburgh (2025)

[LinkedIn](https://www.linkedin.com/in/jiawei-liu-6637122a1/)
