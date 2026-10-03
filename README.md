# SellerPilot MVP

A browser-testable MVP for an e-commerce seller operations SaaS.

## Included
- Dashboard
- Profit calculator
- Product tracker
- Order/profit tracker
- RTO tracker
- Subscription pricing page
- Local browser storage demo
- PostgreSQL schema for a real backend

## Run locally
No build step is required.

1. Download/clone this repository.
2. Open `index.html` in a browser.

For GitHub Pages, push the files to a repository and enable Pages from the repository's Settings.

## Business model
- Free: acquisition and basic tools
- Pro: ₹199/month
- Annual: ₹1,999/year

The subscription buttons are intentionally demo-only. A production version needs:
- authenticated backend
- password hashing/session management
- payment gateway checkout
- server-side webhook verification
- subscription entitlement checks
- marketplace APIs or CSV imports
- backups, logging and privacy controls

## Suggested production stack
Frontend: Next.js/React
Backend: Node.js API
Database: PostgreSQL
Payments: Razorpay/Stripe (subject to business/account eligibility)
Hosting: Vercel/Render/Railway or equivalent

## Important
Do not put payment secrets or database credentials in frontend JavaScript.
