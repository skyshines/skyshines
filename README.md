- 🛡️ **Sequential Patch Rollout Safety:** Implemented patch deployment groups tied to Partner Approval Groups, enforcing sequential rollout ordering to limit the blast radius of faulty patches - adopted by **5 major partners across 50K+ endpoints**.
- ⚡ **Event-Driven Scheduler Reliability:** Diagnosed and resolved scheduler job mismatches between Scheduler and Patching microservices by consuming `Effective Policy Change` events from Apache Kafka and removing fragile synchronous API dependencies, **reducing job reaction errors by 76%**.
- 🔄 **Automated Policy Reconciliation:** Built a 4-hour policy job reconciliation service that creates or deletes scheduler jobs against the latest authoritative policy state to recover jobs missed by lost or false Kafka events across **200K+ endpoints in 3 global production regions**.
- 🔍 **OS Patching & Self-Serve Diagnostics:** Led end-to-end Windows Event Viewer integration inside the OS patching plugin, mapping critical workflows (assessment, download, install, deployment, feature update) to structured events with traceable context - improving partner self-serve debugging and driving **10 partner launch-day sign-ups**.
- 🚀 **High-Throughput Bulk Export APIs:** Built 3 partner-facing bulk export APIs (patch details, compliance summary, partner approvals) supporting endpoint, client, site, and partner-level paginated responses using Go worker pools and goroutines for concurrent DB reads, exporting an average of **2 million endpoints' worth of data per month**.
🧰 `Tech Stack:` `Go` `React` `Cassandra` `Kafka` `Redis`
---
### 🏢 ConnectWise - Software Development Engineer (Internship)
📅 **May 2024 - August 2024** | 📍 Pune, Maharashtra (On-Site)
- 🎟️ **Entitlement Management UI:** Built the Entitlement Management UI in React for creating and editing product and feature entitlements via the Entitlement Microservice, **eliminating 450+ monthly support tickets** to the Rapid Response Team (RRT).
🧰 `Tech Stack:` `JavaScript` `React` `Go` `.NET` `Redis` `Cassandra`
---
## 🚀 Projects
### 🧠 [Knowledge-Base-Master AI-Native Repository Context Engine](https://github.com/skyshines/Knowledge-Base-Master)
📅 **Nov 2026** | 🔗 [github.com/skyshines/Knowledge-Base-Master](https://github.com/skyshines/Knowledge-Base-Master)
- 🗺️ **Targeted Context Routing:** Designed an AI-native knowledge base skill that pre-maps repository workflows, DB schemas, Kafka topics, and API contracts into structured `.md` files with a keyword-to-file routing index - enabling agents to load 3-5 targeted files per task instead of scanning 40+ source files, **reducing context window consumption by ~65%** and **estimated LLM API cost by 40-50%**.
- 🤝 **Sub-Agent Cross-Repo Extraction:** Architected a sub-agent delegation pattern where cost-efficient `flash-lite` models shallow-clone foreign repos, extract only specified API/Kafka contracts, write KB docs, and terminate cleanly - keeping parent context clean via a TTL and commit-hash drift freshness layer.
- ⏱️ **Velocity & Documentation Impact:** **Reduced agent task completion time by ~20%** by eliminating orientation round-trips and **accelerated ADD generation, debugging ticket resolution, and onboarding documentation by ~50%** through single-pass artifact generation.
- 🧩 **Repo-Portable Design:** Built as a language-agnostic skill with auto-detection for Java/Spring, Go, Python, and Node.js entry points, zero host-repo code changes, and two core commands (`/kb setup` and `/kb refresh`).
🧰 `Tech Stack:` `Markdown` `Git` `Multi-model Agent Architecture (flash-lite sub-agents)` `Antigravity / Cursor / Claude Agent Skills`
---
## 🏆 Achievements
- 🥈 **2nd Position** - Code Red by Coding Cell AIT
- 🎯 **Level 2 Qualifier** - GRiD 5.0 by Flipkart (top **2,000** teams pan-India out of **120,000+** teams)
---
## 🎓 Education
🏛️ **Army Institute of Technology, Pune** | 📅 **2021 - 2025**  
📜 Bachelor of Computer Engineering - **8.89 SGPA** | 📍 Pune, Maharashtra
