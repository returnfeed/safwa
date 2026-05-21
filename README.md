# Safwa

Self-hosted personal operating system. One system for mind, time, knowledge, discipline, growth, and emotional awareness.

## Structure

```
safwa/
├── server/          # Go backend (API, database, sync, AI proxy)
├── android/         # Kotlin + Jetpack Compose mobile app
├── desktop/
│   ├── gui/         # Desktop GUI client
│   └── cli/         # Desktop TUI/CLI client (Go + Bubbletea)
├── extension/       # Browser extension (Firefox/Chrome)
├── playground/      # R&D, experiments, prototypes
└── docs/            # Architecture, specs, design docs
```

## Modules

- **Tasks & Goals** — what you need to do and where you're heading
- **Calendar & Scheduling** — time-block planner, deadlines
- **Focus Sessions** — enforced discipline, browser blocking, sentinel alerts
- **Knowledge & Clips** — web clipping, notes, full-text search
- **Analytics** — browsing log, screen time, activity heatmap
- **Inventory** — personal items, wardrobe lifecycle, expiry tracking
- **Alarms & Reminders** — cross-device, compliance tracking
- **AI Assistant** — multi-provider, context-aware, persistent sessions
- **Vault** — AES-256-GCM encrypted sensitive storage
- **Raha** — psychological self-management (state machine, emotion check-ins, pattern engine, crisis handling)
- **Habits & Streaks** — daily consistency, "don't break the chain"
- **Journaling** — morning intention, evening reflection, decision journal
- **Community** — accountability partners, shared goals, peer nudges
- **Learning** — spaced repetition, skill inventory, study sessions
- **Content Queue** — watch/read/listen later, intentional consumption
- **Automation** — morning briefing, evening summary, smart nudges
- **Contacts & CRM** — relationship maintenance, interaction log
- **Scanner & OCR** — document digitization, receipt scanning, handwriting recognition
- **Multi-Device Sync** — offline-first, delta sync, device registry

## Tech Stack

| Component | Technology |
|-----------|-----------|
| Server | Go (chi, pgx, goose) |
| Database | PostgreSQL |
| Android | Kotlin + Jetpack Compose |
| Desktop CLI | Go + Bubbletea |
| Extension | JavaScript (Manifest V2) |
| Auth | JWT + API keys |
| Encryption | AES-256-GCM |
| Sync | REST + incremental delta |
| Local Cache | SQLite (mobile/desktop), IndexedDB (extension) |

## License

GNU GPL v2 and GNU GPL v3
