# Mykhailo Krasynskyi

**Senior Full-Stack & Systems Engineer** · Rust · Flutter/Dart · Industrial IoT · Web Systems

[Website](https://www.gencto.uk) · [pub.dev](https://pub.dev/publishers/gencto.uk) · [LinkedIn](https://www.linkedin.com/in/gencto) · [Email](mailto:info@gencto.uk)

<p>
  <img src="https://skillicons.dev/icons?i=rust,dart,flutter,ts,react,nextjs,nodejs,nestjs,py,docker,kubernetes,aws,gitlab&perline=12" alt="Tech stack: Rust, Dart, Flutter, TypeScript, React, Next.js, Node.js, NestJS, Python, Docker, Kubernetes, AWS, GitLab" />
</p>

---

### Now

- 🐉 Building **[WYRM](https://github.com/gencto/wyrm)**, an open-source industrial IoT broker in **Rust** with a **Flutter** desktop studio.
- 🔭 Building AI-assisted engineering workflows with the **Claude API**, **MCP** and subagents.

---

### Overview

Full-Stack Engineer with 8+ years of experience architecting cross-platform mobile apps, IoT platforms, and scalable web solutions. Specialized in the **Flutter/Dart ecosystem**, hardware-level integrations, and industrial communication protocols.

- **IoT & Industrial background:** Built engineering workflows and protocol-level integrations (BACnet, Modbus, MQTT, DLMS, NB-IoT) across 20+ BMS and Smart Metering projects.
- **AI-Assisted Engineering:** Actively integrating LLM capabilities (Anthropic Claude API, MCP, subagent workflows) into production dev pipelines.

---

### Featured Project — [WYRM](https://github.com/gencto/wyrm)

An industrial IoT broker on top of [Eclipse Zenoh](https://zenoh.io). Devices, services and logic live in one tree of nodes, and every client reads it the same way: `list`, `subscribe`, `set`, `invoke`.

- **Rust broker (`wyrmd`):** one binary with a router, admin plane, flow engine, historian and user gateway; canonical CBOR on the wire, TLS/mTLS and signed per-request tokens by default.
- **Protocol links:** Modbus TCP/RTU, BACnet/IP, OPC UA, Siemens S7, SNMP, MQTT/Sparkplug B, HTTP, Prometheus — embedded, as processes, or as sandboxed **WebAssembly** components.
- **Logic & data:** a dataflow engine with 125 block types, an embedded historian, schedules, alarms and history sync to Postgres/TimescaleDB, InfluxDB, MongoDB and more.
- **Multi-site:** brokers chain over QUIC + mTLS, with standby failover.
- **WYRM Studio:** a Flutter desktop app (English/Ukrainian) — tree explorer, flow editor, history, access control.
- **AI & SDKs:** an MCP server and Claude Desktop extension; SDKs for Rust, Dart and a C ABI.

---

### Selected Work

| Area | What I built |
|---|---|
| **Building Management Systems** | Protocol-level integrations (BACnet, Modbus, Niagara 4) and engineering workflows across 20+ BMS projects. |
| **Smart Metering & IoT** | Device communication over DLMS, MQTT and NB-IoT — from hardware to cloud dashboards. |
| **Cross-platform Mobile** | Flutter apps with NFC, biometrics and offline-first storage (Riverpod, BLoC, Hive). |
| **AI-Assisted Dev Tooling** | LLM-powered pipelines built on the Claude API, MCP servers and agent workflows. |

---

### Tech Stack

| Domain | Core Technologies |
|---|---|
| **Systems & Rust** | Rust, Tokio, Eclipse Zenoh, Axum, rustls, Wasmtime (WASM components), CBOR, QUIC/mTLS, C FFI |
| **Mobile & Dart** | Dart, Flutter, Riverpod, BLoC, Freezed, Serverpod, Hive |
| **Web & Back-end** | React, Next.js, Node.js (Nest.js), TypeScript, Python |
| **IoT & Hardware** | BACnet, Modbus, OPC UA, Siemens S7, SNMP, MQTT/Sparkplug B, DLMS, NB-IoT, NFC, Biometrics, Niagara 4 |
| **Cloud & DevOps** | Docker, Kubernetes, AWS, GitLab CI/CD, gRPC, WebSockets |
| **AI Workflows** | Anthropic Claude API, Model Context Protocol (MCP), Agentic Frameworks |

---

### Recent Certifications

- **Anthropic Academy** — Claude API · MCP (Intro + Advanced) · Agent Skills & Subagents (2026)
- **TensorFlow 2.0** — Deep Learning & AI (2024)
- **Niagara 4** Technical Certification — Tridium (2020)
