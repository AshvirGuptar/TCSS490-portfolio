# AI Interaction Log - TCSS 490

## Project: Course Portfolio (Artifact 1)
## Ashvir Guptar

---

### Entry 1: Portfolio Setup & Architecture
- **User Prompt:** "Build a simple layout for assignments in a card format using GitHub Pages that will be updated to host projects."
- **AI Action:** Created a single-file static `index.html` structure with Tailwind CSS, vanilla JavaScript and modal viewer.

### Entry 2: Branding & Course Alignment
- **User Prompt:** "Incorporate assignment names, course titles, updated artifact titles, and direct repo link."
- **AI Action:** Updated header metadata, badges, placeholder titles for artifacts 2-5, and linked Artifact 1 button to `https://github.com/AshvirGuptar/TCSS490-portfolio`.

### Entry 3: Summary Integration
- **User Prompt:** "Add a 2-sentence summary of what was built into Card 1."
- **AI Action:** Formatted a styled summary box inside Artifact 1 card detailing the responsive HTML/Tailwind web portfolio and dark mode support.

## Project: Password Generator Dashboard (Artifact 2)
# AI Prompt Log & Development Activity - Artifact 02

This document records the prompt engineering and development workflow utilized to build and deploy the Secure Password Generator dashboard for TCSS 490 (Artifact 02).

---

## Log Entries

| Timestamp (UTC) | Tool / AI Model | Development Focus / Goal | Technical Intent & Summary |
| :--- | :--- | :--- | :--- |
| **2026-10-11 21:00** | Gemini / ChatGPT | Feasibility & Architecture | Evaluated hosting requirements and confirmed client-side browser execution via GitHub Pages for the password generator. |
| **2026-10-11 21:10** | Gemini / ChatGPT | UI & Cryptographic Logic | Designed a responsive Tailwind CSS dashboard integrating `window.crypto.getRandomValues()` for secure character generation, a visual strength meter, and clipboard utilities. |
| **2026-10-11 21:20** | Gemini / ChatGPT | Real-Time State Binding | Implemented event listeners on sliders and configuration checkboxes for dynamic password updates upon user interaction. |

---

## Project: AI-Audited Secure Password Manager (Artifact 3)
# AI Prompt Log & Development Activity - Artifact 03

This document records the prompt engineering and development workflow utilized to design, build, and document the AI-Audited Secure Password Manager for TCSS 490 (Artifact 03).

---

## Log Entries

| Timestamp (UTC) | Tool / AI Model | Development Focus / Goal | Technical Intent & Summary |
| :--- | :--- | :--- | :--- |
| **2026-10-18 10:00** | Gemini | Project Structure | Worked with Gemini initially to build client-side secure vault logic using `localStorage` and designed UI layout for credential cards with Tailwind CSS. |
| **2026-10-19 13:00** | Claude Code (`claude -p`) / Gemini | Debug / Updates | Integrated CSV export functionality formatted for browser manager compatibility. Troubleshooting bugs with AI agent regarding array mapping and HTML string escaping for delete handlers. |
| **2026-10-19 15:30** | Gemini / Claude Code | Deployment | Refined auto-save vs. explicit generation triggers, resolving pre-population bugs on initial page load. Validated GitHub Pages deployment, tested local cache persistence, and finalized master portfolio updates and log entries. |

---

## Project: Investment Goal & Trajectory Calculator (Artifact 4)
# AI Prompt Log & Development Activity - Artifact 04
This document records the prompt engineering and development workflow utilized to build and deploy the Investment Portfolio Trajectory Simulator for TCSS 490 (Artifact 04).
## Log Entries

