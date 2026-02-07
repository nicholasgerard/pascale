# Ensemble pour NY 2026

Campaign site for Pascale Richard.

- **Framework:** Astro
- **Hosting:** Cloudflare Pages
- **Domain:** ensembleny2026.org

## Development

```bash
npm install
npm run dev
```

## Deployment

Pushes to `main` trigger automatic deployment via GitHub Actions.

### Required GitHub Secrets

- `CLOUDFLARE_API_TOKEN` — Cloudflare API token with Pages edit permissions
- `CLOUDFLARE_ACCOUNT_ID` — Cloudflare account ID
