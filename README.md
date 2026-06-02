# CinderFox

CinderFox is a lightweight Firefox wrapper with AcreetionOS-style branding.

## Behavior

- Launches Firefox from `firefox`, `firefox-esr`, or `firefox-bin`
- Opens a themed Firefox home page when started without arguments
- Uses a dedicated profile with Firefox chrome styling enabled
- Ships a desktop entry and branded SVG icon

## Files

- `bin/cinderfox`
- `share/cinderfox/start.html`
- `share/cinderfox/profile/user.js`
- `share/cinderfox/profile/chrome/userChrome.css`
- `share/cinderfox/profile/chrome/userContent.css`
- `share/applications/cinderfox.desktop`
- `share/icons/hicolor/scalable/apps/cinderfox.svg`

## Arch package

Build and install with:

```bash
makepkg -si
```
---

## 🤖 Pullfrog AI Review

This repository uses **Pullfrog AI** to automatically review pull requests.

Pullfrog is an AI-powered code review agent that analyzes every PR for code quality,
security issues, performance problems, and best practice violations. Reviews appear
as inline PR comments and checks. Trigger manually by commenting `@pullfrog` on any PR.

Powered by OpenRouter.