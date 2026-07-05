# Velvet AI Ecosystem

Offline-first AI architecture for vehicles, embedded systems, and autonomous environments.

This organization hosts the public infrastructure layers of the Velvet project.

Velvet is not a chatbot. Velvet is an OS-level intelligence system designed to live inside machines.

Velvet began in the vehicle domain, where local intelligence, hardware integration, deterministic behavior, and safety boundaries matter most. Vehicles impose strict constraints: unreliable connectivity, physical risk, local override needs, real-time systems, and regulatory expectations.

Because of that environment, Velvet is designed to operate locally, predictably, and transparently.

The core principle behind Velvet is simple:

> Intelligence must be modular, inspectable, and owned, not rented.
>
> Velvet is a modular, offline-first intelligence system designed to live inside machines, not behind APIs.

---

## Public Architecture

Velvet separates cognition, authority, execution, observation, interface, continuity, and receipts into independent public infrastructure layers.

```text
human / driver / operator
  -> interface or local client
  -> strict intent route
  -> runtime identity and context check
  -> Court authorization
  -> safety gate
  -> approved executor
  -> receipt
  -> observed result
```

> Brain proposes. Court authorizes. Executors act. Receipts remember.

No public component should bypass the Runtime authority path to reach hardware, files, shell commands, relays, CAN writers, actuators, steering, throttle, braking, locks, lighting, or other physical systems.

---

## Public Repository Set

### `velvet-docs`

Canonical public front door for Velvet doctrine, architecture, repository orientation, contributor paths, deployment notes, and newcomer guidance.

https://github.com/Velvet-ecosystem/velvet-docs

---

### `velvet-ai-core`

Cognition-facing foundation for doctrine, proposal models, identity and naming concepts, memory and conversational abstractions, handmaiden coordination concepts, and shared schemas.

Core proposes and models. It is not the authoritative boot or execution runtime.

https://github.com/Velvet-ecosystem/velvet-ai-core

---

### `velvet-runtime`

Local bootstrap, identity verification, authorization, safety gate, approved executor, replay protection, and execution-receipt wiring.

Runtime is the sole public authority path for physical or write-capable action. Current public capabilities are intentionally conservative and read-only unless explicitly documented otherwise.

https://github.com/Velvet-ecosystem/velvet-runtime

---

### `velvet-interface`

Scene, surface, widget, and router contracts for multi-surface presentation and intent routing.

Interfaces express state and request approved routes. They do not directly actuate hardware.

https://github.com/Velvet-ecosystem/velvet-interface

---

### `velvet-vehicle-can`

Receive-only CAN observation, vehicle fingerprinting, signal discovery, conservative decoding, and vehicle profile foundations.

CAN-discovered activity is observation, not permission. Write-capable behavior requires separate policy, safety gates, approved executors, and receipts.

https://github.com/Velvet-ecosystem/velvet-vehicle-can

---

### `velvet-event-protocol`

Structured local event schemas, source enforcement, receipt-aware delivery, and request/result transport boundaries.

Events describe. They do not authorize.

https://github.com/Velvet-ecosystem/velvet-event-protocol

---

### `velvet-receipts`

Tamper-evident, hash-chained, policy-bound decision and execution records for accountability, auditability, and continuity.

A receipt is evidence, not permission.

https://github.com/Velvet-ecosystem/velvet-receipts

---

### `velvet-continuity-spine`

Local-first identity, lineage, drift, surface binding, and receipt-compatible continuity records.

Continuity verifies identity and history. It does not grant authority.

https://github.com/Velvet-ecosystem/velvet-continuity-spine

---

## Development Disclosure Boundary

Velvet includes additional private research and build tracks that are not public-facing yet. Public documentation may describe broad future directions, but private repository names, internal implementation details, unreleased safety work, private research subjects, and experimental bodies stay out of public docs until explicit disclosure is approved.

The public project should show the foundation honestly: a large local-first system is being built, and early users or contributors can begin from the public docs, tests, read-only Runtime paths, receipts, interface contracts, and conservative vehicle observation.

---

## Design Principles

Velvet is built to be:

- offline-first
- local-API-first
- modular by design
- boundary-driven
- inspectable and auditable
- governance-aware
- receipt-preserving
- graceful under missing optional hardware

Velvet intentionally avoids the typical cloud-AI architecture model.

Velvet is not:

- a chatbot wrapper
- a SaaS AI service
- a cloud-dependent runtime
- a packaged consumer AI product
- a direct hardware-control shortcut

Velvet is infrastructure for long-lived intelligent systems.

---

## Intended Direction

Over time, the public Velvet ecosystem will expand carefully through documented, tested, safety-gated releases.

Public releases remain incremental, architectural, and transparent. New capabilities should become public only when their authority, privacy, safety, receipt, and contributor boundaries are ready.

---

## License

Core infrastructure components are released under GPLv3.

---

> Velvet does not forget. Every decision, every action, and every state change that matters should be traceable, inspectable, and understood.
>
> If intelligence exists inside the machine, it cannot hide behind the cloud. Velvet makes that visible.
