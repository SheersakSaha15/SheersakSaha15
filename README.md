<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=6A0DAD&height=200&section=header&text=&animation=fadeIn" width="100%" />

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=32&pause=1000&color=A855F7&center=true&vCenter=true&width=900&lines=Senior+Software+Engineer;AI+%2F+ML+Engineer;Full+Stack+Architect;Product+Engineer+%7C+Builder+%7C+Creator)](https://git.io/typing-svg)

<br/>

![B.Tech CSE](https://img.shields.io/badge/B.Tech-Computer_Science_%26_Engineering-7C3AED?style=flat-square&logo=graduation-cap&logoColor=white)
![Specialization](https://img.shields.io/badge/Specialization-AI_%26_Machine_Learning-6D28D9?style=flat-square&logo=brain&logoColor=white)
![Location](https://img.shields.io/badge/India-Software_Engineer-4C1D95?style=flat-square&logo=googlemaps&logoColor=white)

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-yourportfolio.dev-7C3AED?style=for-the-badge&logo=vercel&logoColor=white)](https://yourportfolio.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-6D28D9?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/yourusername)
[![Email](https://img.shields.io/badge/Email-Contact_Me-5B21B6?style=for-the-badge&logo=gmail&logoColor=white)](mailto:you@email.com)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-4C1D95?style=for-the-badge&logo=github&logoColor=white)](https://github.com/yourusername)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=yourusername&color=7C3AED&style=flat-square&label=Profile+Views)
![GitHub Followers](https://img.shields.io/github/followers/yourusername?color=6D28D9&style=flat-square&logo=github&label=Followers)
![GitHub Stars](https://img.shields.io/github/stars/yourusername?color=5B21B6&style=flat-square&logo=github&label=Total+Stars)

</div>

---

## About

I am a Senior Software Engineer with deep expertise in building scalable, production-grade systems at the intersection of AI, full-stack development, and product engineering. With a foundation in Computer Science and a specialization in Artificial Intelligence and Machine Learning, I architect solutions that bridge research and real-world impact.

My engineering philosophy is rooted in systems thinking — designing software that is not only functionally correct but resilient, observable, and built to scale. I have shipped end-to-end products across distributed backend services, intelligent data pipelines, and modern frontend experiences, with a strong emphasis on developer experience and operational excellence.

I approach every problem as a product engineer first: deeply understanding user needs, defining measurable outcomes, and delivering with precision. I have hands-on experience across the full delivery lifecycle — from architecture design and API development to ML model deployment, CI/CD automation, and production monitoring.

**Open To:** Senior Software Engineer · AI/ML Engineer · Full Stack Engineer · Platform Engineer · Technical Lead · Remote-first roles

---

## Tech Stack

<div align="center">

**Languages**

[![Languages](https://skillicons.dev/icons?i=python,typescript,javascript,java,cpp,go,bash,sql&theme=dark)](https://skillicons.dev)

**Frontend**

[![Frontend](https://skillicons.dev/icons?i=react,nextjs,tailwind,redux,html,css,figma,vercel&theme=dark)](https://skillicons.dev)

**Backend & Databases**

[![Backend](https://skillicons.dev/icons?i=nodejs,fastapi,django,flask,express,postgresql,mongodb,redis&theme=dark)](https://skillicons.dev)

**Cloud, DevOps & Tooling**

[![DevOps](https://skillicons.dev/icons?i=aws,gcp,docker,kubernetes,terraform,github,githubactions,linux&theme=dark)](https://skillicons.dev)

</div>

---

## AI / ML Expertise

<div align="center">

| Domain | Proficiency | Details |
|--------|-------------|---------|
| Large Language Models | ████████████ Expert | Fine-tuning, RAG pipelines, prompt engineering, LangChain, LlamaIndex |
| Deep Learning | ███████████░ Advanced | CNNs, RNNs, Transformers, PyTorch, TensorFlow, Keras |
| MLOps & Model Deployment | ███████████░ Advanced | MLflow, BentoML, FastAPI serving, model versioning, A/B testing |
| Natural Language Processing | ████████████ Expert | Tokenization, embeddings, semantic search, classification, summarization |
| Computer Vision | █████████░░░ Proficient | Object detection, image segmentation, OpenCV, YOLO, CLIP |
| Reinforcement Learning | ████████░░░░ Intermediate | Q-Learning, PPO, policy gradients, OpenAI Gym |
| Data Engineering | ███████████░ Advanced | Spark, Airflow, dbt, Kafka, feature stores, ETL pipelines |
| Vector Databases | ████████████ Expert | Pinecone, Weaviate, ChromaDB, FAISS, pgvector |

</div>

---

## Featured Projects

<details>
<summary><strong>⬡ &nbsp;IntelliSearch — Enterprise Semantic Search Platform</strong></summary>

<br/>

A production-grade semantic search engine built for enterprise document retrieval, powered by a hybrid dense-sparse retrieval architecture and a fine-tuned embedding model. Designed to serve high-concurrency query workloads with sub-100ms P99 latency at scale.

| Attribute | Detail |
|-----------|--------|
| **Stack** | Python · FastAPI · LangChain · PostgreSQL (pgvector) · Redis · React · TypeScript · Docker · AWS ECS |
| **Scale** | 10M+ documents indexed · 50K+ daily active queries · Multi-tenant SaaS |
| **Performance** | P99 latency < 95ms · 99.95% uptime · Horizontal autoscaling via ECS |
| **Security** | JWT + RBAC auth · Encrypted at rest and in transit · SOC 2 aligned |
| **Impact** | Reduced document retrieval time by 78% · Adopted by 3 enterprise pilot clients |
| **Repository** | [![GitHub](https://img.shields.io/badge/View_Repo-6D28D9?style=flat-square&logo=github&logoColor=white)](https://github.com/yourusername/intellisearch) |

The platform ingests documents via an async pipeline, chunks and embeds content using a fine-tuned sentence transformer, and stores vectors in pgvector with metadata filtering support. The query layer combines BM25 keyword ranking with dense vector similarity, re-ranked by a cross-encoder model. A Redis layer caches hot queries, and the entire stack is deployed on AWS ECS with blue-green deployments managed through GitHub Actions.

<br/>

</details>

<details>
<summary><strong>⬡ &nbsp;Nexus — AI-Powered Full Stack SaaS Boilerplate</strong></summary>

<br/>

An opinionated, production-ready SaaS starter kit that compresses weeks of boilerplate work into a single deployable monorepo. Designed to be the foundation for AI-first products, with built-in authentication, billing, AI capabilities, and observability out of the box.

| Attribute | Detail |
|-----------|--------|
| **Stack** | Next.js 14 · TypeScript · Prisma · PostgreSQL · Stripe · OpenAI API · Vercel · Tailwind CSS |
| **Scale** | Multi-tenant · Role-based access · Usage-based billing |
| **Performance** | Lighthouse score 98 · Edge-rendered pages · CDN-optimized assets |
| **Security** | NextAuth.js · CSRF protection · Rate limiting · Input sanitization |
| **Impact** | 300+ GitHub stars · Used as a foundation by 50+ indie developers |
| **Repository** | [![GitHub](https://img.shields.io/badge/View_Repo-6D28D9?style=flat-square&logo=github&logoColor=white)](https://github.com/yourusername/nexus-saas) |

Nexus abstracts authentication (email, OAuth, magic links), Stripe subscription management (free tier, pro, enterprise), an AI chat interface powered by the OpenAI API with streaming, an admin dashboard, and a comprehensive component library. The codebase is typed end-to-end, covered by integration tests, and ships with a CI/CD pipeline ready to connect to any deployment target.

<br/>

</details>

<details>
<summary><strong>⬡ &nbsp;Sentinel — Distributed Observability & Anomaly Detection System</strong></summary>

<br/>

A real-time distributed tracing and anomaly detection platform that ingests application metrics and logs, runs an LSTM-based anomaly detection model on streaming data, and surfaces actionable alerts to engineering teams through a customizable dashboard.

| Attribute | Detail |
|-----------|--------|
| **Stack** | Python · Apache Kafka · Apache Flink · InfluxDB · Grafana · PyTorch · FastAPI · React |
| **Scale** | 500K+ events/sec ingestion · Sub-5s anomaly alert latency · Multi-service tracing |
| **Performance** | LSTM model F1 score 0.94 · < 2% false positive rate · 99.9% pipeline uptime |
| **Security** | mTLS between services · Encrypted Kafka topics · Audit logging |
| **Impact** | Detected 3 major production incidents before user impact in internal trials |
| **Repository** | [![GitHub](https://img.shields.io/badge/View_Repo-6D28D9?style=flat-square&logo=github&logoColor=white)](https://github.com/yourusername/sentinel) |

Sentinel ingests OpenTelemetry traces and custom metrics via Kafka, processes streams through Flink jobs that compute rolling statistics, and feeds normalized feature vectors into a trained LSTM anomaly detection model served via FastAPI. Anomalies trigger webhook-based alerts to Slack and PagerDuty. Historical data is persisted in InfluxDB and visualized through a customized Grafana dashboard with per-service drill-down capabilities.

<br/>

</details>

<details>
<summary><strong>⬡ &nbsp;FormForge — AI-Driven Dynamic Form Builder</strong></summary>

<br/>

A no-code/low-code form creation platform with an embedded AI assistant that generates form schemas, validates logic, and suggests improvements in natural language. Built for product teams and operations workflows that require dynamic, conditional, and deeply customizable forms.

| Attribute | Detail |
|-----------|--------|
| **Stack** | React · Node.js · Express · MongoDB · OpenAI API · AWS Lambda · S3 · TypeScript |
| **Scale** | 10K+ forms created · 100K+ submissions processed · Webhook + REST export |
| **Performance** | AI schema generation < 3s · Form render < 400ms · Serverless cold start < 800ms |
| **Security** | Encrypted submissions · GDPR-compliant data export and deletion |
| **Impact** | Replaced a manual form-building process saving 6 hours/week per ops team member |
| **Repository** | [![GitHub](https://img.shields.io/badge/View_Repo-6D28D9?style=flat-square&logo=github&logoColor=white)](https://github.com/yourusername/formforge) |

The core product is a React-based drag-and-drop form builder with support for conditional logic, computed fields, file uploads, and multi-step flows. The AI assistant accepts natural language prompts and generates JSON form schemas via a fine-tuned OpenAI GPT-4 call. Submissions are stored in MongoDB, exportable to CSV/JSON, and triggerable via outbound webhooks. The backend is serverless, deployed on AWS Lambda with S3 file storage.

<br/>

</details>

---

## Experience

### Senior Software Engineer
**TechCorp Solutions Pvt. Ltd.** &nbsp;·&nbsp; *Jan 2023 – Present*

Led the design and delivery of a microservices-based platform serving 2M+ end users, owning architecture decisions from API design through to infrastructure provisioning. Worked closely with product and design teams to translate requirements into high-quality engineering deliverables, consistently shipping features ahead of schedule with zero critical production incidents.

- Architected a distributed event-driven backend on AWS ECS with Kafka as the messaging backbone, replacing a monolithic system and reducing deployment time by 60%
- Built and deployed a real-time ML inference pipeline serving personalized recommendations, improving user engagement metrics by 34%
- Established engineering best practices including code review standards, observability guidelines, and an internal design document framework adopted across 4 engineering squads
- Mentored 3 junior engineers, conducting weekly 1:1s and structured technical growth plans

![Python](https://img.shields.io/badge/Python-7C3AED?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-6D28D9?style=flat-square&logo=typescript&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-5B21B6?style=flat-square&logo=amazonaws&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-4C1D95?style=flat-square&logo=apachekafka&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-7C3AED?style=flat-square&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-6D28D9?style=flat-square&logo=postgresql&logoColor=white)

---

### Software Engineer — AI/ML
**DataSystems Analytics** &nbsp;·&nbsp; *Jun 2021 – Dec 2022*

Joined as the third engineer on the ML platform team and grew with the organization through a Series A funding round. Owned the end-to-end development of NLP features across the core product, from research and prototyping through to production deployment and monitoring.

- Developed a document classification pipeline using a fine-tuned BERT model, achieving 91% accuracy across 18 document categories
- Built a semantic search feature using dense retrieval and FAISS, reducing support ticket resolution time by 40%
- Implemented an MLflow-based experiment tracking and model registry system, standardizing the model lifecycle for the entire ML team
- Collaborated with the data engineering team to migrate batch ETL jobs to Airflow-orchestrated streaming pipelines

![Python](https://img.shields.io/badge/Python-7C3AED?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-6D28D9?style=flat-square&logo=pytorch&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-5B21B6?style=flat-square&logo=fastapi&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-4C1D95?style=flat-square&logo=mlflow&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-7C3AED?style=flat-square&logo=apacheairflow&logoColor=white)

---

### Software Engineering Intern
**CloudBase Technologies** &nbsp;·&nbsp; *May 2020 – Jul 2020*

Contributed to the backend services team during a 10-week internship, building REST APIs and improving test coverage across critical payment flow services.

- Developed 5 new REST API endpoints for the billing microservice using Node.js and Express
- Increased unit test coverage from 42% to 79% on the payments module, reducing regression risk
- Resolved 12 production bugs with documented root cause analyses

![Node.js](https://img.shields.io/badge/Node.js-7C3AED?style=flat-square&logo=nodedotjs&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-6D28D9?style=flat-square&logo=javascript&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-5B21B6?style=flat-square&logo=mongodb&logoColor=white)

---

## Achievements

<div align="center">

| Recognition | Details |
|-------------|---------|
| 🏆 Smart India Hackathon — Finalist | Top 20 nationally from 15,000+ participating teams across India |
| 🥇 University Rank 1 — CSE AI/ML | Graduated with the highest GPA in the AI/ML specialization cohort |
| 🌟 Open Source Contributor | 300+ GitHub stars across personal projects · 50+ pull requests merged in external repos |
| 📝 Technical Author | Published 12 long-form engineering articles with 25,000+ total reads |
| 🎤 Conference Speaker | Presented at regional developer meetup on LLM deployment patterns in production |
| 💡 Patent Pending | Co-inventor on a patent application for a novel document chunking algorithm |
| 🔑 Dean's List — 4 Semesters | Recognized for academic excellence throughout undergraduate program |

</div>

---

## Certifications

<div align="center">

**Amazon Web Services**

[![AWS Solutions Architect](https://img.shields.io/badge/AWS-Solutions_Architect_Associate-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)](https://aws.amazon.com/certification/)
[![AWS Developer](https://img.shields.io/badge/AWS-Developer_Associate-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)](https://aws.amazon.com/certification/)
[![AWS ML Specialty](https://img.shields.io/badge/AWS-Machine_Learning_Specialty-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)](https://aws.amazon.com/certification/)

<br/>

**Oracle**

[![Oracle Java SE](https://img.shields.io/badge/Oracle-Java_SE_11_Developer-F80000?style=for-the-badge&logo=oracle&logoColor=white)](https://education.oracle.com/certification)
[![Oracle Cloud](https://img.shields.io/badge/Oracle-Cloud_Infrastructure_Foundations-F80000?style=for-the-badge&logo=oracle&logoColor=white)](https://education.oracle.com/certification)

<br/>

**NPTEL**

[![NPTEL Python](https://img.shields.io/badge/NPTEL-Programming_in_Python_(Elite)-0077B5?style=for-the-badge&logo=coursera&logoColor=white)](https://nptel.ac.in/)
[![NPTEL ML](https://img.shields.io/badge/NPTEL-Machine_Learning_(Elite+Gold)-0077B5?style=for-the-badge&logo=coursera&logoColor=white)](https://nptel.ac.in/)
[![NPTEL DS](https://img.shields.io/badge/NPTEL-Data_Structures_%26_Algorithms-0077B5?style=for-the-badge&logo=coursera&logoColor=white)](https://nptel.ac.in/)

<br/>

**Cisco**

[![Cisco CCNA](https://img.shields.io/badge/Cisco-CCNA_Routing_%26_Switching-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)](https://www.cisco.com/c/en/us/training-events/training-certifications/certifications.html)
[![Cisco CyberOps](https://img.shields.io/badge/Cisco-CyberOps_Associate-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)](https://www.cisco.com/c/en/us/training-events/training-certifications/certifications.html)

</div>

---

## Coding Profiles

<div align="center">

[![LeetCode](https://img.shields.io/badge/LeetCode-1500%2B_Problems_Solved-FFA116?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/yourusername)
[![GeeksforGeeks](https://img.shields.io/badge/GeeksforGeeks-Institute_Rank_1-2F8D46?style=for-the-badge&logo=geeksforgeeks&logoColor=white)](https://www.geeksforgeeks.org/user/yourusername)
[![HackerRank](https://img.shields.io/badge/HackerRank-6_Star_Gold-2EC866?style=for-the-badge&logo=hackerrank&logoColor=white)](https://www.hackerrank.com/yourusername)
[![CodeChef](https://img.shields.io/badge/CodeChef-4_Star_Rated-5B4638?style=for-the-badge&logo=codechef&logoColor=white)](https://www.codechef.com/users/yourusername)

</div>

---

## GitHub Analytics

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=yourusername&show_icons=true&theme=midnight-purple&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D0D0D&title_color=A855F7&icon_color=7C3AED&text_color=C4B5FD" />
&nbsp;
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=yourusername&layout=compact&langs_count=8&theme=midnight-purple&hide_border=true&bg_color=0D0D0D&title_color=A855F7&text_color=C4B5FD" />

</div>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=yourusername&theme=midnight-purple&hide_border=true&background=0D0D0D&ring=A855F7&fire=7C3AED&currStreakLabel=C4B5FD&sideLabels=C4B5FD&currStreakNum=A855F7&sideNums=A855F7&dates=6D28D9" />

</div>

---

## GitHub Trophies

<div align="center">

[![GitHub Trophies](https://github-profile-trophy.vercel.app/?username=yourusername&theme=darkhub&no-frame=true&no-bg=true&margin-w=8&column=7&title_color=A855F7)](https://github.com/ryo-ma/github-profile-trophy)

</div>

---

## Contribution Activity

<div align="center">

[![GitHub Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=yourusername&bg_color=0D0D0D&color=A855F7&line=7C3AED&point=C4B5FD&area=true&area_color=4C1D95&hide_border=true)](https://github.com/ashutosh00710/github-readme-activity-graph)

</div>

---

## Contribution Snake

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/yourusername/yourusername/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/yourusername/yourusername/output/github-contribution-grid-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/yourusername/yourusername/output/github-contribution-grid-snake-dark.svg" />
</picture>

</div>

---

## Current Focus

```yaml
Current Focus — 2024:

  Learning:
    - Advanced RL techniques: PPO, GRPO, RLHF for LLM alignment
    - Distributed systems: consensus algorithms, CRDTs, Raft protocol
    - System design at hyperscale: sharding, consistent hashing, CDN architecture

  Building:
    - A production-grade multi-agent AI framework with tool use and memory
    - An open source developer observability toolkit for LLM applications
    - A personal knowledge management system powered by semantic search

  Exploring:
    - Multimodal foundation models and cross-modal retrieval
    - WebAssembly (WASM) for portable high-performance compute
    - Rust for systems programming and performance-critical services

  Open To:
    - Senior / Staff Software Engineer roles
    - AI/ML Engineering and MLOps Engineering opportunities
    - Technical leadership and principal engineering paths
    - Remote-first, globally distributed engineering teams
    - Open source collaboration and co-authorship
```

---

## Connect

<div align="center">

[![Gmail](https://img.shields.io/badge/Gmail-you%40email.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:you@email.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-yourprofile-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/yourusername)
[![GitHub](https://img.shields.io/badge/GitHub-yourusername-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/yourusername)
[![Portfolio](https://img.shields.io/badge/Portfolio-yourportfolio.dev-7C3AED?style=for-the-badge&logo=vercel&logoColor=white)](https://yourportfolio.dev)

</div>

---

<div align="center">

*"The best engineers are not those who know the most — they are those who build the right things with relentless clarity of purpose."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=6A0DAD&height=120&section=footer" width="100%" />

</div>
