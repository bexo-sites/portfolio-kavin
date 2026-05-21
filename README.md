# kavin's Portfolio

Live: https://kavin.mybexo.com

**Stack:** Next.js 14 (`output: 'export'`), Tailwind, Framer Motion.

| Path | Purpose |
|------|--------|
| `app/` | Routes (static export) |
| `components/` | Portfolio UI |
| `lib/` | `getPortfolioData()` reads `public/data.json` |
| `public/data.json` | Snapshot from BEXO profile |

**CI:** push to `main` runs `npm run build` and uploads `out/` to GCS.

Set repo variable **`PROFILE_ID`** = `82070c0b-204b-4063-ba2d-15b245c27106` (Settings → Secrets and variables → Actions).

Profile ID: `82070c0b-204b-4063-ba2d-15b245c27106`
