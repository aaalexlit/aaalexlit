### Hi, I'm Alex 👋

I'm a long-time Software Developer and I'm interested in everything ML/AI

🌱 I’m currently learning with DataTalks Club [Machine Learning Zoomcamp](https://github.com/DataTalksClub/machine-learning-zoomcamp)

# My recent projects:

- [LLM-powered Question Answering Slack bot](#llm-powered-question-answering-slack-bot)
- [End-to-end MLOps Pipeline](#end-to-end-mlops-pipeline)
- [Climate change-related news articles Scientific verification](#climate-change-related-news-articles-scientific-verification) (NLP-powered project for [Omdena](https://omdena.com/))

   
## LLM-powered Question Answering Slack bot
### to accompany the [MLOps Zoomcamp](https://github.com/DataTalksClub/mlops-zoomcamp) by [DataTalksClub](https://www.linkedin.com/company/datatalks-club/)

### Behind the scenes

Course FAQ Google Document and the Course repo get indexed to the Pinecone vector store.  
Then semantic search retrieves the most similar (and hopefully most relevant) pieces to the question asked.  
Then this information is passed as a context to a conversational LLM to form the final answer.

![The workflow](https://github.com/aaalexlit/faq-slack-bot/blob/main/Mlops_chatbot_diagram.png)

### Components 
**The Star of the show**  
[LangChain](https://github.com/hwchase17/langchain)  
**Vertor DB**  
[Pinecone](https://www.pinecone.io/)  
**Orchestration**  
[Prefect](https://www.prefect.io/)  
**Semantic Search**  
[Sentence Transformers](https://www.sbert.net/)  

[![Alternate Text](https://cdn.loom.com/sessions/thumbnails/8c80ed43bf2142a19865aeb6d89a3e1e-1688983509551-with-play.gif)](https://www.youtube.com/embed/ZTjrkcQIq6Q "MLOps FAQ Bot Demo")

### Project Repo
[MLOps Zoomcamp QA Bot](https://github.com/aaalexlit/faq-slack-bot)

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
