# Changelog

All notable changes to Dyad. Versions follow `MAJOR.MINOR.PATCH`.

## 1.0.0 — 2026-11-19

First release.

### Added
- Private group rooms joined with a room code and optional password, end-to-end encrypted (AES-256-GCM keys derived with PBKDF2).
- Serverless connections over WebRTC. Free public relays (WebTorrent trackers, Nostr, MQTT) carry only the encrypted handshake.
- Manual invites with codes and QR codes, for networks where relays are blocked.
- Mesh networking: members forward messages and handshakes for each other, so people who cannot link directly can still chat.
- Direct messages between two members, with their own key.
- Signed messages, so nobody can impersonate another member. Safety codes to verify each other in person.
- Replies, emoji reactions, editing, deleting, formatting, links, @mentions, typing indicators, read receipts and presence.
- History synced to members who join later.
- Local history on the device, with an optional passphrase lock that encrypts everything at rest.
- Encrypted backup export and import, auto-delete per room, erase all data.
- Search across rooms, a quick switcher, keyboard shortcuts, light and dark themes, accent colours, and a layout that works from phones to wide screens.