| Timestamp (LOCAL PST) | Tool / AI Model | Development Focus / Goal | Technical Intent & Summary |
| :--- | :--- | :--- | :--- |
| **2026-10-25 2:00PM** | Gemini | Project Structure | Evaluated artifact ideas against artifact 4 instructions. Selected client-side investment simulator with dynamic outputs that lined up with the needs of a known and trusted future user. Established single-file index.html architecture using Tailwind CSS and FontAwesome CDN, moved info to Claude for development. |
| **2026-10-28 8:00AM** | Claude Code | Debug / Updates | Coded client-side mathematical compounding growth logic ($PV$, $PMT$, $r$) executing dynamically on input events. Built milestone goal timeline estimator and year-by-year trajectory table breakdown. |
| **2026-10-28 9:00AM** | Claude Code | Added Features | Implemented bottom calculation helper panel providing Historical CAGR ($CAGR = (FV/PV)^{1/t} - 1$) and weighted Asset Allocation methods (Equities/Bonds/Cash) with auto-apply bindings to the main return slider. |
| **2026-10-28 9:00PM** | Claude Code | Added Features | Inflation-Adjusted Purchasing, Save Scenarios, Presets based on clients verbal requests for use case. |
| **2026-10-29 9:00PM** | Claude Code | Criteria Evaluation | Compliance & Constraints Checklist based on artifact 4 instructions and past artifact feedback. |
| **2026-11-03 4:00PM** | Claude Code | Added Feature | Added interactive Virtual Guide feature next to core financial inputs. Clicking an icon opens a concise modal assistant that explains complex terms like CAGR, inflation discounting, and compounding rates for users.|
| **2026-11-03 5:00PM** | Claude Code | Testing/Review | Coordinated with the team regarding finalized artifact version, received testing results from client to get feedback and confirmed that the artifact functions as intended.|
| **2026-11-03 8:00PM** | Client Hand-off | Testing | Confirmed with the client that the current version of our Portfolio Trajectory Simulator fulfills their needs while also collecting feedback on aspects such as UI, development timeline, and possible additions if development on the project continues.|


| Timestamp (LOCAL PST) | Tool / AI Model | Development Focus / Goal | Technical Intent & Summary |
| :--- | :--- | :--- | :--- |
| **2026-11-08 12:00PM** | Claude Code | Scaffolding | Set up the project foundation in Next.js 16, TypeScript and Tailwind, with GitHub Actions CI and deployment to Vercel. Wrote the first CLAUDE.md, PLAN.md and LOG.md so every session could pick up where the last ended. Defined the core architecture: a framework-free analysis engine where every check uses the same scoring format. |
| **2026-11-10 10:00PM** | Claude Code | Building | Built the Page Analyzer, Content Optimizer (with product specs), URL Optimizer, Site Audit crawler and Keyword Clusters. Added GEO scoring for AI search engines, PDF reports, Start over buttons, a redesigned homepage, and code-complete Google sign-in with saved project history. Tested everything with unit tests, browser tests and a phone/tablet sweep.|
| **2026-11-11 12:00AM** | Claude Code | Building/Documentation  | Rewrote PLAN.md as a justified Weeks 2–5 roadmap with deliverables, effort estimates, dependencies and risks. Updated CLAUDE.md with team workflow rules, the current-week process and guidelines for upcoming AI features. Added GEO Optimization alongside AI Visibility as coming-soon tools, and fixed a missing sidebar logo along the way.|

