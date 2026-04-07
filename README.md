# Hi, I'm Ravi Rajpurohit 👋

Senior Backend Engineer with 8+ years of experience building scalable systems, data platforms, and graph-based architectures.

🔧 Java | Spring Boot | GraphQL | Neo4j  
🏢 Morgan Stanley  
🌱 Exploring Offline AI Systems  

![Profile Views](https://komarev.com/ghpvc/?username=RaviRajpurohit&color=blue)
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=RaviRajpurohit&show_icons=true)

---

## 🚀 What I Do

- Design scalable backend systems using Java & Spring Boot  
- Build GraphQL-based data aggregation platforms across multiple data sources  
- Work with graph databases (Neo4j) for complex relationship modeling  
- Develop microservices and event-driven systems  
- Optimize backend performance and large-scale data processing  

---

## 🧠 How I Think About Systems

I focus on designing systems that are:

- **Scalable** → Handle increasing data and traffic efficiently  
- **Composable** → Modular services that evolve independently  
- **Data-centric** → Choosing the right storage (Graph vs Relational vs NoSQL)  
- **Efficient** → Minimizing redundant calls and optimizing query paths  

> "The right data model reduces system complexity more than any optimization."

---

## ⚙️ Design Principles I Follow

- Prefer **data aggregation layers** over scattered client calls  
- Use **GraphQL** to reduce over-fetching and under-fetching  
- Apply **event-driven architecture** for decoupled systems  
- Optimize systems at **data access level, not just code level**  

---

## 💼 Experience

### 🏢 Morgan Stanley (Mar 2023 – Present)
- Contributing to a graph-based platform for analyzing application dependencies and security patterns at scale  
- Designing backend services integrating multiple data sources (Stardog, Snowflake, PostgreSQL)  
- Building data aggregation pipelines for complex relationship analysis  

### 🏢 Publicis Sapient (Sep 2021 – Mar 2023)
- Built fintech systems for fund & investment management  
- Worked as contractor supporting Wellington  
- Developed backend services using Java, Python, AWS  

### 🏢 Confluxsys (Jun 2017 – Sep 2021)
- Led backend for Identity & Access Management systems  
- Built GraphQL aggregation services across multiple databases  
- Designed microservices and workflow-driven systems  

---
## Architecture Dsign 
```
Client
  ↓
GraphQL API
  ↓
Resolver Layer
  ↓
-------------------------------
| Neo4j | PostgreSQL | Oracle |
-------------------------------
  ↓
Aggregation Layer
  ↓
Unified Response
```
---

## 🧩 System Design Experience

### 🔹 GraphQL Data Aggregation Platform

Designed a backend service that aggregates data from multiple heterogeneous data sources (Neo4j, PostgreSQL, Oracle, Cassandra) into a unified GraphQL API.

**Key Highlights:**
- Unified abstraction layer for multi-database querying  
- Reduced client-side complexity  
- Designed resolver strategies to minimize N+1 query problems and improve performance  

---

### 🔹 Identity & Access Governance System

Worked on backend systems for managing identity access, approvals, and governance workflows.

**Key Highlights:**
- Built REST APIs and workflow-driven systems  
- Implemented scheduler-based processing (Quartz)  
- Designed event-driven communication using ActiveMQ  

---

## 🔬 Deep Dive: Multi-Database Aggregation

### Problem:
- Data distributed across Graph + Relational DBs  
- Multiple API calls required  
- Increased latency and complexity  

### Solution:
- Introduced GraphQL-based aggregation layer  
- Centralized data fetching logic  
- Optimized resolver execution  

### Result:
- Simplified client interaction  
- Reduced redundant calls  
- Improved maintainability  

---

## ⚙️ Tech Stack

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql)
![Neo4j](https://img.shields.io/badge/Neo4j-018BFF?style=for-the-badge&logo=neo4j)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws)

---

## 📌 Notable Work

### 🔹 VSCode Google Search Extension
- Search directly from editor using shortcuts  
- Built using TypeScript  

### 🔹 Mini Sidenav (Angular)
- UI component with 50+ stars  
- Based on Angular Material  

### 🔹 CAZRI Inventory System
- Built during ISRO collaboration  
- PHP + MySQL based system  

---

## 🌱 Currently Exploring

- Offline AI systems  
- Efficient small language models  
- Privacy-first architectures  

---

## 📫 Connect With Me

- LinkedIn: https://linkedin.com/in/ravirajpurohit  
- Email: ravirajpurohit29@gmail.com  

---
## 🎯 What I'm Looking For

- Backend / Platform Engineering roles  
- Systems involving data, graphs, and distributed architectures  
- Opportunities to build scalable and impactful systems  
