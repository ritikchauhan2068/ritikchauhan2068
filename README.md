<!--
  GitHub profile README. Save it as README.md in a PUBLIC repo named exactly like your username:
  github.com/ritikchauhan2068/ritikchauhan2068

  Files that go with it (same repo):
    assets/header.svg                 animated banner (self-hosted, no third-party service)
    assets/streak.svg                 built by .github/workflows/streak.yml (your existing workflow)
    .github/workflows/snake.yml       builds the contribution snake onto the "output" branch

  Search for "REPLACE" before publishing: those links need your real repo URLs.
-->

<div align="center">

<img src="./assets/header.svg" alt="Ritik Chauhan, AI/ML and Backend Engineer. FastAPI, RAG, OCR automation." width="100%" />

<br>

*I build production AI systems and automation workflows that save small businesses hours of manual work every day.*

<br>

![Open to work](https://img.shields.io/badge/OPEN%20TO%20WORK-AI%2FML%20%C2%B7%20Python%20Backend%20%C2%B7%20Automation-2ea44f?style=for-the-badge)
![Location](https://img.shields.io/badge/India-Remote%20friendly-0A66C2?style=for-the-badge)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ritik-chauhan-06b279211/)
[![Portfolio](https://img.shields.io/badge/Portfolio-111111?style=for-the-badge&logo=netlify&logoColor=00C7B7)](https://voluble-panda-3a9ee0.netlify.app/)
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/ritikchauhan2068)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ritikchauhan2068@gmail.com)

</div>

---

## 📊 Impact at a glance

<div align="center">

<table>
  <tr>
    <td align="center" width="20%"><h2>2</h2>live client<br>deployments</td>
    <td align="center" width="20%"><h2>90%+</h2>OCR field<br>extraction accuracy</td>
    <td align="center" width="20%"><h2>2+ hrs</h2>manual entry saved(Testing)<br>every day</td>
    <td align="center" width="20%"><h2>10,000+</h2>real-estate listings<br>in the recommender</td>
    <td align="center" width="20%"><h2>18%</h2>relevance lift over<br>keyword baseline</td>
  </tr>
</table>

</div>

---

## 🧭 What I do

| | |
|---|---|
| 🤖 **LLM & RAG applications** | Document-grounded assistants with source citations, built on LangChain, FAISS, and Gemini |
| 📄 **OCR & document intelligence** | Turning WhatsApp images, invoices, and PDFs into validated, structured data |
| ⚙️ **Backend & automation** | FastAPI services, Google Sheets / n8n workflows, and Docker deployments on DigitalOcean and Render |

Since early 2025 I've been shipping backends for real clients.

---

## 🚀 Featured projects

### 📦 OCR-Powered Order Automation
Extracts structured order data from WhatsApp images, invoices, receipts, and PDFs, validates it against a schema, and syncs it to Google Sheets.

- ✅ **90%+** field extraction accuracy &nbsp;·&nbsp; ⏱️ saves **2+ hours** of manual entry every day
- Low-confidence records go to a review queue instead of the spreadsheet

`Python` `FastAPI` `Tesseract OCR` `LangChain` `Google Sheets API` `Docker`

🔗 [Repository](https://github.com/ritikchauhan2068/OCR-For-Business)

<details>
<summary><b>🔍 How it works</b></summary>

```mermaid
flowchart LR
    A[WhatsApp image / PDF / invoice] --> B[Preprocess + OCR]
    B --> C[Field extraction]
    C --> D{Schema valid and confident?}
    D -- yes --> E[Google Sheets sync]
    D -- no --> F[Manual review queue]
    F --> E
```

</details>

---

### 📚 DocuMind: Document-Grounded RAG Assistant
Ask questions about multi-page PDFs and get answers with **page-level citations**. Document isolation through UUID metadata filtering stops answers from leaking across files.

- FAISS similarity search with multi-turn conversational context
- Built for transparency: every answer points back to its source page

`Python` `FastAPI` `LangChain` `FAISS` `Google Gemini`

🔗 [Repository](https://github.com/ritikchauhan2068/REPLACE-WITH-DOCUMIND-REPO)

<details>
<summary><b>🔍 How it works</b></summary>

```mermaid
flowchart LR
    A[PDF upload] --> B[Split into page-tagged chunks]
    B --> C[(FAISS index + UUID metadata)]
    D[User question] --> E[Filter by document UUID]
    C --> E
    E --> F[Top-k similarity search]
    F --> G[Gemini answers with context]
    G --> H[Answer + page citations]
```

</details>

---

### 🏠 Property Recommendation Engine
Content-based recommender over **10,000+ scraped real-estate listings**, using engineered features (price per sq ft, locality tiers, amenity scores) and TF-IDF with cosine similarity.

- 📈 **18%** relevance lift over a keyword-search baseline
- Served through a low-latency API

`Python` `Scikit-learn` `BeautifulSoup` `NLP` `FastAPI`

🔗 [Repository](https://github.com/ritikchauhan2068/Flat-recommdation-system)

---

### 🌐 Client work in production

| Client | What I delivered | Live |
|---|---|---|
| **Heritage Almora** (hospitality) | Backend, cloud deployment, SEO, Google Business optimisation | [heritagealmora.com](https://www.heritagealmora.com) |
| **Auyrco Pharma** (Ayurvedic pharma) | Backend APIs, performance tuning, deployment automation, business workflow automation | [Live site](https://auyrcopharma-5.onrender.com) |

---

## 🛠️ Tech stack

**AI / ML**<br>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![Tesseract OCR](https://img.shields.io/badge/Tesseract%20OCR-3C3C3C?style=flat-square)

**Backend**<br>
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![REST](https://img.shields.io/badge/REST%20APIs-111111?style=flat-square)

**Automation**<br>
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google%20Sheets%20API-34A853?style=flat-square&logo=googlesheets&logoColor=white)
![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-3C3C3C?style=flat-square)

**DevOps & cloud**<br>
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![DigitalOcean](https://img.shields.io/badge/DigitalOcean-0080FF?style=flat-square&logo=digitalocean&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black)

---

## 📈 GitHub activity

<div align="center">

<!-- Snake: built daily by .github/workflows/snake.yml and served from the "output" branch -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ritikchauhan2068/ritikchauhan2068/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/ritikchauhan2068/ritikchauhan2068/output/github-snake.svg" />
  <img alt="Snake eating my GitHub contribution graph, one square per day I pushed code" src="https://raw.githubusercontent.com/ritikchauhan2068/ritikchauhan2068/output/github-snake.svg" />
</picture>

<br>

<!-- Streak: generated by .github/workflows/streak.yml into assets/streak.svg (no third-party image service) -->
<img alt="GitHub contribution streak" src="./assets/streak.svg" />

</div>

*Every square is a real day of work: the snake rebuilds itself every 24 hours.*

---

## 🤝 Work with me

Running a small business and drowning in manual data entry? I can help with:

- 📲 **Order and invoice capture**: WhatsApp images and PDFs straight into Google Sheets
- 💬 **Chat with your documents**: a RAG assistant that answers with citations
- 🔌 **Backends and integrations**: FastAPI, Google APIs, n8n workflows, Dockerised deployments

📧 [ritikchauhan2068@gmail.com](mailto:ritikchauhan2068@gmail.com) · 🌐 [Portfolio](https://voluble-panda-3a9ee0.netlify.app/)

---

## 🎯 Currently

- 🔭 Building LLM applications and AI agents on top of my RAG and OCR work
- 🌱 Going deeper on retrieval evaluation, MLOps, and production deployment
- 💬 Ask me about: FastAPI, RAG pipelines, OCR workflows, automating business operations

## 🧑‍💼 Background

- **Freelance Backend & Automation Engineer**, Jan 2025 to present
- **Data Scientist Intern**, InternPe, Feb to Apr 2024: IPL match prediction, 5 classifiers compared and tuned with GridSearchCV
- **B.Tech CSE**, Chaudhary Charan Singh University (2021-2025)
- **Generative AI for Data-Driven Business Decision-Making**, IIM Mumbai (MIT × NSDC)

---

<div align="center">

**Hiring for an AI/ML or backend role?** I'd love to talk: [ritikchauhan2068@gmail.com](mailto:ritikchauhan2068@gmail.com)

</div>
