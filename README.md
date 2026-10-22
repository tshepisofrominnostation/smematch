# SMEMatch — Tender Match for Township SMEs

A marketplace that matches South African township SMEs to tenders they actually qualify for, with an explainable eligibility check per tender: every match shows which requirements are met, missing, or waivable — in plain language.

**Sprint site:** https://tshepisofrominnostation.github.io/smematch/

## Team (4)
| Role | Name | Focus |
|---|---|---|
| Scrum Master / Developer | Tshepiso Freddy Thosago | Process, eligibility engine, delivery |
| Developer | *(to be added)* | SME profiles + data layer |
| Developer | *(to be added)* | Tender ingestion + parsing |
| QA / Documentation | *(to be added)* | Test gate, docs, demo assets |

## Why it matters
Township SMEs miss tenders they could win because tender notices are dense, scattered, and written in procurement language. SMEMatch turns a tender into a checklist a business owner can read, and turns their profile into an honest answer to "do I qualify?" — before they spend a cent on the bid.

## Capabilities
1. SME profiles: registration details, CIPC status, B-BBEE level, tax compliance, experience, categories
2. Tender ingestion: paste a tender notice, extract structured requirements
3. Explainable eligibility: met / missing / waivable per requirement, with plain-language reasons
4. Match list: tenders you actually qualify for, sorted by deadline and fit
5. Tracking: saved tenders, deadline alerts, application tracker

## Scrum setup
- Sprint 0: Thu 22 – Fri 23 Oct 2026 (2-day starter sprint)
- Sprint 1: Mon 26 Oct – Fri 6 Nov (weeks 2+3)
- Sprint 2: Mon 9 – Fri 20 Nov (weeks 4+5)
- Sprint 3: Mon 23 Nov – Fri 11 Dec (weeks 6+7+8)
- Retrospectives live in docs/retrospectives/ — one file per sprint, filled at each Friday review.

## Setup
git clone https://github.com/tshepisofrominnostation/smematch
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
streamlit run src/app.py

## Adding teammates
Settings → Collaborators → Add people (write access), or send usernames to the repo owner for API invites.
