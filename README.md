# 👋 Akashdeep Singh
💻 **Software Engineer - 1** | 📍 Pune, Maharashtra (Hybrid)  
✉️ [akashdeepsingh30401@gmail.com](mailto:akashdeepsingh30401@gmail.com) | 💼 [LinkedIn](https://www.linkedin.com/in/akashdeepsingh30401/) | 🐙 [GitHub](https://github.com/skyshines)
---
## 🛠️ Technical Skills
| Category | Technologies & Fundamentals |
|---|---|
| ⚡ **Languages & Frameworks** | Go, Java, JavaScript, React.js, .NET |
| ☁️ **Cloud, Streaming & Tools** | AWS (ECS, EC2), Apache Kafka, Redis, GraphQL, Git / GitHub / GitLab, Jira, Confluence, WSL, Postman |
| 📊 **Monitoring & CI/CD** | Jenkins, ELK Stack (Elasticsearch, Logstash, Kibana), Dynatrace, Grafana |
| 🤖 **AI-Assisted Development** | Cursor (custom Skills, Rules, Commands, and AI workflows), GitHub Copilot |
| 🗄️ **Databases** | Cassandra, MySQL, MongoDB |
| 📚 **Core CS** | Microservices, Data Structures & Algorithms, Operating Systems, Object-Oriented Programming, Database Management Systems, Computer Networks |
---
## 💼 Work Experience
### 🏢 ConnectWise - Software Engineer - 1
📅 **June 2025 - Present** | 📍 Pune, Maharashtra (Hybrid)
- ✅ **Partner Patch Approvals Workflow:** Built the end-to-end approvals workflow by introducing a new `"NEW"` approval status in the backend, extending the GraphQL query to expose it, and developing the React approvals grid so partners can approve or reject patches prior to distribution.
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
