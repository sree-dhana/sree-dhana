<div align="center">

<img src="assets/name.svg" alt="𝑹 𝑺𝑹𝑬𝑬𝑫𝑯𝑨𝑵𝑨" width="620" height="90"/>

**AI & Backend Developer · Agentic AI · LLM Systems**

![Open to Work](https://img.shields.io/badge/STATUS-OPEN%20TO%20INTERNSHIPS-2cc5e8?style=for-the-badge&labelColor=0f2027)
![Hackathon](https://img.shields.io/badge/%F0%9F%8F%86%20WINNER-INFINIX%20DATA%20CHALLENGE%202026-f5b82e?style=for-the-badge&labelColor=0f2027)
![Location](https://img.shields.io/badge/BASED%20IN-BANGALORE%2C%20INDIA-203a43?style=for-the-badge&labelColor=0f2027)
![CGPA](https://img.shields.io/badge/CGPA-9.2-2c5364?style=for-the-badge&labelColor=0f2027)

![Followers](https://img.shields.io/github/followers/sree-dhana?style=flat-square&color=203a43&logo=github)

</div>

---

## ⚡ TL;DR

```python
class RSreedhana:
    role        = "AI & Backend Developer"
    education   = "B.Tech CSE (AI & Data Science), Reva University (2024-2028), CGPA 9.2"
    experience  =  BACKEND AI(AGENTIC) DEVELOPER @ Geoace Studio
    wins        = ["Winner, INFINIX Data Challenge (CMRIT Bangalore, 2026)"]
    leadership  = ["Tech Lead, Google Developer Group", "Tech Core Member, Alverse"]
    superpower  = ["agentic AI", "LangChain + LangGraph", "RAG pipelines", "safe, explainable AI decisions"]
    looking_for = "AI / LLM / Agentic AI internship"

    def ship(self, idea):
        return self.build(idea).containerize().deploy().iterate()
```

---

## 🧰 Tech Arsenal

<div align="center">

<img src="https://skillicons.dev/icons?i=py,cpp,bash,linux,fastapi,nodejs,express,react,vite,tailwind&theme=dark" />
<br/>
<img src="https://skillicons.dev/icons?i=docker,mongodb,sqlite,gcp,githubactions,git,tensorflow,opencv&theme=dark" />

<br/><br/>

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=2cc5e8)
![RAG](https://img.shields.io/badge/RAG_Pipelines-203a43?style=for-the-badge)
![Transformers](https://img.shields.io/badge/Transformers_%2F_BERT-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)

![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![spaCy](https://img.shields.io/badge/spaCy-09A3D5?style=for-the-badge&logo=spacy&logoColor=white)
![Tesseract](https://img.shields.io/badge/Tesseract_OCR-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Earth Engine](https://img.shields.io/badge/Google_Earth_Engine-34A853?style=for-the-badge&logo=googleearthengine&logoColor=white)
![Razorpay](https://img.shields.io/badge/Razorpay-0C2451?style=for-the-badge&logo=razorpay&logoColor=white)

</div>

---

## 🚀 Featured Projects

### 💳 [payRescue](https://github.com/sree-dhana/payRescue): AI Payment Recovery System

> **Built to solve problems.** The model estimates recovery probability; deterministic rules pick the action, keeping every decision safe and explainable.

```mermaid
flowchart LR
    A["💸 Failed payment<br/>Razorpay webhook<br/>(signature-verified)"] --> B["🤖 AI model<br/>predict recovery probability"]
    B --> C{"⚖️ Deterministic<br/>policy layer"}
    C -->|"probability ≥ 30%"| D["🔁 Retry"]
    C -->|"insufficient funds"| E["🔗 Send payment link"]
    C -->|"fraud signal"| F["🛑 Stop"]
    C -->|"otherwise"| G["🙋 Escalate"]
    D --> H[("🧾 Audit log<br/>SQLite")]
    E --> H
    F --> H
    G --> H
    H --> I["📊 Dashboard<br/>React · Recharts"]
```

- **FastAPI** backend with **Razorpay Test Mode** checkout and **signature-verified webhooks**
- **SQLite** tracking, an **audit log**, and recovery-strategy analytics
- **React + Vite + Tailwind + Recharts** frontend dashboard

`FastAPI` `React` `Vite` `Tailwind` `Recharts` `SQLite` `Razorpay`

<br/>

### 💊 [Medicine Recognition & Advisory System](https://github.com/sree-dhana/healthcare_system)

> Turns a photo of a prescription into structured data, dosage guidance, and reminders.

```mermaid
flowchart LR
    A["📷 Prescription image"] --> B["🧹 OpenCV<br/>preprocessing"]
    B --> C["🔤 Tesseract OCR"]
    C --> D["🧠 spaCy<br/>medicine + dosage extraction"]
    D --> E["🗂️ Structured data"]
    E --> F["🤖 LLM via LangChain<br/>Gemini / Ollama<br/>dosage guidance"]
    E --> G[("🍃 MongoDB<br/>prescription + user data")]
    F --> H["⚙️ FastAPI backend<br/>Docker"]
    G --> H
    H --> I["⏰ Medicine reminders"]
    H --> J["🩺 Doctor-patient<br/>interaction"]
```

- Extracts medicine names and dosage details from prescription images, turning **unstructured text into structured data**
- **FastAPI + MongoDB** backend with reminder scheduling and a doctor-patient interaction module
- Containerized with **Docker**

`FastAPI` `MongoDB` `OpenCV` `Tesseract` `spaCy` `LangChain` `Docker`

---

## 📈 Activity

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=sree-dhana&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0f2027&title_color=2cc5e8&icon_color=2cc5e8" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sree-dhana&layout=compact&theme=tokyonight&hide_border=true&bg_color=0f2027&title_color=2cc5e8" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=sree-dhana&theme=tokyonight&hide_border=true&background=0f2027&ring=2cc5e8&fire=2cc5e8&currStreakLabel=2cc5e8" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=sree-dhana&bg_color=0f2027&color=2cc5e8&line=2cc5e8&point=ffffff&area=true&area_color=2cc5e8&hide_border=true" width="95%" />

</div>

---

## 🐍 Contribution Snake

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/sree-dhana/sree-dhana/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/sree-dhana/sree-dhana/output/github-snake.svg" />
  <img alt="Contribution snake" src="https://raw.githubusercontent.com/sree-dhana/sree-dhana/output/github-snake.svg" />
</picture>

</div>

---

## 🎯 Currently

| | |
|---|---|
| 🔭 **Exploring** | Agentic AI with LangGraph: planning, tool use, multi-agent coordination |
| 🛠️ **Hardening** | RAG and LLM apps for production: reliability, evaluation, deployment |
| 📚 **Learning** | NLP with Transformers / BERT, TensorFlow and scikit-learn |
| 💬 **Ask me about** | LangChain pipelines, FastAPI backends, OCR + LLM workflows, safe AI decision policies |

---

## 🤝 Let's Build Something

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sreedhana-r-82b279282/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rsreedhana05@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sree-dhana)

</div>
