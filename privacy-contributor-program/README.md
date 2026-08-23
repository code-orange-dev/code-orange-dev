# Code Orange Bitcoin Privacy Contributor Program v2

## Mission

Code Orange develops sustained Bitcoin privacy contributors — not students who simply finish a course or maximize pull-request counts.

The program is designed to move developers from protocol understanding to trusted participation in real open-source projects through a progression of reading, building, testing, reviewing, contributing, and eventually maintaining.

## North-star outcome

**Percentage of participants who remain meaningfully active in at least one Bitcoin privacy-related open-source project six months after structured training ends.**

PRs remain useful evidence, but they are one contribution type among many. Reviews, testing, issue investigation, technical research, documentation, maintainer communication, and sustained project ownership all count.

## The Code Orange developer pipeline

The Privacy Contributor Program is one part of a simple developer pipeline. People can join at the point that matches their experience.

```text
WORKSHOPS AND MEETUPS
        ↓
STUDY COHORTS
Bitcoin Dojo / rawBit / Decoding Bitcoin
        ↓
CODE REVIEW CLUB
Read, test, review, and discuss real Bitcoin work
        ↓
FELLOWSHIPS
Focused time, mentor support, and one project
        ↓
YOUR OWN GRANT OR ROLE
Independent contribution, project funding, or paid FOSS work
```

Privacy specialization, project rotations, and residency sit inside the study-cohort and Code Review Club stages. Participants can test out of prerequisites when they already show the required skills.

## Program phases

### Phase 0 — Discovery and selection

Community workshops remain the broad top of the funnel. They introduce Bitcoin privacy topics, identify motivated developers, and route technically ready participants toward the contributor pathway.

Admission to the advanced track is competency-based rather than attendance-based.

### Phase 1 — Privacy Engineering Foundations (4–6 weeks)

Goal: develop a reusable framework for reasoning about Bitcoin privacy rather than memorizing individual protocols.

Core framework:

**Adversary → Observations → Heuristics → Leakage → Mitigation → Trade-offs**

Participants study chain analysis, wallet privacy, transaction graph heuristics, network privacy, address reuse, change detection, coin selection, metadata leakage, privacy metrics, and protocol trade-offs.

Exit outcome: participants can analyze the privacy properties of a proposal they have not previously studied.

### Phase 2 — Protocol & Code Labs (8–10 weeks)

Each module connects protocol theory to production code:

**Protocol → specification/BIP → implementation → tests → open issues → active PR → review/contribution**

Candidate domains include:

- Silent Payments / BIP352
- Payjoin
- wallet privacy and coin selection
- Bitcoin Core wallet / node / P2P privacy
- Lightning privacy
- CoinJoin-related systems and research
- Fedimint/eCash privacy where relevant

The purpose is breadth with real code exposure, not shallow PR production.

### Phase 3 — Contributor Rotations (6–8 weeks)

Participants rotate through 2–3 projects and practice multiple contribution modes.

Every rotation uses the core loop:

**READ → BUILD → TEST → REVIEW → CONTRIBUTE**

A rotation may produce a code change, but valid proof-of-work also includes substantive review, issue reproduction, test coverage, benchmarks, design analysis, documentation, or technical discussion.

### Phase 4 — Contributor Residency (12–16 weeks)

Each participant selects one primary upstream project and prepares a Contributor Plan containing:

- project and subsystem focus;
- issues and historical PRs studied;
- maintainer priorities;
- review commitments;
- likely contribution areas;
- technical learning objective;
- communication cadence with mentor/upstream contributors.

The residency intentionally reduces classroom instruction. Participants should increasingly identify useful work themselves and interact directly with upstream projects.

### Phase 5 — Fellowship / Maintainer Bridge (3–6 months)

Fellowships are selective and support participants who demonstrate contributor maturity rather than high activity counts.

Selection considers technical depth, review quality, reliability, initiative, communication, response to feedback, upstream usefulness, independence, and sustained engagement.

The fellowship is not another course. It is funded time to become a serious contributor to a specific project.

### Phase 6 — Alumni retention (through 12 months)

Code Orange tracks contribution at 3, 6, and 12 months after structured training. Alumni can join monthly contributor calls, Review Clubs, mentor office hours, and grant/fellowship support.

The strongest alumni are encouraged to become reviewers, mentors, Review Club hosts, and maintainers for future cohorts.

