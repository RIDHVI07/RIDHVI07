<h1 align="center">Hi, I'm Ridhvi Kulshrestha 👋</h1>

<p align="center">
  <strong>Java &amp; C# Backend Engineer · Electronic Trading Systems · FIX Protocol · AI/RAG</strong>
</p>

<p align="center">
  <a href="mailto:ridhvikul07@gmail.com"><img src="https://img.shields.io/badge/Email-ridhvikul07%40gmail.com-blue?style=flat-square&logo=gmail&logoColor=white" /></a>
  <a href="https://linkedin.com/in/ridhvi-kulshrestha"><img src="https://img.shields.io/badge/LinkedIn-Ridhvi%20Kulshrestha-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/Location-Jaipur%2C%20India-orange?style=flat-square&logo=googlemaps&logoColor=white" />
  <img src="https://img.shields.io/badge/Open%20to-New%20Opportunities-brightgreen?style=flat-square" />
</p>

---

## About Me

I'm a backend engineer with **3+ years** of production experience building **low-latency trading systems** at [Nirvana Solutions](https://nirvanasolutions.co/), working in **Java** and **C#**.

Day to day I work on the parts of a trading stack where correctness and concurrency actually matter — **FIX Protocol** order routing engines, execution report handlers, **ATDL**-driven order entry, and real-time data pipelines. A lot of my time goes into production debugging: tracing multithreading and concurrency defects in live environments through log analysis and profiling.

Outside of work I build in the same domain. My projects pair **FIX/trading systems** with **Retrieval-Augmented Generation** — including a local RAG engine with a FIX log analyzer, and a full FIX 4.4 exchange simulator.

**B.Tech (Hons) Computer Science**, Poornima College of Engineering — CGPA 9.3/10. Former **Google Developer Student Club Lead** (600+ members).

---

## 🛠 Tech Stack

**Languages**

