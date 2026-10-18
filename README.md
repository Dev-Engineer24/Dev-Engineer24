## Erik Lindqvist // Stockholm

Systems engineer focusing on structured concurrency, async event loops, task isolation, and network runtimes in Python.

---

### 📡 Upstream Ledger & Contributions

* **[agronholm/anyio](https://github.com/agronholm/anyio)** — TaskGroup lifecycles, cancellation semantics, and inter-thread signal routing.
* **[python-trio/trio](https://github.com/python-trio/trio)** — Nursery boundaries and non-blocking stream synchronization.
* **[encode/httpx](https://github.com/encode/httpx)** — Connection transport timeouts and pool teardown guarantees.

---

### 🛡️ Pre-Flight Verification & Discipline

1. **Cancellation Cleanliness**: Tasks must release file descriptors and sockets cleanly during CancelledError cascades.
2. **Deterministic Regression Tests**: All fixes include targeted unit tests exercising boundary timing conditions.
3. **Pre-Flight Invariant Airlock**: All patches are pre-flight validated against regression invariants using [ZeroSlop™ CI](https://github.com/marketplace/actions/zeroslop-by-ribbsaeter-systems).

---
*Python • AsyncIO • AnyIO • ZeroSlop™ CI*
