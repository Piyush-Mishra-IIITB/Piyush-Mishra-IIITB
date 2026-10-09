

# Hi 👋 I'm Piyush Mishra

### AI / ML Engineer & Backend-Focused Full-Stack Developer

I build **production-oriented intelligent and distributed systems**,
combining AI/ML, backend engineering, realtime communication, and
scalable architectures.

Currently focused on **AI Engineering, Backend Systems, Distributed
Systems, and Realtime Architectures**.

------------------------------------------------------------------------

## 🚀 Engineering Profile

B.Tech student with hands-on experience building and deploying
**multi-service applications** involving:

-   Machine Learning inference
-   RAG-based AI systems
-   REST APIs & microservices
-   Distributed systems
-   Event-driven architectures
-   Realtime communication
-   Authentication & authorization
-   Payment workflows
-   Caching & distributed locking
-   Production debugging and failure handling

I work across the complete engineering lifecycle:

``` text
Data / Knowledge → AI / ML → Services → APIs → Realtime Systems → Infrastructure → Deployment
```

Strong fundamentals in **DSA with Java**, backend development, AI
engineering, and system design.

------------------------------------------------------------------------

## 🧠 Technical Expertise

### AI / Machine Learning

-   NLP classification systems
-   Recommendation systems
-   Retrieval-Augmented Generation (RAG)
-   Semantic search & knowledge retrieval
-   Feature engineering
-   Model evaluation & inference
-   ML model deployment with FastAPI
-   ML + backend service integration

### Backend Engineering

-   REST API design
-   Microservice architecture
-   JWT authentication & role-based authorization
-   MongoDB & SQL database modeling
-   Redis caching & distributed locking
-   RabbitMQ event-driven architecture
-   Transactional Outbox pattern
-   Idempotent event processing
-   Payment workflows & verification
-   API Gateway architecture

### Realtime Systems

-   Socket.IO
-   WebRTC
-   Realtime chat
-   Video consultation
-   WebRTC signaling
-   Realtime state synchronization

### Distributed Systems

-   Service-to-service communication
-   Event-driven architecture
-   Message queues
-   Retry mechanisms
-   Dead Letter Queues (DLQ)
-   Failure recovery
-   Distributed locks
-   Kubernetes & containerized services

------------------------------------------------------------------------

## 🛠 Tech Stack

**Languages**

Java • Python • JavaScript • SQL

**AI / ML**

NumPy • Pandas • Scikit-learn • TensorFlow • PyTorch • RAG

**Backend**

Node.js • Express.js • FastAPI • Flask

**Frontend**

React.js • Context API • Tailwind CSS

**Databases**

MongoDB • MySQL

**Distributed & Realtime Systems**

Redis • RabbitMQ • Socket.IO • WebRTC • REST APIs

**DevOps & Infrastructure**

Docker • Docker Compose • Kubernetes • Minikube • Git • Linux • AWS •
Render

------------------------------------------------------------------------

# 📌 Featured Projects

## 🍔 FoodMesh --- Distributed Food Delivery Platform

A backend-focused **distributed food delivery system** designed using
microservices and event-driven architecture principles.

The project focuses on building a reliable backend capable of handling
**service communication, caching, distributed locking, asynchronous
events, retries, idempotency, and failure recovery**.

### Architecture & Engineering Work

-   Designed a multi-service architecture for:
    -   User Service
    -   Restaurant Service
    -   Order Service
    -   Delivery Service
    -   Payment Service
    -   API Gateway
-   Implemented **API Gateway** for centralized routing and request
    handling
-   Added authentication and role-based authorization across services
-   Implemented **Redis caching** for frequently accessed restaurant
    data
-   Implemented **Redis distributed locking** for delivery-partner
    assignment
-   Integrated **RabbitMQ** for asynchronous event-driven communication
-   Implemented the **Transactional Outbox Pattern** for reliable event
    publishing
-   Added **idempotent event processing** to handle duplicate RabbitMQ
    deliveries
-   Implemented payment processing with:
    -   Retry mechanisms
    -   Bounded retries
    -   Dead Letter Queue (DLQ)
    -   DLQ recovery
