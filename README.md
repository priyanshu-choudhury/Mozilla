# ⚡ CampusPulse: Encrypted Swipe-to-RSVP

Interactive Swipe-to-RSVP web app for campus events built for the Mozilla challenge.

## Live Demo
🔗 **[Play the Live App Here](https://priyanshu-choudhury.github.io/Mozilla/)**

## Features Implemented
- **Event Directory:** Curated campus events across Tech, Cultural, Sports, and Workshops.
- **Swipe Physics & Keyboard Controls:** Drag right (`I'm In`), drag left (`Skip`), or use `←` / `→` / `Ctrl+Z`.
- **Category Deck Filter:** Filter cards dynamically before swiping.
- **Bonus Features:** Multi-step **Undo Last Swipe** stack and live **1-second precision countdown badges** on RSVP'd events.
- **Zero-Trust Client Security:**
  - Non-extractable **256-bit AES-GCM** `CryptoKey` stored in `IndexedDB`.
  - Unique 96-bit IV generated per state write + **SHA-256** payload integrity verification.
  - Strict Content Security Policy (CSP) and XSS-safe DOM manipulation.
