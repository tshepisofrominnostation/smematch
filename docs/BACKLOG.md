# SMEMatch Product Backlog

Ordered by value. Full sprint backlog — mirrored as GitHub Issues with per-sprint milestones.

## Sprint 0 — Starter (Thu 22–Fri 23 Oct)
| # | Story | Pts |
|---|---|---|
| S0-1 | Sprint planning: roles, working agreement, stand-up time | 1 |
| S0-2 | Repo setup: branches, PR flow, requirements, Streamlit skeleton | 1 |
| S0-3 | Data model: SME profile + tender schemas documented | 2 |
| S0-4 | Eligibility factors agreed: CIPC, B-BBEE, tax, years trading, category | 1 |
| S0-5 | Fixtures: 5 SME profiles + 10 tender notices in data/ | 2 |
| S0-6 | Sprint 0 review + retro file filled | 1 |

## Sprint 1 — Profiles + ingestion (Mon 26 Oct–Fri 6 Nov)
| # | Story | Pts |
|---|---|---|
| S1-1 | SME profile CRUD (register, edit, view) | 3 |
| S1-2 | Profile completeness scoring | 1 |
| S1-3 | Tender ingest: paste notice text | 3 |
| S1-4 | Tender parser: deadline, category, B-BBEE min, experience, value | 5 |
| S1-5 | Tender store + list view | 2 |
| S1-6 | Parser test gate on 10 fixtures | 2 |
| S1-7 | Review + retro + demo | 1 |

## Sprint 2 — Eligibility + explainability (Mon 9–Fri 20 Nov)
| # | Story | Pts |
|---|---|---|
| S2-1 | Hard eligibility: CIPC, B-BBEE minimum, tax compliance | 5 |
| S2-2 | Soft scoring: experience, capacity, category fit | 3 |
| S2-3 | Explainable output: met/missing/waivable + plain-language reasons | 3 |
| S2-4 | Match list per SME sorted by deadline | 3 |
| S2-5 | Test gate: 10 SME×tender cases with expected outcomes | 3 |
| S2-6 | Review + retro + demo | 1 |

## Sprint 3 — Dashboard, tracking, deploy (Mon 23 Nov–Fri 11 Dec)
| # | Story | Pts |
|---|---|---|
| S3-1 | Dashboard: match stats, upcoming deadlines | 3 |
| S3-2 | Saved tenders + application tracker | 3 |
| S3-3 | Deadline alerts | 2 |
| S3-4 | Deploy + smoke test | 3 |
| S3-5 | Documentation + user guide | 3 |
| S3-6 | Business case deck + backup demo video | 3 |
| S3-7 | Final showcase + retro + handover | 1 |

## Parking lot
- LLM-assisted tender summarisation
- CIDB/Construction-specific extensions
- Multi-language (isiZulu, Sesotho) eligibility explanations
- Procurement officer view (publish tenders)
- Integration with eTenders / SA government tender feeds