-   Added request IDs and persistent gateway logging for observability
-   Implemented API rate limiting
-   Dockerized the complete system
-   Created Kubernetes / Minikube deployment manifests using Kustomize
-   k6 performance benchmark: Tested GET /api/restaurants through the API Gateway with 1 virtual user for 60 seconds; recorded 60/60 successful responses, 4.68 ms average latency, and 5.98 ms p95 latency in a local, low-load benchmark.


### Architecture

``` text
                         ┌─────────────────┐
                         │   API Gateway   │
                         │      :5000      │
                         └────────┬────────┘
                                  │
          ┌───────────────┬───────┼────────┬───────────────┐
          │               │       │        │               │
          ▼               ▼       ▼        ▼               ▼
     User Service   Restaurant  Order   Delivery       Payment
        :5001         :5002     :5003    :5004          :5005
          │               │       │        │               │
          └───────────────┴───────┴────────┴───────────────┘
                                  │
                    ┌─────────────┼─────────────┐
                    │             │             │
                    ▼             ▼             ▼
                 MongoDB        Redis       RabbitMQ
```

**Tech:** Node.js • Express.js • MongoDB • Redis • RabbitMQ • Docker •
Kubernetes • Minikube

📂 **Repository:** https://github.com/Piyush-Mishra-IIITB/FoodMesh

------------------------------------------------------------------------

## 🏥 Prescripto --- AI Tele-Consultation & Doctor Recommendation Platform

A production-style healthcare platform combining **AI-powered doctor
recommendation, Retrieval-Augmented Generation (RAG), realtime
communication, video consultation, payments, and multi-role backend
architecture**.

### Key Engineering Work

-   Built an **ML triage engine** that predicts the appropriate medical
    specialist from patient symptoms
-   Implemented a **RAG-based healthcare knowledge system** to retrieve
    relevant medical information and provide context-aware responses
-   Designed the RAG pipeline around **knowledge retrieval + contextual
    generation**, reducing reliance on model-only responses
-   Deployed ML inference through a **FastAPI microservice**
-   Integrated AI services with the Node.js backend
-   Implemented secure **Patient / Doctor / Admin** role-based
    architecture
-   Built realtime doctor-patient communication using **Socket.IO**
-   Implemented **WebRTC video consultations** with authoritative
    room-state management
-   Implemented Razorpay payment workflow and verification
-   Built realtime chat and consultation lifecycle synchronization
-   Developed React dashboards for different user roles
-   Designed backend APIs for appointments, doctors, patients,
    consultations, payments, and AI-powered workflows

**Tech:** React • Node.js • Express.js • MongoDB • Socket.IO • WebRTC •
FastAPI • Scikit-learn • RAG

🌐 **Live:** https://medlink360-frontend.onrender.com

📂 **Repository:** https://github.com/Piyush-Mishra-IIITB/Prescripto

------------------------------------------------------------------------

## 📚 Core Strengths

``` text
DSA (Java)
    ↓
Backend Engineering
    ↓
Microservices
    ↓
Distributed Systems
    ↓
AI / ML & RAG
    ↓
Realtime Systems
    ↓
Docker & Kubernetes
```

I enjoy working on systems where **software engineering, AI, and
distributed architecture intersect**.

------------------------------------------------------------------------

## 📊 GitHub Stats

![GitHub
Stats](https://github-readme-stats.vercel.app/api?username=Piyush-Mishra-IIITB&show_icons=true&theme=tokyonight)

![GitHub
Streak](https://streak-stats.demolab.com?user=Piyush-Mishra-IIITB&theme=tokyonight)

![Top
Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Piyush-Mishra-IIITB&layout=compact&theme=tokyonight)

------------------------------------------------------------------------

## 🤝 Connect

**LinkedIn:** https://linkedin.com/in/piyush-mishra-06432a328

**Email:** piyushmishra8982@gmail.com

------------------------------------------------------------------------

⭐ Open to **AI Engineering, Backend SWE, Distributed Systems, and
Software Engineering internships & opportunities**.
