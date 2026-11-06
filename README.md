# Franquen LCARS

Countdown: 6 November 2026, 09:15 CET.

Shared statuses live in status.json. Anyone can read them. To edit, use CONNECTER GITHUB and enter a fine-grained token limited to this repository with Contents read/write. The token stays in page memory, is sent only to api.github.com, and is cleared on reload. Each editor must have repository write access. Never commit a token.

The page polls every 65 seconds and on returning to the tab. Concurrent edits retry against the latest file SHA. Failed updates show an error rather than a successful local-only state.

GitHub Pages deployment uses Actions. If automatic enablement fails, choose Settings → Pages → Source → GitHub Actions, then rerun Publish countdown.
