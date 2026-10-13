# Patrick Pingue

IT support professional with 11 years of federal IT support experience (2015 - 2026) at DHS,
NIH, OIG and USPTO, working at Tier 2. I also build applied-AI tools that run on
local LLMs.

**Looking for:** remote Tier 1 / Tier 2 help desk, desktop support and IT
support roles.

## What I work with

- **Support:** Tier 2 escalations, Active Directory, Microsoft Intune,
  Office 365, ServiceNow
- **Certifications:** CompTIA Security+ (renewal in progress), Microsoft Azure Fundamentals (AZ-900)
- **Automation:** Python, scheduled tasks, health checks and small internal tools
- **Applied AI:** local LLMs through Ollama, with rules that keep the model's
  output checked and safe

## Projects

Small, self-contained tools. Each one has a README with real sample output and
tests you can run with `python -m unittest`.

| Project | What it does |
|---|---|
| [helpdesk-ticket-triage](https://github.com/PinguePatrick/helpdesk-ticket-triage) | Sorts help desk tickets by category and priority with first steps. Works offline; a local LLM can refine the answer but can never lower a security flag. |
| [service-watchdog](https://github.com/PinguePatrick/service-watchdog) | Keeps local services running: restarts only after repeated failed health checks, with backoff, a restart cap and a STOP file. |
| [port-audit](https://github.com/PinguePatrick/port-audit) | Compares a written port plan with what is really listening, and flags down, conflicting and unplanned listeners. |
| [secret-leak-guard](https://github.com/PinguePatrick/secret-leak-guard) | A git pre-commit check that blocks commits containing credentials, without printing the credential. |
| [archive-verify](https://github.com/PinguePatrick/archive-verify) | Finds reclaimable disk space and archives folders with SHA-256 proof that every file was kept. |
| [local-ci-runner](https://github.com/PinguePatrick/local-ci-runner) | Runs lint and tests on a schedule where hosted CI is not available, with a log line per run. |

## Guides I wrote

Short, practical guides on running AI locally, automation and AI for IT work: [alternativephusion2.gumroad.com](https://alternativephusion2.gumroad.com). Free starters: [Run AI on your own PC in 10 minutes](https://alternativephusion2.gumroad.com/l/nhxyuc) and [AI for Noobs](https://alternativephusion2.gumroad.com/l/vffssh).
