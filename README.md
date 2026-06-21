# Morning Brief — system notes

**Owner:** Stephanie Ludovici
A personal daily learning + awareness newsletter, generated automatically on weekdays at 6:00 AM
local time by a scheduled task. 

## What each edition contains
1. **AI governance & policy** — reputable-source news (NIST, OMB/White House, EU, academia, industry leaders).
2. **Cybersecurity & threats** — reputable-source news (CISA, NCSC, NVD, established threat-intel vendors, academia).
3. **Project status** — scans your projects under `Projects\`, leads with the most recently active, and gives a suggested next action.
4. **Five project ideas** — novel, expert-level deep-learning/science ideas (Python primary, R included, Julia where it fits), each with a problem statement, objective, method/approach, and estimated duration. Archived under `project-ideas\`.
5. **Four training items** — a Python lesson (PEP8-commented code), an R lesson, a data-centric lesson, and an AI algorithm/model/method — each long enough to actually learn from.
6. **Companion notebook** — one runnable `.ipynb` per edition (markdown + code + visualization) that *demonstrates* a model/method with explicit Modeling & Simulation (M&S) and Test & Evaluation (T&E) sections.

There is no email section, by Stephanie's standing instruction — the brief never scans, triages, or summarizes email, even if Gmail is connected. A calendar section is optional and appears only if Google Calendar is connected.

## Folders
- `YYYY-MM-DD-morning-brief.md` — the daily edition.
- `project-ideas\` — full idea write-ups (`YYYY-MM-DD-ideas.md`) plus `_ledger.md`, the master novelty index for manual review. *(Kept separate from your existing `Projects\Project Ideas` folder — move favorites over whenever you want to pursue one.)*
- `training-ledger.md` — novelty index of training topics already covered.
- `notebooks\` — the daily companion notebooks.

## Novelty guarantee
Each scheduled run reads `project-ideas\_ledger.md` and `training-ledger.md` first, excludes anything
already covered, generates new material, then appends to both ledgers. This is what keeps "new every
day" honest across runs that otherwise start with no memory of each other.

## Sources standard
Only reputable sources are used: government (e.g., NIST, CISA, OMB, EU institutions), academia
(peer-reviewed papers, arXiv preprints from established groups), and recognized industry leaders.
Every news item and training reference is linked.

## Notebook hygiene
Companion notebooks are local learning artifacts and are delivered with outputs cleared. If one ever
moves into a Git repo, clear outputs first, notebook output cells can
leak secrets.

## Publication numbering & news freshness (effective Publication No. 2)
- **Publication numbers.** Editions are numbered sequentially in `publication-ledger.md`. Each new edition's masthead reads `Morning Brief — Publication No. N — <weekday, date>`. The 2026-06-10 edition is **No. 1** and is kept as-is; the number appears in the masthead from No. 2 onward.
- **News freshness.** In the AI-governance and cybersecurity sections, strongly prefer items published in the **last 24–48 hours**, and **never include anything older than 3 weeks (21 days)**. If a section has no qualifying fresh item, say so briefly rather than padding with stale news. Continuously-updated reference pages (e.g., the NIST AI RMF or CISA KEV landing pages) may still be cited for context, but each *news item* must fall within the window.

### Paste-ready additions for the scheduled task (`SKILL.md`)
The scheduled task's `SKILL.md` governs live behavior and is read-only in the assistant session, so paste these in by hand:
- **Step 1 (date/masthead):** "Read `publication-ledger.md`; set this edition's number to the last number + 1. Set the masthead to `Morning Brief — Publication No. N — <weekday, Month D, YYYY>`. Append the new row to `publication-ledger.md` in Step 9."
- **Steps 3–4 (news):** "Only include news published within the last 3 weeks (21 days); strongly prefer the last 24–48 hours. If no qualifying item exists for a section, state that briefly instead of padding. Reference/landing pages may be cited for context, but each news item must itself fall within the window."

## Scheduling note
Scheduled tasks run only while the Claude desktop app is open. If the app is closed at 6:00 AM, the
edition is generated the next time the app is launched.
