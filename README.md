<div align="center">

```
 ░█████╗░░█████╗░██╗░░██╗░█████╗░░██████╗██╗░░██╗
 ██╔══██╗██╔══██╗██║░██╔╝██╔══██╗██╔════╝██║░░██║
 ███████║███████║█████═╝░███████║╚█████╗░███████║
 ██╔══██║██╔══██║██╔═██╗░██╔══██║░╚═══██╗██╔══██║
 ██║░░██║██║░░██║██║░╚██╗██║░░██║██████╔╝██║░░██║
 ╚═╝░░╚═╝╚═╝░░╚═╝╚═╝░░╚═╝╚═╝░░╚═╝╚═════╝╚═╝░░╚═╝
```

### `Backend Engineer · AI Systems · Distributed Architecture`

*I don't build features. I build the infrastructure that makes features possible.*

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/aakash-kumar-978671274)
[![Portfolio](https://img.shields.io/badge/Portfolio-0f0f0f?style=for-the-badge&logo=github&logoColor=white)](https://aakash-kr-7.github.io)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/aakashkr7)
[![CodeChef](https://img.shields.io/badge/CodeChef_3★-5B4638?style=for-the-badge&logo=codechef&logoColor=white)](https://codechef.com/users/e23cseu0161)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:aakashkumar94303@gmail.com)

![Profile Views](https://komarev.com/ghpvc/?username=aakash-kr-7&label=Profile%20Views&color=6366f1&style=for-the-badge)

</div>

---

<div align="center">

## ⚡ What I Actually Do

</div>

```python
class AakashKumar:

    focus      = ["Memory Architecture", "Async Concurrency", "Vector Retrieval", "Behavioral Simulation"]
    currently  = "Building SOL — a distributed AI relationship platform with persistent memory"
    learning   = ["Advanced System Design", "Vector DB Internals", "LLM Engineering", "Distributed Architectures"]
    open_to    = "Backend infra, data pipelines, or anything that needs a real architecture layer"
    fun_fact   = "Deployed a full multi-user AI backend with 12 autonomous personas for literally $0"

    def builds(self):
        return "Systems where the hard problems live in the backend — not the UI"
```

---

<div align="center">

## 🏗️ Projects

</div>

### 🔵 SOL — Distributed AI Relationship Platform

> `FastAPI` &nbsp;·&nbsp; `Flutter` &nbsp;·&nbsp; `ChromaDB` &nbsp;·&nbsp; `SQLite` &nbsp;·&nbsp; `Firebase` &nbsp;·&nbsp; `FCM` &nbsp;·&nbsp; `Railway`

**The most technically demanding thing I've built.** SOL is a persistent-memory AI platform with **12 autonomous personas**, each capable of evolving relationships, recalling emotional context, and initiating conversations — across thousands of concurrent users, at $0 operational cost.

<details>
<summary><b>🧠 Memory Architecture — Click to expand</b></summary>

<br/>

- **Pair-scoped ChromaDB namespaces** — every user-companion relationship gets its own isolated retrieval namespace. Zero cross-persona memory leakage at the storage layer.
- **Fully inspectable memory system** — users can view, edit, pin, delete, and override AI memories in real time, directly altering downstream retrieval, contextual recall, relationship state, and response generation.
- **30+ structured memory signal types** extracted per conversation — episodic memories, emotional events, behavioral tendencies, unresolved topics, entities, relational links.

</details>

<details>
<summary><b>⚙️ Retrieval Engine — Click to expand</b></summary>

<br/>

A **deterministic 5-factor ranking engine** built to solve long-horizon conversational drift:

```
Score = f(
  vector_similarity,       # semantic closeness
  emotional_salience,      # how emotionally significant the memory is
  memory_strength,         # reinforcement from repeated recalls
  recency_decay,           # time-weighted relevance
  unresolved_context_boost # unsettled threads get priority
)
```

</details>

<details>
<summary><b>🎭 Personality Simulation — Click to expand</b></summary>

<br/>

**132 runtime personality coefficients** per persona. Controls:

| Parameter | What it governs |
|-----------|----------------|
| `impulsiveness` | How quickly a persona responds without prompting |
| `attachment_speed` | Rate of emotional closeness formation |
| `emotional_volatility` | Swing range of mood-based response shifts |
| `texting_cadence` | Message pacing, length, and timing patterns |
| `loneliness_tolerance` | Threshold before proactive outreach triggers |
| `vulnerability_pacing` | How gradually deep topics are introduced |

</details>

<details>
<summary><b>🔄 Concurrency & Relationship Simulation — Click to expand</b></summary>

<br/>

- **Async lifecycle infrastructure** — semaphore-controlled worker pools, pair-level async locks, timeout-aware scheduling, executor-offloaded blocking I/O.
- **Relationship model** — 6 continuously updated behavioral metrics × 5 adaptive relationship stages. Trust, rhythm, openness, comfort, familiarity — all affecting live response generation.
- **Proactive messaging engine** — contextual callbacks, emotional check-ins, inactivity outreach, shared-world interactions — all under runtime-enforced cooldown, maturity, and quiet-hour constraints.

</details>

<details>
<summary><b>🗄️ Persistence & Infrastructure — Click to expand</b></summary>

<br/>

```
Storage Layer  →  19 relational tables, 28 indexed query paths
               →  High-frequency emotional telemetry separated from
                  long-term narrative retrieval and behavioral analytics
Infra          →  FastAPI backend + ChromaDB + async workers + SQLite + FCM
               →  Entire stack on free-tier services
Cost           →  $0.00 — fully live, multi-user, production system
```

</details>

---

### 🟣 AURORA — Speech Emotion Recognition System

> `Python` &nbsp;·&nbsp; `CNN` &nbsp;·&nbsp; `BiLSTM` &nbsp;·&nbsp; `MFCC Feature Engineering` &nbsp;·&nbsp; `TensorFlow`

End-to-end SER pipeline trained on **10,000+ audio samples** across RAVDESS, CREMA-D, and TESS. Unified training pipeline with feature extraction, normalization, augmentation, and dataset harmonization.

| Architecture | Accuracy | Notes |
|---|---|---|
| SVM | 73% | Baseline |
| BiLSTM | 82% | Sequential context |
| **CNN** | **95% ✓** | **Optimal — best at 2D spectrogram pattern extraction** |

---

### 🟢 AETHER — Full-Stack Wellness App

> `Flutter` &nbsp;·&nbsp; `Firebase` &nbsp;·&nbsp; `Firestore` &nbsp;·&nbsp; `System Design`

Firestore backend with **8+ user-scoped collections** under a strict single-owner data model. Custom Firebase security rules enforcing per-user data isolation. Time-series journal schemas architected for future analytics pipelines.

**20+ async UI states** managed across 10+ network-bound screens — explicit error/loading/partial-render handling on every screen. No optimistic fallbacks. No shortcuts.

> 🏆 **Top 100 University Projects — Bennett University, 2025**

---

<div align="center">

## 🔬 Research

</div>

### Paraphrase-Robust Fake News Detection Using DL and Hybrid AI Models

> `NLP` &nbsp;·&nbsp; `ML` &nbsp;·&nbsp; `Deep Learning` &nbsp;·&nbsp; `Sentence Embeddings` &nbsp;·&nbsp; `Ensemble Models`

Built a paraphrase-aware detection pipeline across **190,000+ claims** and **33,294 unique paraphrase sets** — specifically designed to expose robustness failures in misinformation models under LLM-style paraphrased inputs.

```
Best Config: V5 — Weighted Lexical-Semantic Ensemble

  Accuracy              →  0.7648
  Precision             →  0.8219
  Recall                →  0.7709
  F1 Score              →  0.7956
  Prediction Consistency→  0.9328   ← stable across original & paraphrase
  Original-Para Agree   →  0.9375
```

Benchmarked: TF-IDF · MiniLM · MPNet · Logistic Regression · 5 model configurations

---

<div align="center">

## 🛠️ Tech Stack

</div>

<div align="center">

### Languages
<p>
<a href="https://www.python.org" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="42" height="42"/></a>&nbsp;&nbsp;
<a href="https://dart.dev" target="_blank"><img src="https://www.vectorlogo.zone/logos/dartlang/dartlang-icon.svg" alt="dart" width="42" height="42"/></a>&nbsp;&nbsp;
<a href="https://www.java.com" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="42" height="42"/></a>&nbsp;&nbsp;
<a href="https://www.w3schools.com/cpp/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="42" height="42"/></a>
</p>

### Mobile & Frontend
<p>
<a href="https://flutter.dev" target="_blank"><img src="https://www.vectorlogo.zone/logos/flutterio/flutterio-icon.svg" alt="flutter" width="42" height="42"/></a>&nbsp;&nbsp;
<a href="https://developer.android.com" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/android/android-original-wordmark.svg" alt="android" width="42" height="42"/></a>
</p>

### Backend & Databases
<p>
<a href="https://firebase.google.com/" target="_blank"><img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="firebase" width="42" height="42"/></a>&nbsp;&nbsp;
<a href="https://www.sqlite.org/" target="_blank"><img src="https://www.vectorlogo.zone/logos/sqlite/sqlite-icon.svg" alt="sqlite" width="42" height="42"/></a>&nbsp;&nbsp;
<a href="https://www.mongodb.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="42" height="42"/></a>&nbsp;&nbsp;
<a href="https://mariadb.org/" target="_blank"><img src="https://www.vectorlogo.zone/logos/mariadb/mariadb-icon.svg" alt="mariadb" width="42" height="42"/></a>
</p>

### ML & AI
<p>
<a href="https://pytorch.org/" target="_blank"><img src="https://www.vectorlogo.zone/logos/pytorch/pytorch-icon.svg" alt="pytorch" width="42" height="42"/></a>&nbsp;&nbsp;
<a href="https://www.tensorflow.org" target="_blank"><img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="tensorflow" width="42" height="42"/></a>&nbsp;&nbsp;
<a href="https://scikit-learn.org/" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit_learn" width="42" height="42"/></a>
</p>

### Tools & Environment
<p>
<a href="https://git-scm.com/" target="_blank"><img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="42" height="42"/></a>&nbsp;&nbsp;
<a href="https://www.linux.org/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="42" height="42"/></a>&nbsp;&nbsp;
<a href="https://heroku.com" target="_blank"><img src="https://www.vectorlogo.zone/logos/heroku/heroku-icon.svg" alt="heroku" width="42" height="42"/></a>&nbsp;&nbsp;
<a href="https://kotlinlang.org" target="_blank"><img src="https://www.vectorlogo.zone/logos/kotlinlang/kotlinlang-icon.svg" alt="kotlin" width="42" height="42"/></a>
</p>

</div>

---

<div align="center">

## 📊 GitHub Stats

<br/>

<img src="https://github-readme-stats.vercel.app/api/top-langs?username=aakash-kr-7&show_icons=true&locale=en&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=6366f1&text_color=c9d1d9" alt="Top Languages" />

<br/><br/>

<img src="https://github-readme-stats.vercel.app/api?username=aakash-kr-7&show_icons=true&locale=en&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=6366f1&text_color=c9d1d9&icon_color=6366f1" alt="GitHub Stats" />

<br/><br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=aakash-kr-7&theme=tokyonight&hide_border=true&background=0d1117&ring=6366f1&fire=6366f1&currStreakLabel=6366f1" alt="GitHub Streak" />

</div>

---

<div align="center">

## 🏅 Achievements

</div>

```
🎓  B.Tech CSE — Bennett University         CGPA: 9.19 / 10   SAT: 1530 / 1600
🔐  Certified Ethical Hacker (CEH)          EC-Council · Feb 2026 – Mar 2027
💻  350+ Problems Solved                    LeetCode + CodeChef (3★ Division 3)
🏆  Top 100 University Projects             Bennett University — Aether, 2025
```

---

<div align="center">

## 📡 Currently Exploring

</div>

```
▸  Scaling vector retrieval pipelines for long-horizon conversational memory
▸  Optimizing async concurrency patterns in high-throughput Python systems
▸  LLM engineering — prompt architecture, evaluation, and robustness testing
▸  Distributed system design for stateful AI applications
```

---

<div align="center">

## 🤝 Connect

**Open to collaborating on backend systems, data pipelines, or products that need serious infrastructure.**

[![LinkedIn](https://img.shields.io/badge/Let's_connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/aakash-kumar-978671274)
[![Email](https://img.shields.io/badge/Drop_a_mail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:aakashkumar94303@gmail.com)
[![Portfolio](https://img.shields.io/badge/See_my_work-0f0f0f?style=for-the-badge&logo=github&logoColor=white)](https://aakash-kr-7.github.io)

<br/>

*"The backend is where the real decisions live."*

<br/>

---

<sub>Built with precision · Deployed with intention · $0 operational cost and counting</sub>

</div>
