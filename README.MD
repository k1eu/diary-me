# k1eu Diary

This is a Diary repo that represents daily achievements of mine and a place to store them.

### 27/09/2023 - React Guild Meeting

This day we focused on Bun, what it brings to the table, and how easy it is to integrate into our workflow.

First impressions
- running ts out of the box ✅
- speed of CLI ⚡
- drop in replacement package manager
- Vercel, Expo quick support
- Vite integration - works but not perfectly

No.3 - you can try just dumping your package-lock and node_modules and try running `bun install` - appears to be working quiet unproblematic

No.4 - you can create/run/build the app through bun with vite transpiling, dev ESM - but by running it fully in BUN you loose HMR - they keep working on it to fully support it https://bun.sh/guides/ecosystem/vite

There's also an Express like library for Bun already which appears to be working without any issues on smaller cases https://github.com/lau1944/bunrest and is plenty fast!
