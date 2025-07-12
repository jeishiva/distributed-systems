# 📡 Distributed Systems Deep Dive — YouTube & Analytics Engine

As a **mobile engineer**, I’ve always been drawn to building seamless, performant user experiences. Over time, I found myself increasingly intrigued by the systems powering those experiences — particularly how large-scale distributed systems handle complexity, reliability, and scale.

This curiosity led me to invest significant time in understanding and analyzing such systems from the ground up. I chose two real-world, complex platforms to explore and explain my learnings through detailed breakdowns:

---

## 📺 Project 1: Designing YouTube

This project explores how a video streaming platform like YouTube can be architected to handle content at massive scale — uploads, encoding, delivery, recommendations, and more.

### 📘 Articles:

- 🔗 [System Design | YouTube | API & Resource Estimation](https://medium.com/@s.sivaguru11/system-design-youtube-part-1-7db0ae89c95b)  
  Covers the key features of YouTube, breaks down the API design and storage strategy, and includes resource estimation for video uploads and streaming scale.

- 🔗 [YouTube Architecture Visual Post](https://medium.com/me/stats/post/5fdd47b4de25)  
  Presents the high-level architecture diagram for the system. Useful for understanding how different subsystems interact in the design.

### 🧠 Highlights:
- Component-wise architecture with scalability, reliability, and fault tolerance in mind
- API design with clear usage boundaries
- Estimations on video storage (raw + transcoded), thumbnail generation, and CDN bandwidth
- Security and consistency considerations for user uploads and playback

---

## 📊 Project 2: Real-Time + Batch Analytics Engine

This project focuses on building a robust analytics platform that can process both real-time events and batch data — similar to systems used for product analytics or operational monitoring.

### 📘 Articles:

- 🔗 [System Design | Analytics Engine | High-Level Architecture](https://medium.com/@s.sivaguru11/system-design-analytics-engine-78e3e5cc517d)  
  Introduces the full architecture for hybrid analytics, including ingestion layers, stream processors, and long-term storage with high availability and security.

- 🔗 [System Design | Analytics Engine | API & Resource Estimation](https://medium.com/@s.sivaguru11/system-design-analytics-engine-api-resource-estimation-fc50e55fe8cf)  
  Deep-dives into API schema, real-time ingestion, buffering strategies, and resource estimation for scale: users, events, bandwidth, and storage.

### 🧠 Highlights:
- Event lifecycle from ingestion to query: WebSocket, Kafka, Flink/Spark, OLAP databases
- Resource planning for 10M+ daily active users and billions of events
- Emphasis on fault tolerance, retries, replay, deduplication, and exactly-once semantics
- Security and encryption (JWT, TLS, AES) baked into design
- Consideration of latency vs throughput trade-offs

---

## 🛠️ What Sets These Projects Apart

- 📌 **Visual-first** architecture breakdowns and flow diagrams
- 📊 **Detailed resource estimation** based on real-world usage patterns
- 🚀 Clear rationale behind every tech and design decision
- 🧱 Focus on **reliability, scalability, and resilience**
- 🔐 Security and compliance embedded into the core system architecture

---

## 👨‍💻 Who Is This For?

- Engineers preparing for **system design interviews**
- Mobile/backend engineers curious about **distributed systems**
- Engineering leaders looking for **architecture deep-dives**

---

## 📬 Let’s Connect

If you find these projects interesting or have feedback, feel free to reach out or connect on [LinkedIn](https://www.linkedin.com/in/azhagarasan-shiva-39361557/) or [Medium](https://medium.com/@s.sivaguru11).

---
