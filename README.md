# Craftsman Building & Renovations — digital presence

Working files for Craftsman Building & Renovations (Lynchburg, VA) — website, SEO, Google presence, and monthly reporting.

**Site:** [craftsmanhomesva.com](https://craftsmanhomesva.com)  
**Hub:** [odd-even.github.io/craftsman](https://odd-even.github.io/craftsman/)  
**Password:** `Craftsman2026`

## Folder map

| Path | Purpose |
|------|---------|
| `drop/` | Inbox for full-size screenshots. Say **process drop** |
| `_assets/` | Filed screenshots |
| `reports/` | HTML client reports (encrypted copies published) |
| `reports/src/` | Editable plaintext (private workspace only) |
| `monthly-reports/` | Markdown drafts |
| `tracker.md` | What’s active, blocked, done |
| `activity-log.md` | Dated log that feeds the monthly report |
| `client.md` | Who this client is and which sources to use |

## Publish

```bash
STATICRYPT_PASSWORD='Craftsman2026' ./scripts/encrypt-reports.sh
```

Then push the encrypted hub to the public Pages repo.
