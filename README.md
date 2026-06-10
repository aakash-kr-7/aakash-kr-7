<div align="center">

```
╔══════════════════════════════════════════════════════════════╗
║                                                              ║
║          I don't build features. I build systems.            ║
║                                                              ║
╚══════════════════════════════════════════════════════════════╝
```

# Aakash Kumar

**Backend Engineer · AI Systems · Distributed Architecture**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/aakash-kumar-978671274)
[![Portfolio](https://img.shields.io/badge/Portfolio-111827?style=flat-square&logo=github&logoColor=white)](https://aakash-kr-7.github.io)
[![Codolio](https://img.shields.io/badge/Codolio-6366F1?style=flat-square&logoColor=white)](https://codolio.com)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=black)](https://leetcode.com/aakashkr7)
[![CodeChef](https://img.shields.io/badge/CodeChef_3★-5B4638?style=flat-square&logo=codechef&logoColor=white)](https://codechef.com/users/e23cseu0161)
[![Views](https://komarev.com/ghpvc/?username=aakash-kr-7&label=profile+views&color=6366F1&style=flat-square)](https://github.com/aakash-kr-7)

</div>

---

## What I Actually Do

I build things that need serious infrastructure under the hood — systems where the interesting problems are in **memory architecture**, **async concurrency**, **vector retrieval**, and **behavioral simulation at scale**.

Not portfolio pieces. Not tutorials. Systems with real constraints: isolation guarantees, race-condition avoidance, zero-cost deployment, and behavior that holds up under load.

---

## Projects

### SOL — Distributed AI Relationship Platform
> `FastAPI` `Flutter` `ChromaDB` `SQLite` `Firebase` `FCM` `Railway`

The most technically demanding thing I've built. SOL is a persistent-memory AI platform with **12 autonomous personas**, each capable of evolving relationships, recalling emotional context, and initiating conversations — across thousands of concurrent users.

**The hard parts:**

```
Memory Layer       →  Pair-scoped ChromaDB namespaces. Zero cross-persona leakage.
Retrieval Engine   →  5-factor deterministic ranking: vector similarity + emotional
                      salience + memory strength + recency decay + unresolved context.
Personality Model  →  132 runtime coefficients per persona. Controls impulsiveness,
                      attachment speed, emotional volatility, texting cadence, and more.
Concurrency Model  →  Semaphore-controlled async workers, pair-level locks,
                      timeout-aware scheduling. No event-loop starvation.
Storage Layer      →  19 relational tables, 28 indexed query paths.
                      Telemetry separated from narrative retrieval.
Infra Cost         →  $0. Entire stack on free-tier services. Fully live.
```

**Memory signals extracted per conversation:** 30+ structured types — episodic memories, emotional events, behavioral tendencies, unresolved topics, relational links.

**Relationship model:** 6 behavioral metrics × 5 adaptive stages. Trust, rhythm, openness, comfort, familiarity — all continuously updated, all affecting response generation.

---

### AURORA — Speech Emotion Recognition System
> `Python` `CNN` `BiLSTM` `MFCC` `TensorFlow`

End-to-end SER pipeline trained on **10,000+ audio samples** across RAVDESS, CREMA-D, and TESS datasets.

| Model | Accuracy |
|-------|----------|
| SVM | 73% |
| BiLSTM | 82% |
| **CNN** | **95%** ✓ |

CNN dominates — as expected for extracting complex time-frequency patterns from 2D spectrograms. MFCC-based feature extraction pipeline with augmentation and dataset harmonization.

---

### AETHER — Full-Stack Wellness App
> `Flutter` `Firebase` `Firestore` `System Design`

Firestore backend with **8+ user-scoped collections** under a strict single-owner model. Custom security rules enforcing per-user data isolation. Time-series journal schemas built for future analytics pipelines.

20+ async UI states managed across 10+ network-bound screens — explicit error/loading/partial-render handling on every screen. No optimistic fallbacks.

**Top 100 University Projects — Bennett University, 2025.**

---

## Research

### Paraphrase-Robust Fake News Detection
> `NLP` `ML` `DL` `Sentence Embeddings` `Ensemble Models`

Built a paraphrase-aware detection pipeline across **190,000+ claims** and **33,294 unique paraphrase sets** — specifically designed to expose robustness failures under LLM-style paraphrased inputs.

**Best configuration (V5 — weighted lexical-semantic ensemble):**

```
Accuracy    →  0.7648
Precision   →  0.8219
Recall      →  0.7709
F1 Score    →  0.7956
Consistency →  0.9328    ← same prediction on original + paraphrase
Agreement   →  0.9375
```

Compared TF-IDF, MiniLM, MPNet, Logistic Regression across 5 model configurations.

---

## Stack

```python
languages   = ["Python", "Dart", "SQL", "Java", "C++"]
backend     = ["FastAPI", "REST APIs", "Async Python"]
databases   = ["SQLite", "ChromaDB", "Firestore", "Firebase", "Relational Design"]
mobile      = ["Flutter", "FCM", "Firebase Auth"]
ml_ai       = ["NLP", "Sentence Embeddings", "TF-IDF", "CNN/BiLSTM", "MFCC", "scikit-learn"]
systems     = ["Vector Retrieval", "Async Concurrency", "Clean Architecture", "Data Modeling"]
tools       = ["Git", "Linux", "Android Studio", "VS Code"]
```

---

## Background

- 🎓 **B.Tech CSE — Bennett University** · CGPA 9.19 · SAT 1530
- 🔐 **Certified Ethical Hacker (CEH)** — EC-Council · Feb 2026 – Mar 2027
- 💻 **350+ problems solved** across LeetCode, CodeChef (3★ Div. 3)
- 🏆 **Top 100 University Projects** — Bennett University (Aether, 2025)

---

## What I'm Focused On

Currently building deeper into **LLM engineering**, **vector database internals**, and **distributed system design**. Specifically: scaling retrieval pipelines for long-horizon memory and optimizing async concurrency patterns in Python.

Open to collaborating on backend infrastructure, data pipelines, or products that need a real architecture layer — not just scaffolding.

---

<div align="center">

`aakashkumar94303@gmail.com`

*"The backend is where the real decisions live."*

</div>
