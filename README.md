<h1 align="center">Hi, I'm Ridhvi Kulshrestha 👋</h1>

<p align="center">
  <strong>Backend Developer · Java & Spring Boot · Electronic Trading Systems · Distributed Systems</strong>
</p>

<p align="center">
  <a href="mailto:ridhvikul07@gmail.com"><img src="https://img.shields.io/badge/Email-ridhvikul07%40gmail.com-blue?style=flat-square&logo=gmail&logoColor=white" /></a>
  <a href="https://linkedin.com/in/ridhvi-kulshrestha"><img src="https://img.shields.io/badge/LinkedIn-Ridhvi%20Kulshrestha-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/Location-Jaipur%2C%20India-orange?style=flat-square&logo=googlemaps&logoColor=white" />
  <img src="https://img.shields.io/badge/Open%20to-New%20Opportunities-brightgreen?style=flat-square" />
</p>

---

## About Me

I'm a backend developer with **2.5+ years** of production experience building **low-latency trading systems** and **distributed backend infrastructure** at [Nirvana Solutions India Pvt Ltd](https://nirvanasolutions.co/).

My core expertise is in **Java** and **C#**, with deep hands-on experience in **FIX Protocol (4.2/4.4)**, **QuickFIX/J**, **Spring Boot**, and **Apache Kafka**. I design systems where correctness, concurrency, and throughput matter — order routing engines, execution handlers, and real-time data pipelines.

I hold a **B.Tech (Hons) in Computer Science** from Poornima College of Engineering (CGPA: 9.3/10) and was a **Google Developer Student Club (GDSC) Lead**, running technical workshops for 600+ members.

---

## 🛠 Tech Stack

**Languages**

