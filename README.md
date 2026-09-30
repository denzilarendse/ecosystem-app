# CareerLaunch SA

CareerLaunch SA is a mobile-first South African career support PWA and Android app. It provides secure candidate profiles, truthful ATS-focused career workflows, verified opportunity discovery, and application support.

## Release discipline

No security or release gate is considered passed without execution evidence. Production data is protected by Supabase RLS and the browser uses only a publishable key.

## Commands

- `npm run check`
- `npm test`
- `npm run build`

Android builds target API 36 and are produced by GitHub Actions from the same verified web bundle.
