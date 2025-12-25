# AutomationZ Restart Loop Guard  [![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/R6R51QD7BU)
[![Automation-Z-Restart-Loop-Guard-Dashboard.png](https://i.postimg.cc/yN2f0Wb6/Automation-Z-Restart-Loop-Guard-Dashboard.png)](https://postimg.cc/CZHHgM09)
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

## Credits

---
🧩 AutomationZ 
These tools are part of the AutomationZ Admin Toolkit:

- AutomationZ Mod Update Auto Deploy (steam workshop)
- AutomationZ Uploader
- AutomationZ Scheduler
- AutomationZ Server Backup Scheduler
- AutomationZ Server Health
- AutomationZ Config Diff 
- AutomationZ Admin Orchestrator
- AutomationZ Log Cleanup Scheduler
- AutomationZ_Restart_Loop_Guard

Together they form a complete server administration solution.

### 💚 Support the project

AutomationZ tools are built for server owners by a server owner.  
If these tools save you time or help your community, consider supporting development.
It does **not** monitor remote processes or servers by itself.

---


