# Mission Control HQ

A local-first Bikfix GTM operating dashboard. It keeps prospect evidence, qualification uncertainty, outreach review, feedback, pipeline state, agent handoffs, and artifacts in one place.

## Run

```bash
npm install
npm run dev
```

## Data provenance and safety

- `data/prospect-roster.md` is the 50-account research roster dated 17 September 2026.
- `data/outreach-batch-01.md` is the first 10-message review batch.
- Outreach is review-only and unsent. The UI deliberately has no sending integration.
- Qualification gaps remain explicit. Tier A requires evidence for 10+ managed client sites, client-level Cloudflare use, and a usable contact route.
- No credentials or secrets are stored.

## Build

```bash
npm run build
```