![Java](https://img.shields.io/badge/Java%2017%20%2F%2021-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)


**Backend & Frameworks**

![Spring Boot](https://img.shields.io/badge/Spring%20Boot%203-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Data JPA](https://img.shields.io/badge/Spring%20Data%20JPA-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate%206-59666C?style=flat-square&logo=hibernate&logoColor=white)
![.NET Core](https://img.shields.io/badge/.NET%20Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST%20APIs-informational?style=flat-square)

**Trading Technology**

![FIX Protocol](https://img.shields.io/badge/FIX%20Protocol-4.4-blueviolet?style=flat-square)
![QuickFIX/J](https://img.shields.io/badge/QuickFIX%2FJ-Order%20Routing-blueviolet?style=flat-square)
![ATDL](https://img.shields.io/badge/ATDL-Order%20Entry-blueviolet?style=flat-square)
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socket.io&logoColor=white)

**AI & GenAI**

![RAG](https://img.shields.io/badge/RAG-Retrieval%20Augmented%20Generation-8A2BE2?style=flat-square)
![Vector Search](https://img.shields.io/badge/Embeddings%20%26%20Vector%20Search-8A2BE2?style=flat-square)
![Gemini](https://img.shields.io/badge/Google%20Gemini%20API-4285F4?style=flat-square&logo=googlegemini&logoColor=white)
![AI Assisted Dev](https://img.shields.io/badge/AI--Assisted%20Dev-Claude%20%2F%20ChatGPT-8A2BE2?style=flat-square)

**Databases, Testing & Tools**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**Domain**

![Electronic Trading](https://img.shields.io/badge/Electronic%20Trading%20Systems-0d1117?style=flat-square)
![Low Latency](https://img.shields.io/badge/Low--Latency%20Applications-0d1117?style=flat-square)
![Distributed Systems](https://img.shields.io/badge/Distributed%20Systems-0d1117?style=flat-square)
![Event Driven](https://img.shields.io/badge/Event--Driven%20Architecture-0d1117?style=flat-square)

---

## 🚀 Featured Projects

### 🔍 [TradeLens AI](https://github.com/RIDHVI07/Tradelens-AI-Project) — FIX Log Analysis + Local RAG
> **Java 21 · Spring Boot 3 · RAG · React 18 · Google Gemini**

An AI investigation workspace that combines document intelligence with FIX protocol analysis. Runs entirely locally — no Docker, no Kubernetes, no external vector database.

- **FIX Log Analyzer** — parses trading logs and detects anomalies including rejects, sequence gaps and duplicate orders, feeding timeline generation and root-cause analysis
- **Local RAG engine** — document parsing → chunking → offline embeddings → in-database vector storage → semantic retrieval with source citations
- Document ingestion via **PDFBox** and **Apache POI**; optional **Google Gemini** integration
- 12 modules spanning knowledge base, trading investigation, timeline exploration, report generation and dashboards
- **React 18 + Vite + Tailwind** frontend with Recharts analytics

`Java 21` `Spring Boot 3` `Spring Data JPA` `H2 / PostgreSQL` `React 18`

---

### 🔀 [FIX Trading Simulator](https://github.com/RIDHVI07/Fix-Trading-Simulator) — FIX 4.4 Order Lifecycle
> **Java 17 · Spring Boot 3 · QuickFIX/J · Docker**

A self-contained FIX 4.4 trading simulator. Pairs a FIX initiator with an in-process mock exchange acceptor, so complete order lifecycles can be exercised with zero external venue connectivity.

- FIX 4.4 **initiator + acceptor** with full session management, logon/logout and heartbeats
- **NewOrderSingle**, **OrderCancelRequest** and asynchronous **ExecutionReport** handling (NEW → FILLED)
- Thread-safe in-memory order book with dual indexing on `orderId` and FIX `ClOrdID`
- REST API for place / cancel / query, fully documented with **Swagger/OpenAPI**
- Multi-stage **Docker** build — one `docker-compose up` to run, no Java install required
- Tested with **JUnit 5, Mockito and MockMvc** across repository, service and controller layers

`Java 17` `Spring Boot 3` `QuickFIX/J` `FIX 4.4`  `JUnit 5` `Maven`

---

### 📦 [CommerceFlow](https://github.com/RIDHVI07/CommerceFlow-Application) — Event-Driven Commerce Platform
> **Java 21 · Spring Boot 3.5 · MySQL 8 · Spring Security**

An event-driven e-commerce platform with separate customer and admin surfaces. Checkout stays responsive by pushing side effects off the request path.

- Placing an order publishes an **`OrderPlacedEvent`** consumed independently by three listeners — inventory decrement with low-stock flagging, in-app notification, and audit logging — on a dedicated **`ThreadPoolTaskExecutor`** rather than blocking checkout
- **Spring Security 6** with JWT (jjwt) and BCrypt password hashing
- Layered architecture — controller → service → repository → entity — with **12 JPA entities, 11 repositories and 8 domain events**
- Customer routes for cart and order history; admin routes for inventory, dashboards and audit trails
- **JUnit 5 + Mockito + H2** test suite

`Java 21` `Spring Boot 3.5` `Spring Data JPA` `Hibernate 6` `MySQL 8` `Spring Security` `JWT` `Thymeleaf` `JUnit 5`

---

## 💼 Work Experience

**Backend Developer** · Nirvana Solutions India Pvt Ltd · *Jan 2023 – Present*

- Delivered production backend trading services in **Java** and **C#**, sustaining **99.9% uptime** for order and execution workflows under heavy load
- Engineered **FIX Protocol** order routing engines, execution report handlers and **ATDL**-driven order entry for venue-specific algorithmic parameters
- Designed **RESTful APIs** between core backend modules and front-end interfaces, cutting integration latency by **25%**
- Diagnosed and resolved complex **multithreading and concurrency** defects in live trading environments through log analysis and profiling
- Refactored legacy codebases and optimized **SQL** queries, reducing resource consumption by **~35%**
- Built a configuration-driven **XML generation engine** in C#/.NET Core for automated reporting, cutting execution time **30–40%** on large datasets

**Software Developer Intern** · Dept. of IT &amp; Communication, Govt. of Rajasthan · *Jul 2022 – Dec 2022*

- Built the **iSTART** mobile application backend with **REST APIs** and **PostgreSQL**, implementing secure server-side authentication and schema design

---

## 🏆 Achievements

| | |
|---|---|
| 🎓 **CGPA 9.3/10** | B.Tech (Hons) Computer Science — Poornima College of Engineering |
| 👨‍💻 **GDSC Lead** | Led technical workshops on DSA and backend system design for **600+ members** |
| 📜 **NPTEL Elite** | "Elite" certification in Introduction to Algorithms; certified in Java, C++ and C |

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://streak-stats.demolab.com?user=RIDHVI07&theme=default&hide_border=true&date_format=M%20j%5B%2C%20Y%5D" height="160" />
</p>
<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=RIDHVI07&theme=default" width="100%" />
</p>

---

## 📫 Let's Connect

I'm actively looking for **backend engineering roles** in fintech, electronic trading and high-performance Java/Spring Boot environments.

- 📧 **ridhvikul07@gmail.com**
- 💼 **[LinkedIn](https://linkedin.com/in/ridhvi-kulshrestha)**
- 📍 **Jaipur, Rajasthan, India** · Open to remote and relocation

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=RIDHVI07&label=Profile%20Views&color=0e75b6&style=flat-square" />
</p>
