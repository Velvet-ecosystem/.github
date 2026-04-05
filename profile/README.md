# Velvet AI Ecosystem

Offline-first AI architecture for vehicles, embedded systems, and autonomous environments.

This organization hosts the public infrastructure layers of the Velvet project.

Velvet is not a chatbot, Velvet is an OS-level intelligence sytem that lives inside machines.

Velvet was originally developed in the vehicle domain, where local intelligence, hardware integration, and deterministic behavior matter most. Vehicles impose strict constraints: unreliable connectivity, safety boundaries, real-time systems, and regulatory expectations.

Because of that environment, Velvet was designed from the beginning to operate locally, predictably, and transparently.

The core principle behind Velvet is simple:

> Intelligence must be modular, inspectable, and owned — not rented.
> Velvet is a modular, offline-first intelligence system designed to live inside machines - not behind APIs
---

## Core Architecture

Velvet is composed of several core infrastructure layers.

### velvet-ai-core - Runtime Spine
Runtime spine of the Velvet AI system.

Event-driven orchestration, module lifecycle management, and the core intelligence loop.

https://github.com/Velvet-ecosystem/velvet-ai-core

---

### velvet-vehicle-can
Real-time vehicle communication layer.

Provides CAN bus communication, signal discovery, and vehicle telemetry access.

https://github.com/Velvet-ecosystem/velvet-vehicle-can

---

### velvet-interface
Unified Multi-surface scene framework for embedded interfaces.

Designed for vehicles, robotics dashboards, mobile devices, Embedded systems and industrial HMIs.

https://github.com/Velvet-ecosystem/velvet-interface

---

### velvet-receipts

Tamper-evident memory ledger for Velvet AI.

Provides hash-chained, policy-bound decision receipts for auditability, accountability, and long-term system coherence.

https://github.com/Velvet-ecosystem/velvet-receipts

---

## System Flow

Velvet is structured as a layered intelligence system.

Velvet separates **interface**, **intelligence**, and **hardware control** into independent layers.

User / Driver / Operator
        │
        ▼
  velvet-interface
        │
        ▼
    velvet-ai-core
        │
        ▼
  velvet-vehicle-can
        │
        ▼
Vehicle Systems / Sensors / Hardware

---

## 🧩 Design Principles

Velvet is built to be:

- Offline-first
- Modular by design
- Boundary-driven
- Inspectable and auditable
- Governance-aware

Velvet intentionally avoids the typical cloud-AI architecture model.

Velvet is not:

- A chatbot wrapper
- A SaaS AI service
- A cloud-dependent runtime
- A packaged consumer AI product

Velvet is infrastructure for long-lived intelligent systems.

---

## 🛠 Intended Direction

Over time the Velvet ecosystem will expand to include:

- Automotive Grade Linux (AGL) integration
- Human-machine interface layers (Qt-based)
- Governance and execution control systems
- Deterministic logging and replay infrastructure
- Embedded hardware integration
- Mobile and home system surfaces

Public releases will remain incremental, architectural, and transparent.

---

## 📜 License

Core infrastructure components are released under GPLv3





---

> Velvet does not forget. Every decition, every action, every state can be traced, inspected, and understood.
If intelligence exists inside the machine, it cannot hide behind the cloud.
Velvet makes that visible.
