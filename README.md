# Erik Lindqvist

Systems engineer based in Stockholm, Sweden.  
Working on async I/O primitives, structured concurrency, and event-loop invariants.

---

### ⚡ Technical Domains & Focus

| Domain | Focus |
|---|---|
| **Structured Concurrency** | Task group cancellation, exception bubbling, and clean child termination |
| **Event Loop Internals** | Timer precision, selector loop performance, and task scheduling |
| **Async Protocols** | Streaming data pipelines, backpressure handling, and graceful shutdown |

---

### 📐 Principles

1. **Leak-Free Concurrency**: Ensuring every spawned background task has a deterministic parent scope.
2. **Explicit Cancellation**: Shielding critical rollback blocks while honoring cancellation tokens.
3. **Strict Type Annotations**: Using modern typing primitives (`TypeVar`, `ParamSpec`, `Protocol`) for async signatures.

---
*Python • AsyncIO • AnyIO • Trio • Structured Concurrency*