## Contribution philosophy

We do not require a PR after every session.

Instead:

> Every technical module engages participants with a real open-source codebase and produces verifiable proof of work.

Valid contribution evidence includes:

- code authored or merged;
- substantive PR review;
- testing another contributor's PR;
- bug reproduction;
- issue investigation or triage;
- tests or fuzzing improvements;
- benchmarks;
- documentation;
- protocol/privacy analysis;
- technical discussion with maintainers;
- research that prevents an unnecessary or incorrect change.

Quality and usefulness matter more than raw counts.

## Review as a first-class contribution

The Code Orange Privacy Review Club is a recurring program component. Participants prepare real upstream PRs by checking out the branch, building it, running tests, reading relevant code and discussion, and preparing review notes.

Review progression:

1. **Reproduce** — build/test the change and report results.
2. **Explain** — accurately describe motivation and implementation.
3. **Challenge** — identify edge cases, missing tests, assumptions, or privacy concerns.
4. **Review** — provide substantive conceptual or code feedback upstream.
5. **Own** — independently review unfamiliar work and participate constructively with maintainers.

Participants who author substantial work are expected to also contribute through review and validation of others' work.

## Program-level success metrics

### 1. Contribution readiness

Percentage of participants who can independently build an unfamiliar project, navigate its code, understand an issue, test a PR, communicate upstream, and produce a useful review.

### 2. Meaningful upstream activity

Track contribution types separately:

- PRs authored / merged;
- PRs meaningfully reviewed;
- review discussions participated in;
- PRs built/tested;
- bugs reproduced;
- issues investigated/resolved;
- tests/fuzzing/benchmarks added;
- documentation;
- protocol/privacy research.

### 3. Contributor depth

Track repeat meaningful interactions with the same project and increasing scope/difficulty of work.

### 4. Retention

Measure meaningful activity at 3, 6, and 12 months after structured training.

### 5. Progression

Track fellows, grant recipients, regular reviewers, maintainers, OSS employment, mentors, and Review Club hosts.

## Upstream usefulness signal

Where practical, Code Orange asks upstream contributors a lightweight question:

> Would you like this contributor to continue working on your project?

Maintainer/upstream feedback is treated as a qualitative signal rather than a popularity score.

## Anchor-project strategy

The program favors depth over repository count.

```text
Explore 4–6 projects
        ↓
Rotate through 2–3
        ↓
Residency in 1 primary project
```

Anchor candidates should be chosen based on active maintenance, meaningful privacy-related work, mentor/reviewer capacity, issue availability, language fit, and healthy contribution practices. Candidate ecosystems include Bitcoin Core, rust-bitcoin, BDK, rust-payjoin/Payjoin, Silent Payments implementations/tooling, LDK/Lightning projects, peer-observer/network privacy tooling, and Fedimint where privacy work is relevant.

Code Orange should confirm priorities with upstream contributors before assigning work; the curriculum should follow real project needs rather than manufacture beginner PRs.

## Instructor → mentor transition

Early phases use instructors to teach protocol and codebase foundations.

Later phases use mentors who ask questions such as:

- What are you working on and why is it useful?
- What did upstream say?
- What evidence supports your approach?
- What alternatives did you consider?
- What review/testing have you done for others?
- What is preventing you from moving independently?

A successful program makes Code Orange staff progressively less necessary to the contributor's day-to-day work.

## Program principle

> Our goal is not to optimize for developers who can produce PRs. Our goal is to develop contributors whom upstream projects actually want to keep working with.

## Companion documents

- `CONTRIBUTOR_SCORECARD.md` - competency levels, evidence types, and progression indicators.
- `CURRICULUM.md` - the competency-driven curriculum and residency checkpoints.
- `REVIEW_CLUB.md` - preparation, facilitation, review progression, and upstream etiquette.
- `MEASUREMENT.md` - outcome, retention, and reporting framework.
- `OPERATING_STANDARD.md` - admission routing, maintainer-aligned project intake, progression gates, governance, and data integrity.
- `CONTRIBUTOR_PLAN_TEMPLATE.md` - individual residency plan and evidence portfolio.
- `COHORT_REPORT_TEMPLATE.md` - aggregate reporting at program completion and 3/6/12-month retention.
- `BTRUST_RESPONSE.md` - polished response to the Btrust follow-up.
