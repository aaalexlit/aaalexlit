### Hi, I'm Alex 👋

I'm an AI/Data Engineer, and I'm interested in everything ML/AI

🌱 I’m currently [Improving my statistical inferences](https://www.coursera.org/learn/statistical-inferences) with the help of wonderful [Daniel Lakens](https://www.tue.nl/en/research/researchers/daniel-lakens)

# My recent projects:

- [LLM-powered Question Answering Slack bot](#llm-powered-question-answering-slack-bot) (Ongoing)
- [End-to-end ML Vision Project on Blood Vessel Segmentation](#blood-vessel-segmentation)
- [Diabetes classification model training and deployment](#diabetes-classification-model-training-and-deployment)
- [End-to-end MLOps Pipeline](#end-to-end-mlops-pipeline)
- [Climate change-related news articles Scientific verification](#climate-change-related-news-articles-scientific-verification) (NLP-powered project for [Omdena](https://omdena.com/))

   
## LLM-powered Question Answering Slack bot
### to accompany 4 Zoomcamps by [DataTalksClub](https://www.linkedin.com/company/datatalks-club/)

### Project Repo
[Zoomcamp QA Bot](https://github.com/aaalexlit/faq-slack-bot)

### Behind the scenes

### Tech stack 
**Connecting the dots**  
[Llamaindex](https://www.llamaindex.ai/)  
**Vertor DB**  
[Milvus](https://milvus.io/) and
[Zilliz (Cloud-Native Milvus)](https://zilliz.com/)  
**Orchestration**  
[Prefect](https://www.prefect.io/)  
**Embeddings**  
[BAAI/bge-small-en-v1.5](https://huggingface.co/BAAI/bge-small-en-v1.5)  
**Re-ranker**  
[Cohere re-ranker](https://cohere.com/rerank)  


![The ingestion](https://github.com/aaalexlit/faq-slack-bot/blob/main/slack_bot_custom_ingestion.png)

[![Alternate Text](https://cdn.loom.com/sessions/thumbnails/8c80ed43bf2142a19865aeb6d89a3e1e-1688983509551-with-play.gif)](https://www.youtube.com/embed/ZTjrkcQIq6Q "MLOps FAQ Bot Demo")

---
## Blood Vessel Segmentation

Fine-tune [Ultralytics](https://www.ultralytics.com/) [YOLOv8](https://github.com/ultralytics/ultralytics) segmentation model on 
3D Hierarchical Phase-Contrast Tomography (HiP-CT) data from human kidneys to segment blood vessels.

### Project Repo
[Hacking the Human Vasculature](https://github.com/aaalexlit/hacking-human-vasculature)

EDA => Training => Hyperparameter tuning => Deployment as a service (FastAPI) => Containerization => Deployment to AWS EKS

![FastAPI Service screenshot](https://github.com/aaalexlit/hacking-human-vasculature/blob/main/images/openaoi_ui.png?raw=true)

---

## Diabetes classification model training and deployment

### Project Repo
[MLZoomcamp Midterm project](https://github.com/aaalexlit/ml_zoomcamp_midterm_cdc_diabetes)

- Trained several models
  - Logistic regression
  - Random Forest
  - [XGBoost](https://xgboost.ai/)
- Hyperparameter finetuning with
  - [Optuna](https://optuna.org/)
  - [Hyperopt](https://hyperopt.github.io/hyperopt/)
  - [Wandb Sweeps](https://docs.wandb.ai/guides/sweeps)
- Deploy containerized model with [FastAPI](https://fastapi.tiangolo.com/) on [AWS Elastic Beanstalk](https://aws.amazon.com/elasticbeanstalk)

---
## End-to-end MLOps Pipeline

![Workflow diagram](https://github.com/aaalexlit/capitalbikeshare-mlops/blob/main/docs/images/full_diagram_white.png)
### Project Repos
1. [Training pipeline](https://github.com/aaalexlit/capitalbikeshare-mlops)
2. [Prediction web service](https://github.com/aaalexlit/capitalbikeshare-service)
3. [Prediction web service IAC](https://github.com/aaalexlit/capitalbikeshare-service-terraform)

---
## Climate change-related news articles Scientific verification

A tool and an API for Climate change-related news articles Scientific verification and Global warming stance detection

### Components 
**NLP Framework**  
[Haystack](https://haystack.deepset.ai/)  
**Vertor DB**  
[FAISS](https://engineering.fb.com/2017/03/29/data-infrastructure/faiss-a-library-for-efficient-similarity-search/)  
**API**  
[FastAPI](https://fastapi.tiangolo.com/)  
**UI**  
[Streamlit](https://streamlit.io/)  
**Semantic Search**  
[Sentence Transformers](https://www.sbert.net/)  

![Application UI](https://github.com/aaalexlit/cc-omdena-streamlit/blob/main/streamlit_app.gif)

developed as a part of [Omdena's](https://omdena.com/) 
[Detecting Bias in Climate Reporting in English and German Language News Media](https://omdena.com/chapter-challenges/detecting-bias-in-climate-reporting-in-english-and-german-language-news-media/) Local Chapter Challenge

### Project Repos
1. [WebApp repo](https://github.com/aaalexlit/cc-omdena-streamlit)
2. [API repo](https://github.com/aaalexlit/cc-evidences-api)
3. [Auxiliary repo 1](https://github.com/aaalexlit/omdena_climate_change_challenge_notebooks)
   [Auxiliary repo 2](https://github.com/aaalexlit/cc-claim-verification)

---

[![Alex's GitHub stats](https://github-readme-stats.vercel.app/api?username=aaalexlit&count_private=true&show_icons=true)](https://github.com/anuraghazra/github-readme-stats)  
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=aaalexlit&size_weight=0&count_weight=1&langs_count=10&layout=compact)](https://github.com/anuraghazra/github-readme-stats)

<!--
**aaalexlit/aaalexlit** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