![Java](https://img.shields.io/badge/Java%208%2F11%2F17-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Backend Frameworks & Architecture**

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Cloud](https://img.shields.io/badge/Spring%20Cloud-6DB33F?style=flat-square&logo=spring&logoColor=white)
![.NET Core](https://img.shields.io/badge/.NET%20Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=flat-square&logo=hibernate&logoColor=white)
![Microservices](https://img.shields.io/badge/Microservices-Architecture-informational?style=flat-square)

**Messaging & Protocols**

![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![FIX Protocol](https://img.shields.io/badge/FIX%20Protocol-4.4-blueviolet?style=flat-square)
![QuickFIX/J](https://img.shields.io/badge/QuickFIX%2FJ-Order%20Routing-blueviolet?style=flat-square)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socket.io&logoColor=white)

**Databases & Tools**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**Domain Expertise**

![Electronic Trading](https://img.shields.io/badge/Electronic%20Trading%20Systems-0d1117?style=flat-square)
![Low Latency](https://img.shields.io/badge/Low--Latency%20Applications-0d1117?style=flat-square)
![Distributed Systems](https://img.shields.io/badge/Distributed%20Systems-0d1117?style=flat-square)
![System Design](https://img.shields.io/badge/System%20Design-0d1117?style=flat-square)

---

## 🚀 Featured Projects

### 🔀 FIX Protocol Trading Simulator
> **Java · Spring Boot · QuickFIX/J · REST API · Docker**

A self-contained FIX 4.4 trading simulator built with QuickFIX/J and Spring Boot. Implements a mock exchange acceptor, in-memory order book, and REST API for order lifecycle management (place, cancel, query). Containerized with Docker Compose for zero-dependency local execution.

- FIX 4.4 initiator + acceptor with full session management
- REST endpoints for new order, cancel, and order status
- In-memory order repository with thread-safe order book operations
- Swagger/OpenAPI documentation for all endpoints

`Java 17` `Spring Boot 3` `QuickFIX/J` `Docker` `JUnit 5` `Maven`

---

### ⚡ Distributed Rate Limiter
> **Spring Boot · Redis · Spring AOP · System Design**

A production-grade distributed rate limiting library implementing Token Bucket and Sliding Window Log algorithms. Exposed as a custom `@RateLimited` Spring annotation using AOP — drop-in for any Spring Boot application.

- Two configurable algorithms: Token Bucket and Sliding Window
- Redis-backed distributed counter store (works across multiple instances)
- Custom annotation-based API via Spring AOP
- Load tested at 10,000 req/s with sub-2ms p99 latency

`Spring Boot 3` `Redis` `Spring AOP` `JUnit 5` `Docker Compose`

---

### 📦 Event-Driven Order Management System
> **Spring Boot · Apache Kafka · Spring Cloud · Microservices · Docker**

A 3-service event-driven order management system demonstrating asynchronous inter-service communication, API gateway routing, and circuit-breaker patterns.

- Services: `order-service`, `inventory-service`, `notification-service`
- Apache Kafka message bus with guaranteed delivery semantics
- Spring Cloud Gateway for API routing and cross-cutting concerns
- Resilience4j circuit breaker on all synchronous service calls
- Full Docker Compose setup (services + Kafka + PostgreSQL)

`Spring Boot 3` `Apache Kafka` `Spring Cloud Gateway` `Resilience4j` `PostgreSQL` `Docker Compose`

---

### ⚙️ Automated XML Engine
> **C# · .NET Core · Data Structures · File I/O**

A configuration-driven XML generation engine to automate complex data reporting workflows at Nirvana Solutions. Eliminated manual processing bottlenecks across multiple data pipelines.

- Configuration-driven template engine — zero code change for new report types
- Optimized file processing with custom data structure selection
- Achieved 30–40% reduction in execution time on large datasets

`C#` `.NET Core` `File I/O` `Data Structures`

---

## 💼 Work Experience

**Backend Developer** · Nirvana Solutions India Pvt Ltd · *Jan 2023 – Present*

- Architected high-performance Java and C# trading services with **99.9% uptime** under heavy production load
- Engineered **FIX Protocol** order routing engines enabling low-latency transaction processing and high-throughput real-time data pipelines
- Designed RESTful APIs between core backend modules and front-end interfaces, reducing integration latency by **25%**
- Resolved complex multithreading and concurrency bugs via deep log analysis and profiling
- Refactored legacy codebases and SQL queries, cutting resource consumption by **~35%**

**Software Developer Intern** · Dept. of IT & Communication, Govt. of Rajasthan · *Jul 2022 – Dec 2022*

- Built REST API backend for the **iSTART** mobile application handling real-time startup data and funding workflows
- Managed PostgreSQL schemas and implemented secure server-side authentication

---

## 🏆 Achievements

| | |
|---|---|
| 🎓 **CGPA 9.3/10** | B.Tech (Hons) Computer Science — Poornima College of Engineering |
| 👨‍💻 **GDSC Lead** | Led technical workshops on DSA and backend system design for **600+ members** |
| 📜 **NPTEL Elite** | "Elite" certification in Introduction to Algorithms; certified in Java, C++, and C |
| 🏅 **Technovation Prize** | Research paper award — Distributed Systems and Low-Latency Backend Architectures |

---

📊 GitHub Stats
<p align="center">
  <img src="https://streak-stats.demolab.com?user=RIDHVI07&theme=default&hide_border=true&date_format=M%20j%5B%2C%20Y%5D" height="160" />
</p>
<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=RIDHVI07&theme=default" width="100%" />
</p>

---

## 📫 Let's Connect

I'm actively looking for **backend engineering roles** in fintech, distributed systems, and high-performance Java/Spring Boot environments.

- 📧 **ridhvikul07@gmail.com**
- 💼 **[LinkedIn](https://linkedin.com/in/ridhvi-kulshrestha)**
- 📍 **Jaipur, Rajasthan, India** · Open to remote and relocation

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=RIDHVI07&label=Profile%20Views&color=0e75b6&style=flat-square" />
</p>
