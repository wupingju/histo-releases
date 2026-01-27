# Changelog

All notable changes to Histo will be documented in this file.

---

## [0.4.1] - 2026-01-27

- Improve Fork feature with cleaner Markdown export and helpful token estimation
- Add help button explaining difference between Resume and Fork actions

---

## [0.4.0] - 2026-01-25

- Add Selection Mode for selecting and exporting conversation content at multiple levels (Session, Sub-session, Turn, or Message).
  - You can drag a selection box to select multiple objects, or click the "Select all" button to select all.
- Add Content Filter to filter conversation by message type (User, Assistant, Tool Use)
- Add Filter in the Search Panel to filter results by message type (User, Assistant)
- Tool use messages are filtered by default in the conversation view and search view to reduce noise.
- Fix search results showing duplicate messages when the same message exists in multiple sessions
- Fix search result preview only showing one message instead of the full conversation

---

## [0.3.0] - 2026-01-21

- Significantly improve overall performance, including launch speed, scrolling speed, responsiveness when clicking on sessions and sub-sessions, and any operations during sync.
- Redesign the color system with a refined, low-contrast palette for comfortable extended reading.
- Refine loading animation with smoother, more polished spinner.
- Simplify timeline interface for cleaner, more focused browsing experience.
- Simplify session header and remove sub-session banner for a more compact, focused view.
- Standardize all date and time displays to use consistent ISO-like format (yyyy-MM-dd HH:mm).
- Filter out duplicated sessions introduced by Claude Code to reduce timeline noise.
- Fix an issue where global search results could cause the app to freeze.
- Fix an issue where search result previews don't show the full conversation context.

---

## [0.2.2] - 2026-01-18

- Fix app freezing when multiple Claude Code sessions are running simultaneously

---

## [0.2.1] - 2026-01-18

- Improve iCloud sync integrity with automatic detection and repair of orphaned sessions
- View parent session for forked or continued conversations with one click

---

## [0.2.0] - 2026-01-17

- **[Important]** This update includes a data migration to support Claude Code v2.1.11's new features. Your sessions will be re-uploaded to iCloud to ensure cross-device sync works correctly.
- Support for session deeplinks. You can right-click on a session to copy its deeplink and use it in other products. Clicking the link will open a session preview, helping you get back to the context faster.
- Improve the error notifications users receive when iCloud storage is full, and enhance the retry experience.
- Fix issue where app would freeze when scrolling through long conversations.
- Fix blank screen that could appear after rapidly scrolling through conversations.
- Fix sync issue where sessions with shared message IDs would fail to load.

---

## [0.1.0] - 2026-01-15

🎉 Initial Public Release

---

## 💬 Feedback & Support

Questions or feedback? Reach out to us:

📧 **[support@histo.cc](mailto:support@histo.cc)**
