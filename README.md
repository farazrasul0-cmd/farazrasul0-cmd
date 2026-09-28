<div align="center">

# MD Mayenaz Rasul Faraz
### Final-Year Software Engineering Undergraduate at Sichuan University
**Building Deterministic Sandboxed Runtimes, Distributed Systems & Developer Tooling**

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/md-mayenaz-rasul-faraz-24a6b518a)
[![Email](https://img.shields.io/badge/Email-farazrasul0%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:farazrasul0@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-farazrasul0--cmd-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/farazrasul0-cmd)

<br/>

</div>

---

### 👨‍💻 Engineering Profile

I am a Software Engineering undergraduate at **Sichuan University** focused on backend systems, cloud infrastructure, and low-level virtualization mechanisms. My projects center on engineering deterministic sandbox environments, static code analysis platforms with machine learning defect risk prediction, and scalable distributed architectures.

- 🎓 **Education:** Bachelor of Engineering in Software Engineering at Sichuan University (2022 – 2026).
- 💼 **Industry Experience:** Data Engineering Intern at **Chengdu Sundape Data Co., Ltd** (Received an official **"Excellent"** evaluation for B2B data modeling and visual analytics).
- 🛠️ **Current Engineering Focus:** Exploring Linux kernel isolation primitives (cgroups v2, Seccomp-BPF, unprivileged user namespaces) and container runtimes.
- 📬 **Direct Contact:** [farazrasul0@gmail.com](mailto:farazrasul0@gmail.com)

---

### 🛠️ Technical Stack & Tooling

<table>
  <tr>
    <td align="center" width="140"><strong>Languages</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
      <img src="https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white" />
      <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" />
      <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td align="center" width="140"><strong>Backend & Systems</strong></td>
    <td>
      <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
      <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
      <img src="https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white" />
      <img src="https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socketdotio&logoColor=white" />
      <img src="https://img.shields.io/badge/POSIX_PTY-333333?style=flat-square&logo=linux&logoColor=white" />
      <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td align="center" width="140"><strong>Cloud & Infrastructure</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
      <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" />
      <img src="https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white" />
      <img src="https://img.shields.io/badge/Linux_cgroups_v2-FCC624?style=flat-square&logo=linux&logoColor=black" />
      <img src="https://img.shields.io/badge/Seccomp--BPF-232F3E?style=flat-square&logo=linux&logoColor=white" />
      <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td align="center" width="140"><strong>Databases & Storage</strong></td>
    <td>
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
      <img src="https://img.shields.io/badge/Row--Level_Security-008080?style=flat-square" />
      <img src="https://img.shields.io/badge/Redis_Cache-DC382D?style=flat-square&logo=redis&logoColor=white" />
      <img src="https://img.shields.io/badge/SQLite_WAL-003B57?style=flat-square&logo=sqlite&logoColor=white" />
    </td>
  </tr>
</table>

---

### 🏛️ Flagship Architectural Systems

#### 1. [Secure Real-Time Remote Code Execution Platform](https://github.com/farazrasul0-cmd/secure-remote-code-execution-lab)
> **Multi-Tenant Sandboxed Execution Engine with Low-Latency PTY Terminal Streaming**
- Engineered a concentric 6-layer security perimeter combining Linux cgroups v2 resource quotas, unprivileged user namespaces, read-only rootfs, and Seccomp-BPF filters blocking ~350 syscalls.
- Integrated POSIX pseudo-terminal (`pty.openpty()`) allocation with WebSockets, Celery FIFO job queues, and Redis Pub/Sub for sub-5ms cold startup times and real-time streaming.
- Built a cloud-native Kubernetes deployment with PodSecurityStandards Restricted and queue-depth HPA autoscaling.

#### 2. [CodeSentinel: Code Quality & Defect Risk Analysis](https://github.com/farazrasul0-cmd/CodeSentinel-AI)
> **Static AST Security Scanning & ML-Driven Defect Prediction Engine**
- Developed a deterministic AST analysis platform catching critical security flaws (SQL injection CWE-89, command execution CWE-78, unsafe deserialization CWE-502).
- Integrated Random Forest + TreeSHAP explainability to quantify module-level defect risk and prioritize engineering review efforts.
- Computed dependency graph coupling using Tarjan's Strongly Connected Components algorithm and exported OASIS SARIF v2.1.0 scan results for CI/CD pipelines.

#### 3. [RAGBench: RAG Evaluation Laboratory](https://github.com/farazrasul0-cmd/RAGBench-Evaluation-Lab)
> **Parameterizable Scientific Benchmarking Platform for Retrieval-Augmented Generation**
- Engineered an evaluation laboratory treating RAG pipelines as parameterizable scientific experiments across chunking strategies, embeddings, and neural rerankers.
- Formalized quantitative Information Retrieval metrics to benchmark recall, precision, and hallucination reduction across diverse corpora.

#### 4. [EduOS: Multi-Tenant Institutional Management SaaS](https://github.com/farazrasul0-cmd/EduOS)
> **Bilingual Multi-Tenant School Administration Platform**
- Architected enterprise multi-tenancy with strict PostgreSQL Row-Level Security (RLS) data isolation.
- Implemented real-time financial ledger tracking, algorithmic exam tabulation grading engines, and dynamic vector PDF broadsheet rendering.

---

### 📊 GitHub Activity & Metrics

<div align="center">
  <img height="165em" src="https://github-readme-stats.vercel.app/api?username=farazrasul0-cmd&show_icons=true&theme=radical&include_all_commits=true&count_private=true" />
  <img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=farazrasul0-cmd&layout=compact&theme=radical&langs_count=6" />
</div>

<br/>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=farazrasul0-cmd&theme=radical&hide_border=false" />
</div>

---

<div align="center">

**Connect with me:** [LinkedIn](https://www.linkedin.com/in/md-mayenaz-rasul-faraz-24a6b518a) • [Email](mailto:farazrasul0@gmail.com) • [GitHub](https://github.com/farazrasul0-cmd)

</div>
