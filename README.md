# Hi, I'm Khalil Damak 👋

**Final-year Computer Science Engineering student (Data Science & AI) at ESPRIT, Tunis.**
I build AI systems that run in the real world: LLM agents with tool calling, multi-agent platforms,
NLP models and ML pipelines, shipped behind APIs with tests and CI.

🎯 **Looking for a 6-month End-of-Studies internship (PFE) starting January 2027** in AI / Data Science / ML engineering.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-khalildamak-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/khalildamak)
[![Email](https://img.shields.io/badge/Email-khalil.damak02%40gmail.com-D14836?logo=gmail&logoColor=white)](mailto:khalil.damak02@gmail.com)
![Location](https://img.shields.io/badge/Tunis-Tunisia-555555)

---

## 🚀 Featured projects

### [Padel Academy WhatsApp Agent](https://github.com/kdamak02/padel-academy-whatsapp-agent) · LLM agent & automation
Daily session confirmations for a real padel academy in Tunis (~1,100 members) on the official WhatsApp Business API,
replacing manual phone calls. An **n8n LLM agent** with **tool calling** and **structured output** handles free-text
replies, with confidence-based guardrails and human fallback. Includes a WhatsApp/LLM simulator and **43 automated tests** in GitHub Actions.
`n8n` `WhatsApp Cloud API` `Google Apps Script` `LLM` `Docker` `CI`

### [orqestra (CallVerse)](https://github.com/boufadenghassen/callverse-app) · Multi-agent contact-center platform — team of 7
A contact-center digital twin with **7 specialized AI agents** orchestrated by NestJS over FastAPI.
I owned the **[Customer Advisor agent](https://github.com/boufadenghassen/callverse-app/blob/main/docs/agents/02-customer-advisor.md)**:
hybrid TF-IDF retrieval + **fine-tuned MiniLM** intent model (26K telecom messages, 26 intents, +10 pts over the TF-IDF baseline),
exported to **ONNX int8** (23 MB, 3 ms). Also integrated an LLM customer simulator (Qwen 2.5 7B via Ollama) with Whisper STT and Piper TTS.
`PyTorch` `Transformers` `ONNX` `FastAPI` `NestJS` `Ollama` `pytest`

### [AgriSmart](https://github.com/kdamak02/agrismart-full-system) · AI + IoT smart agriculture platform
Full-stack platform: plant disease detection, **NDVI/NDWI** satellite analysis, a **RAG** assistant and smart irrigation
on **ESP32 + Jetson Nano**. React frontend, Express/Prisma API, FastAPI AI services.
See also the edge component: [irrigation_agent](https://github.com/kdamak02/irrigation_agent) (LSTM soil-moisture forecasting driving the pump).
`FastAPI` `TensorFlow` `PyTorch` `YOLO` `RAG` `React` `PostgreSQL` `ESP32` `Jetson Nano`

### [Car Sound Doctor](https://github.com/kdamak02/car-sound-doctor) · Audio deep learning + LLM agents *(in progress)*
Send an engine sound on Telegram, get a likely fault, guided physical checks and a cited repair guide.
Three agents: an audio model service (AST embeddings, autoencoder anomaly detection) and two **LLM + RAG** agents (Qdrant), orchestrated with n8n.
`PyTorch` `Audio DL` `RAG` `Qdrant` `n8n` `FastAPI`

### [Tunicare Solutions website](https://github.com/kdamak02/tunicare-website) · Freelance · **live at [tunicare.tn](https://www.tunicare.tn)**
Corporate website for a medical-surgical equipment distributor in Tunisia, designed, built and deployed for a paying client:
product catalogue, quote requests through a contact-form API (Resend), SEO and Vercel deployment.
`Next.js` `TypeScript` `Tailwind CSS` `Vercel`

---

## 💼 Experience

- **Data Scientist Intern — Banque Zitouna** (Jul–Aug 2026): automated two BCT regulatory annexes (100% and 91%),
  reverse-engineered undocumented risk-classification rules, and built an Isolation Forest anomaly detector with 32 automated tests.
  *(Code is private: banking data.)*
- **IT Data Analyst Intern — Medikipment** (Jul–Aug 2025): parsed medical binary signal files into structured datasets and visualizations.

## 🛠️ Tech stack

**AI / Data:** LLM agents · tool calling · multi-agent systems · NLP · Transformers · RAG · ML / deep learning · anomaly detection  
**Languages:** Python · SQL · TypeScript · JavaScript · Java · C++ · R  
**Frameworks:** PyTorch · TensorFlow · scikit-learn · Hugging Face · ONNX · FastAPI · NestJS · Spring Boot · React · Next.js  
**Automation & ops:** n8n · Docker · GitHub Actions · pytest · AWS · Linux  
**Databases:** PostgreSQL · MySQL · MongoDB · Neo4j · Qdrant

## 📜 Certifications

NVIDIA DLI — Building Transformer-Based NLP Applications · Applications of AI for Anomaly Detection · Fundamentals of Deep Learning  
AWS Academy Graduate — Cloud Foundations

🌍 Arabic (native) · French · English · German (B1)
