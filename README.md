# Soumaditya Pal
**Platform & Systems Engineer**
[Portfolio](https://www.soumadityapal.in/) | [Email](mailto:soumaditya.pal23@gmail.com)

**Status:** Open for SDE roles & specialized freelance contracts.

## The Reality of Production
Writing working code is the floor. Surviving production is the job. 

I engineer high-throughput backend services and distributed systems. When your architecture bottlenecks, your database connections exhaust, or your polling layers choke under traffic spikes, I fix it. I specialize in replacing heavy HTTP polling with WebSockets/SSE, decoupling blocking workloads via task queues, and ensuring exact state synchronization in multi-tenant environments.

## Engineering Outcomes
* **Asynchronous Execution (Emergence Mobility):** Architected distributed queues using BullMQ and Valkey to process heavy async jobs. Replaced legacy polling with Server-Sent Events (SSE). Result: Eliminated server ingress overhead and prevented event-loop blocking under high concurrent user load.
* **Distributed State Synchronization (LYNER):** Engineered a real-time collaboration engine using WebSockets and Fastify. Implemented CRDTs (Conflict-free Replicated Data Types) backed by an append-only PostgreSQL event log to guarantee global consistency across concurrent client edits.
* **Client-Side Fault Tolerance (FOCUSKARO):** Built a background processing platform that survives severe browser-side throttling using Web Workers. Engineered a lightweight SSE telemetry system with heartbeat failure detection to decouple the backend from dead client states.
* **Concurrency Control (Legal Care):** Profiled and patched critical thread and async race conditions in distributed Node.js authorization flows, stabilizing session state reliability.

## Freelance Consulting
I take on fixed-scope infrastructure contracts. I do not bill for hours; I bill for solved architectural failures.
* **Legacy Migrations:** Converting standard REST/Polling architectures to high-concurrency WebSocket/SSE streams.
* **Performance Tuning:** Optimizing Node.js event-loop blocks, PostgreSQL query plans, and Redis caching tiers.
* **System Decoupling:** Implementing BullMQ/Valkey queue systems to offload heavy synchronous tasks via Pub/Sub patterns.

## Technology Stack
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)
![Fastify](https://img.shields.io/badge/fastify-000000?style=for-the-badge&logo=fastify&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Valkey](https://img.shields.io/badge/Valkey-8A2BE2?style=for-the-badge)
![BullMQ](https://img.shields.io/badge/BullMQ-FF4081?style=for-the-badge)
![Pub/Sub](https://img.shields.io/badge/Pub/Sub-4285F4?style=for-the-badge)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
