```markdown
# Rolla MVP Web App (scaffold)

This repo contains a minimal front-end scaffold for the Rolla MVP web app:
- Modal route pattern for transaction detail (/tx/:id)
- Pay wizard with query param hydration (/pay)
- KYC guard and 2FA gating placeholders
- Multi-page skeletons: Home, Wallet, Virtual Account, Card, More, Services, Search
- Toast notifications and telemetry stubs
- Basic types and mock data

How to use
1. Create a new React + TypeScript project (Vite or CRA)
2. Copy `src/` files from this scaffold into your project
3. Install dependencies: react-router-dom, react-icons, date-fns, and any UI library you prefer
4. Implement backend API adapters and auth

Notes and next steps
- Replace mock data fetches with real API calls (with caching & error handling)
- Implement 2FA modal and session gating for sensitive reveals
- Implement PDF generator for Virtual Account instructions
- Add telemetry backend integration (PostHog/Segment)
- Add tests and performance instrumentation
```
