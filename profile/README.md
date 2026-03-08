# Velvet AI Ecosystem

Offline-first AI architecture for vehicles, embedded systems, and autonomous environments.

This organization hosts the public infrastructure layers of the Velvet project.

Velvet was originally developed in the vehicle domain, where local intelligence, hardware integration, and deterministic behavior matter most. Vehicles impose strict constraints: unreliable connectivity, safety boundaries, real-time systems, and regulatory expectations.

Because of that environment, Velvet was designed from the beginning to operate locally, predictably, and transparently.

The core principle behind Velvet is simple:

> Intelligence should be modular, inspectable, and owned — not rented.

---

## Core Architecture

Velvet is composed of several core infrastructure layers.

### velvet-ai-core
Runtime spine of the Velvet AI system.

Event-driven orchestration, module lifecycle management, and the core intelligence loop.

https://github.com/Velvet-ecosystem/velvet-ai-core

---

### velvet-vehicle-can
Vehicle communication layer.

Provides CAN bus communication, signal discovery, and vehicle telemetry access.

https://github.com/Velvet-ecosystem/velvet-vehicle-can

---

### velvet-interface
Multi-surface scene framework for embedded interfaces.

Designed for vehicles, robotics dashboards, mobile devices, and industrial HMIs.

https://github.com/Velvet-ecosystem/velvet-interface

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
