# 🔋 VoltTrace Core Engine

![Version](https://img.shields.io/badge/Engine_Version-1.0.0--core-blue.svg)
![License](https://img.shields.io/badge/License-Proprietary-green.svg)
![Compliance](https://img.shields.io/badge/Compliance-EU_2023%2F1542-success.svg)
![Architecture](https://img.shields.io/badge/Architecture-Deterministic_Zero--Trust-red.svg)

**VoltTrace Core** is an industrial-grade, deterministic Digital Twin Engine designed to enforce the physical and cryptographic lifecycle of Lithium-ion batteries. Built as the ultimate compliance infrastructure for the **EU Battery Regulation (2023/1542)**, it ensures absolute causality from raw material extraction to final pack assembly.

> *We don't build web forms. We build the cryptographic ledger governed by the laws of physics.*

---

## 🚀 Engine Philosophy: The "Anti-Form" Paradigm

The industry is saturated with fragile, human-entry "Battery Passports." VoltTrace redefines the standard by operating as a **Physics-Bound Rules Engine**. We address the critical vulnerabilities of modern global supply chains—data tampering, scope shifting, and API interception—by implementing a pure Zero-Trust architecture coupled with deep recursive DAG (Directed Acyclic Graph) compute logic.

### Core Engine Capabilities
* **🛡️ Cryptographic Asset Anchoring**: Sub-second Keccak-256 fingerprinting (Industrial Grade) of physical parameters. The engine actively intercepts and flags cryptographic anomalies (`[HASH MISMATCH DETECTED]`), guaranteeing absolute immutability.
* **🏭 Dynamic Carbon Recursion (Scope 1/2/3)**: Automated emissions calculation based on real-time DAG traversal. A 1-gram variation in upstream mining assets triggers a synchronized, deterministic recalculation across the entire downstream ledger.
* **⚖️ Physics Law Enforcement**: Form inputs and API payloads are not just type-checked; they are physics-checked. The compute node automatically rejects anomalies (e.g., EV capacities >500kWh) directly at the I/O gateway.
* **🔐 Multi-Tenant Industrial Isolation**: Strict structural RBAC. Miners, Assemblers, and Regulators operate within isolated cryptographic views.

---

## 🏗️ Engine Architecture & Topology

VoltTrace is engineered on a proprietary, ultra-low-latency decoupled stack. We bypassed standard fragile middleware to establish direct, deterministic pathways to the persistence layer.

* **Client Matrix**: High-performance portal with localized state management and dynamic DAG visualization.
* **Physics-Bound Compute Node**: An asynchronous, high-throughput validation gateway that strictly enforces real-world physics laws.
* **Persistence Layer**: Deterministic relational modeling engine, architected for rapid memory-mapped reads.
* **IIoT Integration Ready**: Designed to ingest structured payloads directly from factory MES/ERP systems via secure endpoints.

---

## ⚙️ Engine Ignition Sequence (Local Evaluation)

To initialize the VoltTrace engine in a local sandbox environment:

### 1. Matrix Initialization
```bash
git clone [https://github.com/tiankonghpf/volttrace-core.git](https://github.com/tiankonghpf/volttrace-core.git)
cd volttrace-core
npm install
2. Environment Configuration
Create a .env file in the root directory and define your data persistence layer:
echo "DATABASE_URL=\"file:./dev.db\"" > .env
3. Ledger Instantiation
Initialize the schema and seed the cryptographic actors:
npx prisma db push
npm run db:seed
4. Dual-Node Ignition
Boot both the physics-bound validation compute node and the client matrix:
# Terminal 1: Ignite the Compute Node (Validation Gateway)
npm run dev:backend

# Terminal 2: Ignite the Client Matrix (Visual Interface)
npm run dev:frontend
5. Access the Secure Dashboards
Navigate to http://localhost:3000/login.
Local Development Credentials (Demo Only):

Assembler Terminal: factory / 123456

Miner Terminal: miner / 123456

EU Regulator: admin / admin (or admin/volttrace depending on local seed)

🔬 Zero-Trust Audit Protocol
We challenge you to break the engine's causality:

The Physics Violation: Log in as factory and attempt to inject a payload with 99999 kWh capacity. Watch the compute node instantly intercept and terminate the transaction with a [PHYSICS_VIOLATION].

The Integrity Verification: Open any generated Digital Passport and engage the green Blockchain Anchored trigger. The engine will execute a live cryptographic recalculation of the physical assets against the anchored ledger.

📈 Engine Scaling Trajectory
[x] EU 2023/1542 Compliance Data Structuring

[x] Recursive Supply Chain DAG Compute Engine

[x] Automated Scope 1/2/3 Carbon Footprint Engine

[x] Multi-tenant Industrial Security Gateway

[x] Phase 1.5: Rust-based Verification Core (Initial Build)

[ ] Phase 2: Direct IIoT & MES System API Integration

[ ] Phase 3: Mainnet Smart Contract Deployment (Polygon/Ethereum)

📞 Strategic & Technical Access
For venture capital inquiries, technical due diligence requests, or to obtain the full VoltTrace Sovereign Whitepaper, please contact the architecture lead directly:

Lead Architect: Peifeng Huang

Secure Channel: moonlight00806@gmail.com

GitHub: @tiankonghpf

Confidentiality Notice: Technical deep-dives into the core logic require an executed NDA.

VoltTrace Core — Precision engineering for the future of global energy ledgers.
