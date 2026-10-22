# SMEMatch Sprint Plan

Four sprints, Thu 22 Oct to Fri 11 Dec 2026. The original 8-week outline is compressed per the team's decision: a 2-day starter sprint now, then weeks 2+3, 4+5, and 6+7+8 combined.

Stand-up daily 08:30 (15 min). Midday checkpoint 12:30. Push by 16:00. Review + retro Friday 15:00.

## Roles
- **Scrum Master / Developer — Tshepiso:** process, blockers, eligibility engine
- **Dev 1:** SME profiles + data layer
- **Dev 2:** tender ingestion + parsing
- **QA / Docs:** test gate, documentation, demo assets

## Sprint 0 (Thu 22 – Fri 23 Oct): Starter — setup and discovery
**Sprint goal:** team aligned, repo live, data model agreed, fixtures seeded.

| Day | Focus |
|---|---|
| Thu PM | Sprint planning, roles, working agreement, repo setup |
| Thu PM | Data model: SME profile + tender schemas; eligibility factors agreed (CIPC, B-BBEE, tax, years trading, category) |
| Fri AM | Fixtures: 5 SME profiles + 10 tender notices with requirements |
| Fri PM | Skeleton app runs; review + retro 15:00 |

**Done when:** schemas documented, fixtures merged, app skeleton runs, retro-0 file filled.

## Sprint 1 (Mon 26 Oct – Fri 6 Nov): Profiles + tender ingestion
**Sprint goal:** an SME can register a profile; a tender can be pasted in and parsed.

- SME profile CRUD + completeness scoring (Dev 1)
- Tender ingest: paste notice text (Dev 2)
- Tender parser: deadline, category, B-BBEE minimum, experience required, tender value (Dev 2 + SM)
- Parser verified against the 10 fixture tenders (QA gate)
- Review + retro Fri 6 Nov

## Sprint 2 (Mon 9 – Fri 20 Nov): Eligibility engine + explainability
**Sprint goal:** "Do I qualify?" answered with evidence, per tender.

- Hard eligibility: CIPC registration, B-BBEE minimum, tax compliance pin (SM + Dev 1)
- Soft scoring: experience, capacity, category fit (SM)
- Explainable output: met / missing / waivable per requirement, plain-language reasons (Dev 1 + Dev 2)
- Match list per SME: tenders you qualify for, sorted by deadline
- Test gate: 10 SME×tender cases with expected outcomes (QA)
- Review + retro Fri 20 Nov

## Sprint 3 (Mon 23 Nov – Fri 11 Dec): Dashboard, tracking, deploy, showcase
**Sprint goal:** a deployed, documented, demo-ready marketplace.

- Dashboard: match stats, upcoming deadlines, coverage (Dev 1)
- Saved tenders + application tracker (Dev 2)
- Deadline alerts (in-app or email) (Dev 2)
- Deploy + smoke test (All)
- Documentation, user guide, business case deck + backup demo video (QA + SM)
- Final showcase + retro + handover Fri 11 Dec

## Descope order under pressure
1. Soft scoring sophistication (keep hard requirements)
2. Deadline alerts (keep saved tenders)
3. Application tracker (keep match list)
Never cut: eligibility engine, explainability, deployment, documentation.

## Risks
| Risk | Response |
|---|---|
| Tender parsing is the hard part | Fixtures first; parser has 2 full weeks (sprint 1); manual override in UI |
| Sprint 3 carries 3 original weeks | Deploy by Wed of week 2 of sprint 3; docs continue in parallel |
| Eligibility rules wrong = false hope | Every requirement shows its source text from the tender |
| Team availability (studies/work) | 5-8 stories per sprint max; scope cut at midday checkpoint |
