# Velvet Ecosystem

Velvet is a modular, offline-first AI architecture designed for embedded environments.

This organization hosts the public infrastructure layers of the Velvet project.

Velvet was originally developed in the vehicle domain, where local intelligence, hardware integration, and deterministic behavior matter most. Vehicles impose strict constraints: unreliable connectivity, safety boundaries, real-time systems, and regulatory expectations.

Because of that environment, Velvet was designed from the beginning to operate locally, predictably, and transparently.

The core principle behind Velvet is simple:

> Intelligence should be modular, inspectable, and owned — not rented.

---

## 🧠 Current Components (Alpha)

### velvet-ai-core

The runtime spine of the Velvet system.

Features:

- Modular Python runtime framework
- Event-driven architecture
- Hot-swappable module model
- Interface contracts between subsystems
- Boundary-aware architecture documentation
- Zero external runtime dependencies (Python stdlib only)

This repository provides architectural infrastructure, not a finished AI product.

---

### velvet-vehicle-can

Vehicle communication and diagnostics layer for Velvet.

Capabilities under development:

- CAN bus backend interface
- Vehicle dialect learning
- ECU fingerprinting
- Vehicle profile modeling
- Qualification and safety gating

This subsystem is designed for embedded Linux and automotive environments and serves as the bridge between Velvet and vehicle hardware.

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
