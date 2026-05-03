<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=soft&color=0:f9f0eb,50:fde8d8,100:f5c6a0&height=180&section=header&text=Kenisha%20P&fontSize=78&fontColor=2d2d2d&fontAlignY=45&desc=Building+intelligent+systems+that+never+guess&descAlignY=68&descSize=17&animation=twinkling" />

</div>

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Crimson+Pro&weight=600&size=22&pause=1400&color=c0533a&center=true&vCenter=true&width=580&lines=NLP+that+understands+context%2C+not+just+words;RAG+systems+with+source+on+every+answer;LangGraph+%7C+FastAPI+%7C+ChromaDB+%7C+scikit-learn;Multimodal+AI+%7C+A%2FB+Testing+%7C+Python;B.Tech+AI+%26+ML+%E2%80%94+Bengaluru+2027" alt="Typing SVG" />

</div>

<br/>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/-Kenisha%20P-c0533a?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kenisha-p-5bb002314/)
&nbsp;
[![GitHub](https://img.shields.io/badge/-kenisha007-2d2d2d?style=flat-square&logo=github&logoColor=white)](https://github.com/kenisha007)
&nbsp;
![Location](https://img.shields.io/badge/-Bengaluru%2C%20India-6b8f6b?style=flat-square&logo=googlemaps&logoColor=white)
&nbsp;
![Status](https://img.shields.io/badge/-Open%20to%20Internships-f5a97f?style=flat-square)

</div>

---

<br/>

> *I build NLP systems that don't hallucinate, RAG pipelines that cite every answer, and AI backends that fail gracefully — with a human escalation ticket rather than a confident wrong answer.*

<br/>

---

## ✦ Who I Am

**Kenisha P** — AI & ML undergrad at **Global Academy of Technology, Bengaluru** (VTU, 2027), working at the edge of **language intelligence** and **production AI systems**.

My work is shaped by one conviction: **AI that can't explain itself shouldn't be trusted**. Every project I ship is grounded — in source documents, in statistical evidence, in interpretable signals.

I'm drawn to the hard parts of NLP — not just "what's the sentiment" but *why, with what confidence, and who should act on it.*

---

## ✦ What I Build

<br/>

### 🔍 CLARITY &nbsp;·&nbsp; *Intelligent Feedback Triage Engine*

> *Turn noisy customer text into actionable intelligence — one pipeline call.*

CLARITY is a production NLP microservice I designed around a simple frustration: most sentiment tools stop at a label. Real support teams need **urgency scores, topic signals, and team routing** — not just "negative."

Built on **FastAPI + scikit-learn + Pydantic v2**, it exposes 7 endpoints across preprocessing, sentiment analysis, priority scoring, topic detection, owner recommendation, token annotation, and a full end-to-end pipeline.

`FastAPI` &nbsp; `scikit-learn` &nbsp; `Pydantic v2` &nbsp; `uvicorn` &nbsp; `Python 3.11`

→ [**kenisha007/CLARITY**](https://github.com/kenisha007/CLARITY)

<br/>

### 🤖 RAG Customer Support Assistant &nbsp;·&nbsp; *No Hallucinations. Source Everything.*

> *Upload your support docs. Every answer traces back to them.*

This is a document-grounded chatbot that refuses to guess. It ingests any PDF knowledge base, embeds it into **ChromaDB**, and uses a **LangGraph workflow** to retrieve, synthesize, and attribute every response.

The part I'm proudest of: **confidence routing**. When retrieval similarity falls below 0.62 — or the intent signals something sensitive — the system generates a **human escalation ticket** instead of fabricating an answer. Local development works entirely offline via a **TF-IDF fallback** with no API quota.

`LangGraph` &nbsp; `LangChain` &nbsp; `ChromaDB` &nbsp; `OpenAI` &nbsp; `pypdf` &nbsp; `scikit-learn`

→ [**kenisha007/RAG-Based-Customer-Support-Assistant**](https://github.com/kenisha007/RAG-Based-Customer-Support-Assistant)

<br/>

### 🧠 SilentSigns &nbsp;·&nbsp; *Passive Neurological Screening — Cognizant Technoverse 2026*

> *Your phone already knows. It just hasn't been asked the right questions.*

SilentSigns is a smartphone-native **passive Parkinson's disease screening platform** that detects early neurological biomarkers without any clinical intervention. The system runs entirely on-device using **TinyML**, analysing four passive signal streams — voice tremor, typing dynamics, gait patterns, and touch pressure — to surface early warning indicators of Parkinson's.

No wearable. No hospital visit. Just the phone people already carry.

`TinyML` &nbsp; `Digital Biomarkers` &nbsp; `Signal Processing` &nbsp; `Python` &nbsp; `On-device ML`

→ [**kenisha007**](https://github.com/kenisha007)

<br/>

### 🎙️ Parkinson's Analyzer &nbsp;·&nbsp; *Voice-Based Neurological Screening*

> *Three seconds of sustained vowel. One number between 0 and 1.*

A multilingual voice screening system that detects Parkinson's disease from a short "aaaah" recording — no wearable, no clinic, no language barrier. Built on **wav2vec2-XLS-R**, a self-supervised speech model pretrained across 128 languages, its frozen embeddings feed a lightweight logistic classifier trained on Italian PD patients.

The most honest part of this project is what it reports about generalization: hand-crafted acoustic features (MDVP) break completely when you train on one language and test on another. wav2vec2 embeddings don't — because they've seen Indian, Italian, and English speech during pretraining. That cross-corpus failure is a known but underreported problem in medical speech AI. This project tests it explicitly and reports it honestly.

| Metric | Value |
|--------|-------|
| CV AUC *(5-fold, subject-grouped)* | **0.972 ± 0.034** |
| Subject-level AUC | **0.996** |
| Accuracy | **94.2%** |
| Training data | 831 recordings · 61 subjects |

`wav2vec2-XLS-R` &nbsp; `PyTorch` &nbsp; `scikit-learn` &nbsp; `praat-parselmouth` &nbsp; `Flask` &nbsp; `Optuna`

→ [**kenisha007/Parkinson-s\_voice\_detection**](https://github.com/kenisha007/Parkinson-s_voice_detection)

<br/>

### 🧪 A/B Testing Framework &nbsp;·&nbsp; *Statistical Rigor, Deployed*

> *Because "it feels like it works" is not a product decision.*

End-to-end A/B testing pipeline covering experiment design, hypothesis testing, p-value computation, effect size analysis, and a Flask dashboard for reporting — with a Procfile for live deployment.

`Python` &nbsp; `Flask` &nbsp; `scipy` &nbsp; `pandas` &nbsp; `Deployed`

→ [**ab-testing-project**](https://github.com/kenisha007/ab-testing-project) &nbsp;·&nbsp; [**A-B-Testing**](https://github.com/kenisha007/A-B-Testing)

---

## ✦ Toolkit

```
Language          Python 3.11+
NLP / LLMs        LangChain · LangGraph · HuggingFace · spaCy · NLTK
Vector Search     ChromaDB · TF-IDF · OpenAI Embeddings
ML                scikit-learn · TensorFlow · pandas · NumPy · scipy
Backend           FastAPI · Flask · Pydantic · uvicorn
Frontend          HTML · CSS · JavaScript
Visualization     Matplotlib · Plotly · Jupyter
Version Control   Git · GitHub
```

---

## ✦ Stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=kenisha007&show_icons=true&hide_border=true&bg_color=fdf6f0&title_color=c0533a&icon_color=c0533a&text_color=2d2d2d&count_private=true" />
&nbsp;
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=kenisha007&layout=compact&hide_border=true&bg_color=fdf6f0&title_color=c0533a&text_color=2d2d2d&langs_count=6" />

<br/><br/>

<img src="https://streak-stats.demolab.com?user=kenisha007&hide_border=true&background=fdf6f0&stroke=e8d5c4&ring=c0533a&fire=c0533a&currStreakLabel=c0533a&dates=2d2d2d&sideLabels=2d2d2d" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=kenisha007&bg_color=fdf6f0&color=c0533a&line=c0533a&point=2d2d2d&hide_border=true&area=true&area_color=fde8d8" width="95%" />

</div>

---

## ✦ Highlights

| | |
|---|---|
| 🥇 | **Cognizant Technoverse Hackathon 2026** — SilentSigns: passive Parkinson's screening via TinyML + digital biomarkers |
| 🎙️ | **Parkinson's Analyzer** — wav2vec2-XLS-R voice screening · Subject AUC 0.996 · 94.2% accuracy · cross-lingual generalization |
| ⚙️ | **CLARITY** — 7-endpoint NLP triage microservice with urgency scoring + team routing |
| 📄 | **RAG Assistant** — Confidence-routed, source-attributed, hallucination-free support bot |
| 📊 | **A/B Testing** — Deployed statistical experimentation framework with live dashboard |

---

<div align="center">

<br/>

[![LinkedIn](https://img.shields.io/badge/Let's%20connect%20on%20LinkedIn-c0533a?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kenisha-p-5bb002314/)

<br/>

<img width="100%" src="https://capsule-render.vercel.app/api?type=soft&color=0:f5c6a0,50:fde8d8,100:f9f0eb&height=100&section=footer&reversal=true" />

</div>
