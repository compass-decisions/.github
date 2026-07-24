<div align="center">

# Compass Decisions 

**Voice-first AI planning — turning spoken chaos into scheduled clarity.**

[![Status](https://img.shields.io/badge/status-active%20development-blue)]()
[![Platform](https://img.shields.io/badge/platform-PWA%20%7C%20mobile--first-informational)]()
[![Integrations](https://img.shields.io/badge/integrations-Google%20Calendar-brightgreen)]()
[![License](https://img.shields.io/badge/license-proprietary-lightgrey)]()

</div>

---

## About

Compass Decisions Team designs and builds AI-powered planning tools that remove the friction between *deciding what to do* and *actually doing it*. Our flagship product is a **mobile-first, voice-driven web application** that listens to a task, breaks it into small, concrete, time-estimated steps, and schedules it — with minimal effort from the user.

This team hosts the development of that product, built in partnership with our client, **Roberto**.

## What We're Building

The core loop is simple by design:

1. **Speak** — a voice prompt, a brain-dump of the day, or a vague goal ("finish the report by Friday and clean the garage").
2. **AI breaks it down** — complex or messy input is parsed into small, concrete, time-estimated chunks.
3. **Scheduled automatically** — chunks are written to the user's **Google Calendar** after a lightweight, one-tap confirmation. The calendar stays the system of record; we don't replace it, we organize around it.

Planned next: **Google Tasks** and **Google Classroom** as additional input/output sources, so the same chunking engine can pull from and write to more of where users already plan.

## Key Capabilities

| | |
|---|---|
| 🎙️ **Voice-first, touch-fallback** | Every core action is completable by voice; every voice action has a visible touch equivalent. |
| 🧠 **AI task chunking** | Turns unstructured, spoken goals into small, schedulable steps — not a rigid command syntax. |
| 📅 **Google Calendar sync** | Reads existing calendar context and writes new events, after confirmation. |
| 🔜 **Google Tasks & Classroom** | Planned integrations to widen input sources and sync targets. |
| 📲 **Progressive Web App** | Installable, mobile-first, with push notifications for reminders and schedule nudges. |
| ⚡ **Low-friction confirmation** | One tap or word before anything is written to the user's calendar — never a form. |

## Tech Stack

> Living reference — the authoritative, up-to-date stack lives in each repository's own README. This is the current high-level direction.

| Layer | Approach |
|---|---|
| Frontend | Mobile-first Progressive Web App |
| AI / Orchestration | LLM-based task parsing and chunking |
| Voice | Speech-to-text input, text-to-speech feedback |
| Calendar & Tasks | Google Calendar API (live), Google Tasks & Google Classroom APIs (planned) |
| Notifications | Web Push via the PWA |

## Roadmap

- [x] **Phase 1** — Product definition & UX/UI design
- [ ] **Phase 2** — Frontend build (responsive PWA)
- [ ] **Phase 3** — Google OAuth + Calendar integration, backend & data model
- [ ] **Phase 4** — AI pipeline (speech → structured chunks → schedule proposal)
- [ ] **Phase 5** — Production hardening: testing, monitoring, accessibility audit, beta

## Repositories

| Repository | Description |
|---|---|
| [`.github`](.) | This repository — organization profile and org-wide community health defaults |
| `app` | Main application (rename to match your actual repo) |
| `docs` | Product, architecture, and API documentation |

> Keep this table current — it's the fastest way for a new teammate or reviewer to orient.

## Contributing

This is a private client engagement. Team members should follow the branching strategy, commit conventions, and PR review process in [`CONTRIBUTING.md`](./CONTRIBUTING.md). Access to source repositories is by invitation only.

## Security

Please do not open a public issue for security concerns. See [`SECURITY.md`](./SECURITY.md) for our responsible disclosure process and contact.

## Contact

Maintained by the Compass Decisions Team. For project inquiries, open a discussion in this organization or reach out to the maintainers directly.

---

<div align="center">
<sub>© 2026 Compass Decisions Team. All rights reserved.</sub>
</div>
