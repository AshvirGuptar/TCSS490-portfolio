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

| Timestamp (UTC) | Tool / AI Model | Development Focus / Goal | Technical Intent & Summary |
| :--- | :--- | :--- | :--- |
| **2026-10-25 2:00PM** | Gemini | Project Structure | Evaluated artifact ideas against artifact 4 instructions. Selected client-side investment simulator with dynamic outputs that lined up with the needs of a known and trusted future user. Established single-file index.html architecture using Tailwind CSS and FontAwesome CDN, moved info to Claude for development. |
| **2026-10-28 8:00AM** | Claude Code | Debug / Updates | Coded client-side mathematical compounding growth logic ($PV$, $PMT$, $r$) executing dynamically on input events. Built milestone goal timeline estimator and year-by-year trajectory table breakdown. |
| **2026-10-28 9:00AM** | Claude Code | Added Features | Implemented bottom calculation helper panel providing Historical CAGR ($CAGR = (FV/PV)^{1/t} - 1$) and weighted Asset Allocation methods (Equities/Bonds/Cash) with auto-apply bindings to the main return slider. |
| **2026-10-28 9:00PM** | Claude Code | Added Features | Inflation-Adjusted Purchasing, Save Scenarios, Presets based on clients verbal requests for use case. |
| **2026-10-29 9:00PM** | Claude Code | Criteria Evaluation | Compliance & Constraints Checklist based on artifact 4 instructions and past artifact feedback. |

