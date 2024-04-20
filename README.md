
# 🌐 System Design Overview

System design is a fundamental process in software engineering where engineers plan and define the architecture, components, interfaces, and data for a system to meet specified requirements. It involves considering and balancing numerous aspects such as scalability, performance, reliability, and security to ensure the system operates effectively across a range of real-world scenarios.

Effective system design addresses both the technical and business challenges of creating a robust architecture that can scale and adapt as needs evolve. This involves making critical decisions about software and hardware configurations, communication strategies, data management practices, and more. The goal is to create a system that not only meets the current needs but also anticipates future growth and technological advancements.

Below are the topics, building blocks, architectural patterns, and other resources that are crucial to understanding and mastering system design:

### 🔍 Topics 

System design topics cover various aspects of designing and managing scalable, efficient, and robust systems. These topics range from understanding fundamental principles like Scalability and the CAP Theorem to practical strategies such as Consistent Hashing and Rate Limiting. Other key areas include designing APIs, understanding different types of consistency, and choosing between synchronous and asynchronous communications. Each topic dives deep into the mechanisms and considerations necessary to build systems that can handle the demands of modern computing environments.


- [Scalability](topics/scalability.md)
- [Througput vs Latency](topics/throughput-vs-latency.md)
- [Cap Theorem](topics/cap-theorem.md)
- [ACID Transactions](topics/acid-transactions.md)
- [Consistent Hashing](topics/consistent-hashing.md)
- [Rate Limiting](topics/rate-limiting.md)
- [API Design](topics/api-design.md)
- [Strong vs Eventual Consistency](topics/strong-vs-eventual-consistency.md)
- [Synchronous vs. asynchronous communications](topics/synchronous-vs-asynchronous-communications.md)
- [REST vs RPC](topics/rest-vs-rpc.md)
- [Batch Processing vs Stream Processing](topics/batch-processing-vs-steam-processing.md)
- [Fault Tolerance](topics/fault-tolerance.md)
- [Consensus Algorithms](topics/consensus-algorithms.md)
- [Gossip Protocol](topics/gossip-protocol.md)
- [Service Discovery](topics/service-discovery.md)
- [Disaster Recovery](topics/disaster-recovery.md)
- [Distributed Tracing](topics/distributed-tracing.md)

### 🧱 Building Blocks

Building blocks in system design refer to the core components and technologies that form the foundation of any system architecture. This includes Databases, Content Delivery Networks (CDNs), and the Domain Name System (DNS), among others. Advanced components like Distributed Caching, Load Balancing, and Database Sharding are crucial for enhancing performance and scalability. Understanding these elements is essential for architects and developers to effectively design, optimize, and maintain robust systems that can scale and perform under varying loads.

- [Databases](blocks/databases.md)
- [Content Delivery Network (CDN)](blocks/cdn.md)
- [Domain Name System (DNS)](blocks/dns.md)
- [Caching](blocks/caching.md)
- [Distributed Caching](blocks/distributed-caching.md)
- [Load Balancing](blocks/load-balancing.md)
- [SQL vs NoSQL](blocks/sql-vs-nosql.md)
- [Database Index](blocks/database-index.md)
- [Consistency Patterns](blocks/consistency-patterns.md)
- [HeartBeat](blocks/heartbeat.md)
- [Circuit Breaker](blocks/circuit-breaker.md)
- [Idempotency](blocks/idempotency.md)
- [Database Scaling](blocks/database-scaling.md)
- [Data Replication](blocks/data-replication.md)
- [Data Redundancy](blocks/data-redundancy.md)
- [Database Sharding](blocks/database-sharding.md)
- [Microservices Guidelines](blocks/microservices-guidelines.md)
- [Failover](blocks/failover.md)
- [Proxy Server](blocks/proxy-server.md)
- [Message Queues](blocks/message-queues.md)
- [WebSockets](blocks/websockets.md)
- [Bloom Filters](blocks/bloom-filters.md)
- [API Gateway](blocks/api-gateway.md)
- [Distributed Locking](blocks/distributed-locking.md)
- [Checksum](blocks/checksum.md)

### 🏛️ Architectural Patterns

Architectural patterns provide a high-level framework that guides the organization and configuration of software systems. Popular patterns such as Microservices Architecture and Serverless Architecture focus on ways to structure applications for ease of deployment, scalability, and independence. Other patterns like Event-Driven and Peer-to-Peer (P2P) Architecture cater to specific needs such as dynamic event handling and decentralized network design. Each pattern offers unique advantages and challenges, and is chosen based on the specific requirements and constraints of the project at hand.

- [Client-Server Architecture](patterns/client-server-architecture.md)
- [Microservices Architecture](patterns/microservices-architecture.md)
- [Serverless Architecture](patterns/serverless-architecture.md)
- [Event-Driven Architecture](patterns/event-driven-architecture.md)
- [Peer-to-Peer (P2P) Architecture](patterns/p2p-architecture.md)

### 📚 Important Summaries To Read
- [Top 15 Tradeoffs](summaries/top-15-tradeoffs.md)
- [How to Answer a System Design Interview Problem](summaries/system-design-interview-problem.md)

### 🎥 Practical Videos
- [Design Unified Payment Interface (UPI)](https://www.youtube.com/watch?v=QpLy0_c_RXk)
- [Design Stock Exchange System](https://www.youtube.com/watch?v=dUMWMZmMsVE)
- [Design Live Comments](https://systemdesign.one/live-comment-system-design/)
