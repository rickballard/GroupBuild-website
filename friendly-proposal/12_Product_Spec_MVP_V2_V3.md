# Product Spec — MVP, V2, V3
## MVP — Detailed
- **Auth:** pseudonymous handles; local account or Discord OAuth without exposing PII.
- **RepTags (v1):** integer points from merged PRs, verified attendance, review helpfulness (curated).
- **Weighted Voting:** linear weight = base + f(reputation); simple, auditable math.
- **Briefs:** template library; AI-assisted generation; export to GitHub Issues.
- **ScriptTags:** tags on posts that trigger workflow hooks (e.g., create issue, label, deploy demo).
- **Demo Sandbox:** forum/chat with threads; ScriptTag buttons; sandbox banner to avoid confusion with prod.
- **Events:** minimal create/list; cohort invites; iCal export; reminders.
- **Resources Library:** Markdown pages with PR-driven improvements.
- **Donations:** UI slider (placeholder), integrate later with Stripe/Patreon/OpenCollective.

## V2 — Detailed
- **Reputation v2:** topic-scoped (health/safety/policy/dev), damping for brigades, decay over time.
- **Summaries & Trails:** threaded convos + AI summaries linked to briefs.
- **Analytics:** cohort and funnel dashboards; A/B copy experiments.
- **Integrations:** Discord/Matrix bridges; webhooks; mobile PWA.
- **Resilience:** mirror button, static fallbacks, IPFS doc mirrors.

## V3 — Exploration
- **Connectivity Assurance:** mesh/backhaul experiments; field gateways; hardware dongles feasibility study.
- **Attestations:** optional on-chain proofs of attendance/contribution.
- **Simulation:** event flow modeling and safety staffing calculators.