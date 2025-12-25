# AutomationZ Restart Loop Guard (UI)

AutomationZ Restart Loop Guard is a lightweight admin UI tool that prevents **infinite restart loops** by guarding restart/start attempts on the local machine.

It does **not** detect crashes.
It protects your automation from repeatedly restarting a failing service or game server.

---

## 🧠 What this tool does

- Tracks restart/start attempts within a configurable time window
- Locks further attempts when a threshold is reached
- Persists the lock across reboots (manual unlock required)
- Provides a clear UI status: OK / WARNING / LOCKED
- Optional Discord notification when a lock occurs

This acts like a **circuit breaker** for restart automation.

---

## 📍 Local-only by design (important)

Restart Loop Guard tracks **restart attempts on the machine where it runs**.

Typical use cases:
- Server machine with auto-restart scripts
- Admin/control machine that triggers restarts (SSH, scripts, schedulers)
- AutomationZ OS or standalone AutomationZ tools

It does **not** monitor remote processes or servers by itself.

---


