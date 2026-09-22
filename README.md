<h1 align="center">Bruno Sancho Deltell</h1>

<p align="center">
  <b>AI Engineer · Machine Learning Engineer</b><br>
  <sub>Dublin, Ireland</sub>
</p>

<p align="center">
  <a href="https://linkedin.com/in/bruno-sancho-deltell"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:b.sancho.deltell@gmail.com"><img src="https://img.shields.io/badge/Email-1f2937?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://link.springer.com/chapter/10.1007/978-3-032-19763-4_49"><img src="https://img.shields.io/badge/Published_Research-B31B1B?style=for-the-badge&logo=googlescholar&logoColor=white" alt="Research"></a>
</p>

---

AI engineer working across LLM and agent systems, computer vision and multimodal deep learning. Mostly Python.

What interests me is the whole path rather than any one piece of it: the model and the data work, then the API around it, the deployment, the evaluation harness, and the monitoring that tells you when something has quietly started to drift. Most of what I have built ends up in production with people depending on it, which turns out to be a good teacher about latency budgets, failure modes and honest evaluation.

M.Sc. in Artificial Intelligence, 9.11/10. Based in Dublin.

<br>

## 🎙️ [SyncoLabs](https://synco.es) — AI voice agents for local businesses

Self-hosted conversational platform, live with paying B2B clients. LiveKit Agents orchestrating streaming speech-to-text, LLMs served at **~250 ms time-to-first-token** and multi-vendor TTS, all over SIP telephony.

Multi-tenant from the ground up: per-client agent configuration, auto-discovered function-calling tools, a FastAPI backend with JWT auth and a React operations dashboard. **860+ automated tests** across 97 suites, with per-call latency breakdowns and provider cost reconciliation.

`Python` `LiveKit` `FastAPI` `SIP` `Docker` `React`

## 📖 [TuCuento](https://tucuento.es) — generative AI, end to end

Personalised illustrated children's books, generated and then physically printed and delivered. LLM storytelling with content-safety filtering, image generation, automated cover and PDF assembly, and print-on-demand fulfilment.

`Next.js` `Supabase` `Stripe` `Replicate`

## 🏆 [AquaDEX](https://aquadex-alc.vercel.app) — 1st place, Aguas de Alicante Data Hackathon

Location intelligence scoring commercial viability across **1,591 geospatial nodes** in 48 neighbourhoods, fusing 28 data sources — hourly water telemetry, cadastral records, OpenStreetMap mobility, census, rents and tourism.

LSTM temporal models, a GraphSAGE graph neural network over the urban network, and HDBSCAN clustering, with SHAP explainability. Scores returned in under ten seconds.

`PyTorch` `GNN` `LSTM` `HDBSCAN` `SHAP`

<br>

---

## 🔬 Research — 3DPerceptionLabs, University of Alicante

Deep learning for fine-grained animal behaviour recognition in the wild.

**[Exploring Temporal Action Segmentation Techniques for Enhanced Bird Behavior Recognition](https://link.springer.com/chapter/10.1007/978-3-032-19763-4_49)** · *published* — SOCO 2025, Springer CCIS vol. 2806. Frame-level and segment-level pipelines benchmarked over I3D, R(2+1)D, MViT-B and PDAN backbones. [Code](https://github.com/bsd7-ua/birds-temporal-action-segmentation).

**[ViP-BiRd: Multimodal Fine-Grained Bird Behavior Recognition via RGB Video and Pose Data](https://github.com/3dperceptionlab/vip-bird)** · *under review* — multimodal architecture fusing V-JEPA video representations with ST-GCN++ skeletal motion over a custom 10-node avian graph. Reaches **55.91%** on Visual WetlandBirds against 49.46% RGB-only and 47.31% pose-only, showing the gain comes from the fusion itself. Master's thesis, graded 10/10.

**Predicting Avian Occurrence in Mediterranean Wetlands** · *under review* — second author. ValWet-Birds, a harmonised dataset unifying professional censuses, eBird citizen science and Raspberry Pi acoustic sensors across three protected wetlands (2010–2025, 395 species). LSTM occurrence models cut test MSE by 42.7% over census-only training.

<br>

## 🎓 Education

**M.Sc. Artificial Intelligence** — University of Alicante, 2025–2026. Overall 9.11/10, taught entirely in English. Thesis graded 10/10.

**B.Sc. Computer Engineering (Ingeniería Informática)** — University of Alicante, 2021–2025. Computing specialisation: theory of computation, automated reasoning, computer vision and robotics, language processing. Final-year project graded 10/10.

**Northern Arizona University**, USA — Erasmus+ exchange semester, Fall 2024. Upper-division computer science in English: Artificial Intelligence, Machine Learning, Algorithms, Automata Theory, Virtual Worlds. Top 5% of the senior Algorithms class.

<br>

## 🛠️ Tech

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,cpp,pytorch,tensorflow,fastapi,django,nextjs,react,docker,postgres,supabase,linux,git,ts" alt="Tech stack">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/LLM_Orchestration-1f2937?style=flat-square" alt="LLM Orchestration">
  <img src="https://img.shields.io/badge/Conversational_AI-1f2937?style=flat-square" alt="Conversational AI">
  <img src="https://img.shields.io/badge/Computer_Vision-1f2937?style=flat-square" alt="Computer Vision">
  <img src="https://img.shields.io/badge/Multimodal_Deep_Learning-1f2937?style=flat-square" alt="Multimodal Deep Learning">
  <img src="https://img.shields.io/badge/NLP-1f2937?style=flat-square" alt="NLP">
  <img src="https://img.shields.io/badge/MLOps-1f2937?style=flat-square" alt="MLOps">
</p>

<br>

## 📂 Also public

**[cpp-search-engine](https://github.com/73bruno/cpp-search-engine)** — a search engine written from scratch in C++ with no external libraries. Hand-written tokenizer state machine, inverted index with positional postings and disk spilling, Porter stemming, and BM25 / DFR ranking with TREC-format evaluation.

> Most of what I work on lives in private repositories — they are live commercial products with client data in them. The projects above are the ones I can open up, and I am happy to walk through the architecture of any of the others.

<br>

---

<p align="center">
  <sub>EU citizen · based in Dublin · open to AI/ML engineering roles</sub>
</p>
