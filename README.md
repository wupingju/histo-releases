# Histo

A native macOS app for browsing, searching, and analyzing your Claude Code conversation history.

> See every key decision across all your projects on a single timeline. Instantly reconnect with your train of thought.

[![macOS 14+](https://img.shields.io/badge/macOS-14%2B-blue)](https://github.com/wupingju/histo-releases/releases)
[![Latest Release](https://img.shields.io/github/v/release/wupingju/histo-releases)](https://github.com/wupingju/histo-releases/releases/latest)

---

## Why Histo?

When you work with Claude Code, valuable conversations—where you clarify intentions, explore ideas, and make decisions—are scattered across projects and time. Histo brings them together so you can:

- **Find pivotal moments** — Locate conversations where ideas and decisions were forged
- **Learn from patterns** — Review successful prompts to reuse; recall failures to avoid
- **Resume your context** — Pick up exactly where you left off, without re-explaining everything

---

## Features

### Cross-Project Timeline

Browse all your projects at once, or focus on one.

- Chronological view of every session
- Filter by turn count to surface meaningful conversations
- One click to jump into full conversation detail

### Intelligent Conversation Display

Read conversations the way they were meant to be read.

- **Turn grouping** — Consecutive messages from the same role are merged for clarity
- **Sub-Session splitting** — Long conversations are divided by git commits for quick navigation
- **Collapsible tool calls** — Focus on dialogue first; expand tool details when needed
- **Rich content** — Code blocks, diffs, images, Markdown, shell output

### Global Search

Find anything, anywhere, in any language.

- Full-text search across all conversations
- Multilingual support
- Dual-pane preview with direct jump to matched passage

### Resume & Fork

Continue where you left off—or start fresh with just the context you need.

- **Resume** — Return to the original session
- **Fork** — Extract key discussion points into a new Claude Code session

### Cross-Device Sync

A conversation on one Mac appears on another within seconds.

- Real-time sync via iCloud
- On-demand download (metadata syncs first, full content on click)
- Incremental updates only

### Local-First & Private

Your data stays on your devices and your iCloud. Never on third-party servers.

- Zero sign-up required
- Zero tracking or analytics
- Works offline

### Safe & Non-Invasive

Histo never modifies your original `.claude` files.

- Read-only access to your `.claude` folder
- All caches stored in a separate SQLite database
- Automatic backup of original data

---

## Installation

### Download

Download the latest `.dmg` from [Releases](https://github.com/wupingju/histo-releases/releases/latest).

### Requirements

- macOS 14.0 (Sonoma) or later
- Apple Silicon or Intel Mac

### First Launch

1. Open the `.dmg` and drag Histo to Applications
2. Launch Histo
3. Grant read access to your Claude Code data directory when prompted
4. Your conversations will be indexed automatically

---

## Plans & Pricing

### Basic (Free)

- iCloud sync
- Unlimited sessions
- Access to conversations from the last 30 days
- Search within the last 30 days

### Pro

- **No time limits** — Full access to your entire conversation history
- AI analysis features (coming soon)

### Pro Pricing

| Phase | Price | Notes |
|-------|-------|-------|
| Alpha (current) | **Free** | All Pro features unlocked |
| Early Bird | $29 | One-time, includes 1 year of updates |
| 1.0 Release | $39 | One-time, includes 1 year of updates |

*Histo is currently in alpha. All Pro features are free during this period.*

---

## Roadmap

### Planned

- [ ] Local LLM support for conversation analysis
- [ ] Advanced search filters
- [ ] Full keyboard shortcut support
- [ ] Export selected messages as PDF
- [ ] Internationalization (i18n)

### Under Consideration

- [ ] Mobile companion app (read-only)
- [ ] Usage statistics and insights
- [ ] Cloud AI model integration (BYOK only)

---

## Data & Privacy

Histo is designed with privacy as a core principle:

| Aspect | How Histo Handles It |
|--------|---------------------|
| **Data storage** | Local SQLite database + your iCloud |
| **Original files** | Read-only, never modified |
| **Account required** | No |
| **Analytics/tracking** | None |
| **Third-party servers** | None |

Your conversation data never leaves your devices and iCloud account.

---

## Support

- **Email**: [support@histo.cc](mailto:support@histo.cc)
- **Website**: [building]
