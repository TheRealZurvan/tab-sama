# Mojtaba "Tab" Ahmadi
**Senior Backend & Distributed Systems Engineer**

📧 tabmadi@proton.me |
📱 +968 92212401 |
🔗 [LinkedIn](https://linkedin.com/in/tabmadi) |
🐙 [GitHub](https://github.com/TheRealZurvan) | 
🤖 [Stackoverflow](https://stackoverflow.com/users/4155138/zurvan) |
📍 Oman

---

## Professional Summary

Senior backend and distributed systems engineer with 10+ years of experience building high‑throughput, fault‑tolerant platforms in production. Specialized in Go‑based microservices, event‑driven architectures, and long‑running workflow orchestration for financial and blockchain systems.

Experienced in designing and operating infrastructure handling millions of transactions, with a strong focus on correctness, observability, and failure resilience. Background spans payments, blockchain infrastructure, and data platforms, with hands‑on ownership from system design through production operations.

Currently focused on senior individual contributor roles building backend and distributed systems at scale.

---

## Skills

### Backend & Distributed Systems
Golang (Go), Rust, Node.js, Python, Distributed Systems, Microservices, Event‑Driven Architecture, Kafka, RabbitMQ,
Temporal, gRPC, PostgreSQL, Redis, Elasticsearch, Neo4j, CQRS, API Gateway, Tyk, OAuth2, OIDC, Auth0

### Blockchain Infrastructure
Cosmos SDK, Tendermint, Validator Operations, EVM, Solidity, Solana, UTXO, Cross‑chain Communication,
Zero‑Knowledge Proofs (ZKPs), DeFi Protocols, DEX Architecture

### Infrastructure & Platform
Kubernetes (K8s), Docker, Helm, Argo CD, GitOps, Terraform, Ansible, AWS, Google Cloud Platform (GCP), DigitalOcean,
GitHub Actions, Prometheus, Grafana, HashiCorp Vault, Elastic (ELK) Stack, Linux, OWASP

---

## Experiences

### Senior Backend Engineer
**[Zion Payment](https://zionpayment.com/)** – Crypto payment solutions | *07/2025–Present*
- Integrated Polygon, TON, and Polkadot blockchains into the payments platform, increasing daily transactions by **50%**
- Owned the migration from a custom Saga implementation to **Temporal**, improving developer velocity and reducing MTTR by **3×**
- Designed and deployed an **API Gateway** using Tyk with Auth0 integration, reducing average API latency by **80%**
- Deployed and operated **30+ microservices** on Kubernetes (DigitalOcean), maintaining **99.9% availability**
- Architected core API security modules aligned with **OWASP**, eliminating all critical vulnerabilities identified in penetration tests

### Senior Blockchain Engineer
**[Apybara (Coinbase partner)](https://www.staking.xyz/)** – Zero‑Knowledge DeFi Infrastructure | *06/2024–06/2025*
- Designed backend systems supporting a staking platform serving **2,000+ MAUs** within the first quarter
- Built **gRPC‑based microservices** indexing **2M+ transactions**, reducing operational costs by **20%**
- Implemented **Temporal** for long‑running blockchain workflows, achieving **100% execution reliability** during chain instability
- Operated and maintained validators for **Aleo, Ethereum, and Cosmos** with **99.8% uptime**
- Built and operated a custom **Geth node**, replacing Infura and reducing indexing costs by **75%**
- Designed an observability stack using **Prometheus, Loki, and Grafana**, reducing incident resolution time by **40%**

### Senior Software Engineer
**[Zion Payment](https://zionpayment.com/)** – Crypto payment solutions | *05/2022–05/2024*
- Integrated payment processing across **12+ blockchain networks** (EVM, UTXO, Tron, XRP), achieving **99.9% uptime**
- Designed a scalable **Go‑based microservice architecture** processing **1,000+ transactions/day**
- Engineered an **event‑driven system** using RabbitMQ across **30+ services**
- Implemented the **Saga Pattern** to ensure consistency in distributed transactions
- Built CI/CD pipelines with **GitHub Actions**, reducing deployment time from **2 hours to 15 minutes**
- Designed a multi‑layer wallet security architecture, achieving **0 security incidents**

### Blockchain Engineer
**[THORSwap](https://www.thorswap.finance/)** – Cross‑chain DEX on THORChain | *09/2021–04/2022*
- Architected and developed blockchain‑specific microservices enabling cross‑chain swap execution
- Migrated a legacy monolith to **Golang microservices** using the Strangler Pattern, reducing infrastructure costs by **90%**
- Implemented **event‑driven communication** using Kafka and Confluent, indexing **100,000+ transactions/day**
- Applied **event sourcing** for blockchain data persistence, ensuring complete transaction auditability
- Improved query performance by **20×** using **CQRS** with separated read/write databases
- Built an API gateway with load balancing, authentication, and rate limiting for **5,000+ daily users**
- Reduced cloud costs by **10%** by migrating infrastructure from AWS to **GCP**
- Implemented **GitOps** with ArgoCD for Kubernetes, ensuring 100% environment consistency and self‑service deployments

### Backend Engineer
**Science and Technology Park** – Startup Incubator & R&D Hub | *06/2017–08/2021*
- Launched a **Layer‑1 blockchain** using the **Cosmos SDK**, progressing from testnet to mainnet in **9 months**
- Built a blockchain explorer indexing **100% of blocks and transactions** with **P95 < 800 ms**
- Delivered a non‑custodial wallet with **1,000 installs**, **100 WAU**, and **0 security incidents**
- Scaled indexing infrastructure with a **50‑node Docker Swarm**, handling **10M+ requests/day**
- Implemented centralized logging and monitoring with the **ELK stack**, reducing MTTR by **80%**
- Automated provisioning of **50+ servers** using **Ansible**, reducing setup time from days to under an hour
- Optimized a core graph algorithm with a **100× speedup** by rewriting it from Python to **Rust**

---

## Projects

### [Omnivers (ExchAInge)](https://www.omnivers.net/)
*Decentralized data exchange infrastructure | Open Source | 2025*
- Designed and implemented a trustless data exchange protocol for verified physical AI datasets
- Developed core on-chain logic in **Rust (Solana)** to enforce ownership, verification, and settlement guarantees
- Built off-chain services coordinating with on-chain programs to ensure correctness and secure data delivery
- Focused on deterministic execution, failure-resilient workflows, and protocol-level invariants

**Tech:** Rust, Solana

### [Trustero](https://trustero.pages.dev/auth/login)
*Peer-to-peer encrypted communication system | Personal Project | 2024*
- Built a serverless, peer-to-peer messaging system with decentralized client discovery
- Implemented secure connection establishment using **WebRTC**, with BitTorrent-based signaling mechanisms
- Addressed NAT traversal, connection reliability, and end-to-end encryption constraints in distributed environments

**Tech:** TypeScript, WebRTC

### [NightTrader](https://nighttrader.exchange/)
*Non-custodial exchange infrastructure | Open Source | 2023*
- Implemented a non-custodial trading architecture based on **multi-signature authorization**
- Designed transaction flows ensuring asset safety without centralized custody
- Focused on cryptographic guarantees, transaction correctness, and adversarial failure scenarios

**Tech:** JavaScript, Cryptography

### [Layer](https://layer.cafe/)
*Online mind mapping and task manager | Freelance | 2023*
- Designed backend data models using a **graph-based architecture** to support complex relationship queries
- Implemented an **event-driven pipeline** using **Kafka** for data propagation and indexing
- Designed and operated a **hot-warm-cold storage architecture** leveraging **Elasticsearch** to optimize latency and cost
- Built offline-first synchronization mechanisms supporting eventual consistency across clients

**Tech:** Python, Kafka, Elasticsearch, Neo4j

---

## Education

### Bachelor of Science in Computer Science
**Azad University** | *2015–2017*