## Project: SEO & GEO Studio (Artifact 5)
# AI Prompt Log & Development Activity - Artifact 05
This document records the prompt engineering and development workflow utilized to build and deploy the SEO & GEO Studio for TCSS 490 (Artifact 05 Moonshot).
## Log Entries
| Timestamp (LOCAL PST) | Tool / AI Model | Development Focus / Goal | Technical Intent & Summary |
| :--- | :--- | :--- | :--- |
| **2026-11-08 12:00PM** | Claude Code | Scaffolding | Set up the project foundation in Next.js 16, TypeScript and Tailwind, with GitHub Actions CI and deployment to Vercel. Wrote the first CLAUDE.md, PLAN.md and LOG.md so every session could pick up where the last ended. Defined the core architecture: a framework-free analysis engine where every check uses the same scoring format. |
| **2026-11-10 10:00PM** | Claude Code | Building | Built the Page Analyzer, Content Optimizer (with product specs), URL Optimizer, Site Audit crawler and Keyword Clusters. Added GEO scoring for AI search engines, PDF reports, Start over buttons, a redesigned homepage, and code-complete Google sign-in with saved project history. Tested everything with unit tests, browser tests and a phone/tablet sweep.|
| **2026-11-11 12:00AM** | Claude Code | Building/Documentation  | Rewrote PLAN.md as a justified Weeks 2–5 roadmap with deliverables, effort estimates, dependencies and risks. Updated CLAUDE.md with team workflow rules, the current-week process and guidelines for upcoming AI features. Added GEO Optimization alongside AI Visibility as coming-soon tools, and fixed a missing sidebar logo along the way.|
| **2026-11-13 2:45PM** | Claude Code / Claude Opus 5.5 | Building (Week 4: AI Visibility) | Built AI Visibility v1: per-project prompt sets and tracked brands, runs that ask Claude (`claude-opus-5-5`, web search `web_search_20260209`, server-side refusal fallbacks) one prompt per request, a pure engine for mentions/rank/citations, share of voice and a 0–100 visibility score, trend chart, per-prompt answers with sources, CSV export, run history, and a weekly schedule through Vercel Cron (`vercel.json`, `CRON_SECRET`). Added the first slice of the Week 2 AI foundation it needs: `src/lib/ai/` (client, micro-dollar pricing, `ai_usage` logging, daily per-user and monthly budget caps, disabled-without-key). New tables in migration `0001_ai_visibility`. 21 new unit tests (117 total); verified the full run flow locally against a fake Claude server, no real API spend. Not yet run against the real API or on phones. |
| **2026-11-14 12:00PM** | Claude Code / Claude Opus 5.5 | API cost controls | Made AI spending safer before Week 2: default limits now $2 per person per day and $10 per month (matching the $10 credits), new `AI_MODEL` setting to test on cheaper Sonnet 5.5 or Haiku 5.5 while production keeps Opus 5.5, and web searches per AI Visibility question default to 2 (`AI_WEB_SEARCH_MAX_USES`). Per-model request options handle Haiku's differences, and cost estimates follow the chosen settings. Weekly runs remain off by default. |
| **2026-11-17 3:50PM** | Claude Code / Claude Opus 5.5 | Open mode (skip sign-in for now) | Team decided to skip Google sign-in for now and accept a public site. With only `DATABASE_URL` set, the app now runs in open mode: everyone acts as one shared Team user (`OPEN_MODE_USER`, created on first use), so Projects, Save to project and AI Visibility work without logging in; Team & access stays off; the daily AI limit becomes one shared limit (monthly cap unchanged). Guards (`requireActiveUser`, `requirePageUser`) return the Team user in open mode; `requireAdmin` requires real sign-in. Sidebar/home use `dataEnabled()`; setup notice now explains the database-only option. Adding the sign-in variables later switches back to per-person accounts automatically. 3 new tests (125 total); verified locally with no login against a fake Claude server (no real spend). Added the API-key and spending rules to Conventions. |
| **2026-11-17 6:00PM** | Claude Code / Claude Opus 5.5 | Email + password accounts (replaces Google requirement) | Google OAuth publishing needed a verified domain, so accounts now use email + password. Accounts turn on with `DATABASE_URL` + `BETTER_AUTH_SECRET`; Google stays optional. New sign-in page with Sign in / Create account tabs, Account page (change password, signs out other devices), admin Reset password on Team & access (one-time temporary password, revokes sessions), Refresh button on Access requested. Rate limits in a new `rate_limit` table (migration `0002`): sign-in 5/min, sign-up 5/10 min, password change 5/min. `AUTO_APPROVE_DOMAINS` now only trusts verified emails, so nobody can type a uw.edu address to skip approval. Revoked sessions now redirect to sign-in. 4 new tests (129 total) plus an 18-step browser run (admin/invited/pending sign-up, approve, duplicate and wrong-password messages, reset, rate limit, change password, iPhone SE layout). |
| **2026-11-17 7:00PM** | Claude Code / Claude Opus 5.5 | Free vs Premium tools | Tools that use the Claude API are now **Premium**: gold text and a crown in the sidebar and homepage (`--premium` token, `Crown`/`PremiumBadge`). Free tools are public by default (`PUBLIC_TOOLS=false` locks them). Signed-out visitors opening a premium tool see "only for approved users" with Sign in / Request access (the sign-up tab), and return to the tool afterwards; pending users can use the free tools and see a "waiting for approval" card on premium pages; Projects shows a "needs an account" card. Premium APIs still require an approved user. `premiumPageAccess()` in page-guard.ts, `PREMIUM_TOOL_PATHS` kept in sync with nav.ts by a test. New `APPROVED_EMAILS` env var: approved members on sign-up (for the professors testing). 132 tests; 14-step browser run (crown and gold colour, gate, request access, pending, approval, API 401, iPhone SE). |
| **2026-11-17 7:45PM** | Claude Code / Claude Opus 5.5 | Approval-based password reset | Replaced the admin temporary-password reset with a self-service request: "Forgot password?" on sign-in → the person gets a 4-character code → the request shows on Team & access with the same code → admin approves after checking it → the person's page updates by itself and asks for a new password, then signs them in. Only the browser that made the request can finish (secret token in localStorage, SHA-256 hash in the new `password_reset` table, migration `0003_password_reset`); approvals expire after 24h and are single-use; admins can't approve their own; 3 requests per account per day; unknown emails get an identical-looking response. 136 tests; 12-step browser run (code match, resume after reload, auto-update on approval, old password rejected, wrong token refused, no self-approval, iPhone SE). |
| **2026-11-17 8:30PM** | Claude Code / Claude Opus 5.5 | Email password-reset links | Added classic "Forgot password?" by email: Better Auth `sendResetPassword` + nodemailer 10 over SMTP (Gmail + app password via `SMTP_USER` / `SMTP_PASSWORD`, optional `SMTP_HOST` / `SMTP_PORT` / `EMAIL_FROM`), escaped HTML + text template (`src/lib/email/templates.ts`), new public `/reset-password` page (new + confirm password). Links last 60 minutes, work once, and sign out other devices; reset requests rate limited to 3 per 10 min. Unknown emails get the same "check your email" message. The admin-approved reset stays as the automatic fallback when email isn't configured. Proton `@proton.me` can't send via SMTP, so the team made a Gmail for the app. 139 tests; 14-step browser run against a local fake SMTP server (no real email sent). |
| **2026-11-17 9:15PM** | Claude Code / Claude Opus 5.5 | Fix "Invalid origin" on sign-up | Better Auth only trusted one address (BETTER_AUTH_URL or the production domain), so signing up from another of the project's Vercel addresses failed with "Invalid origin". New pure `src/lib/auth/origins.ts`: `authBaseURL()` (BETTER_AUTH_URL, else the branch URL on previews, else the production domain) and `authTrustedOrigins()` (base URL, production domain, this deployment's URL, its branch alias, plus optional `TRUSTED_ORIGINS`), and the address the request was sent to (`requestOwnOrigin`, same-site so safe). Outside sites are still rejected (checked: own address 200, other site 403). 6 new tests (145 total). |
| **2026-11-17 9:45PM** | Claude Code / Claude Opus 5.5 | Looser sign-in limits | Raised the sign-in limit to 10 per minute and sign-up to 10 per 10 minutes per IP (were 5), after the first real sign-ups hit the limit during the "Invalid origin" retries. |
| **2026-11-17 10:30PM** | Claude Code / Claude Opus 5.5 | UW-only accounts + no endless spinner | Team decision: only `@uw.edu` addresses can create accounts, and they get in straight away (no approval queue); the address itself is the "key" (deliberately simple, unverified). `SIGNUP_DOMAINS` (default `uw.edu`, `*` = anyone) with `canSignUp()` in access.ts, enforced in Better Auth's `user.create.before` hook with a clear "use your @uw.edu email" error; look-alikes like `x@uw.edu.evil.com` are blocked; `ADMIN_EMAILS` / `APPROVED_EMAILS` / invites stay as exceptions. Sign-in/sign-up form now gives up after 25 s with a message (the live sign-up was loading forever) and does a full page load after success instead of client-side navigation. 149 tests; 9-step browser run including a deliberately stuck server. |
| **2026-11-17 10:50PM** | Claude Code / Claude Opus 5.5 | Hide the domain in the UI | The sign-in page, form hints, placeholders and the sign-up error now say "your UW email" instead of printing "@uw.edu" (the domain is the "key", so it isn't shown). `signupLabel()` in access.ts (default "UW", `SIGNUP_LABEL` overrides). 149 tests; checked in a browser that no "@uw.edu" appears. |
| **2026-11-18 7:30PM** | Claude Code / Claude Opus 5.5 | AI Visibility check + report redesign | Checked AI Visibility end to end: Claude request settings match the current API (Opus 5.5, `web_search_20260209`, effort medium, `fallbacks: "default"` refusal fallback, `pause_turn` resume), cost math matches current prices, and a browser run against a local fake Claude server confirmed setup saving, one-prompt-per-request runs, paused-turn resume, usage logging, results reloading from the database and run history (no real API spend). Redesigned the results: score gauge with a word label and change vs last run, a one-line summary, share of voice, a new "Sites the AI cites" ranking, a question-by-brand coverage grid, a "Biggest openings" list (questions where competitors are named and you aren't), and the trend chart only once there are two runs. The run bar moved to the top and setup collapses to a summary once saved. New pure `src/lib/seo/visibility-insights.ts` (3 tests, 152 total). Checked on desktop and iPhone 14. |

