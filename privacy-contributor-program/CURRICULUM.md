# Privacy Contributor Program — Curriculum Blueprint

This is a competency-driven blueprint. Exact projects/PRs should be selected close to delivery based on active upstream priorities.

## Phase 1 — Privacy Engineering Foundations (6 weeks)

### Week 1 — Privacy threat modeling
Adversaries, observability, linkability, metadata, anonymity sets, threat-model boundaries.

**Proof of work:** threat model for a real Bitcoin workflow.

### Week 2 — Transaction graph privacy
Common-input ownership, change heuristics, address reuse, amount/timing leakage, clustering assumptions.

**Proof of work:** analyze a transaction flow and document which conclusions are evidence vs heuristic.

### Week 3 — Wallet privacy
Coin selection, UTXO labeling, change, address management, wallet-server leakage, scanning models.

**Proof of work:** code/test walkthrough of a wallet privacy behavior.

### Week 4 — Network privacy
P2P observability, transaction broadcast, Tor, peer behavior, timing/network metadata.

**Proof of work:** reproduce or analyze a network-privacy behavior using a real codebase/tool.

### Week 5 — Privacy protocol evaluation
Reusable framework: adversary → observations → heuristics → leakage → mitigation → trade-offs.

**Proof of work:** independent analysis of a protocol not previously taught in depth.

### Week 6 — Open-source privacy engineering
Specifications/BIPs, implementation archaeology, test strategy, responsible technical communication.

**Proof of work:** prepare and present a real privacy-relevant upstream PR for Review Club.

## Phase 2 — Protocol & Code Labs (8 weeks)

Each lab follows:

**specification → implementation → tests → historical issues/PRs → active work → contribution evidence**

### Lab A — Silent Payments
BIP352 concepts, scanning, implementation architecture, wallet integration and privacy trade-offs.

### Lab B — Payjoin
Transaction construction, receiver/sender roles, server models, implementation/testing and interoperability.

### Lab C — Wallet privacy
BDK/Bitcoin Core or other active wallet code: coin selection, labels, address/change behavior, privacy-oriented tests.

### Lab D — Network privacy
Bitcoin Core P2P/network code and/or peer-observation tooling; transaction propagation and metadata leakage.

### Lab E — Lightning privacy
Routing/payment privacy, gossip/graph leakage, probing and implementation trade-offs in active Lightning projects.

### Lab F — Privacy architectures
CoinJoin-related systems/research and Fedimint/eCash where technically relevant to current upstream work.

Labs can span more than one week; not every cohort needs every lab. Choose depth and active upstream opportunities over topic count.

## Phase 3 — Contributor Rotations (6–8 weeks)

Participants select 2–3 ecosystems. For each rotation they must demonstrate multiple contribution modes:

- read historical context;
- build the project;
- test a real PR/change;
- prepare a review;
- investigate an issue or test gap;
- contribute something useful where appropriate.

At least one rotation should produce meaningful review/validation evidence independent of authored code.

## Phase 4 — Residency (12–16 weeks)

No fixed weekly syllabus. Each participant maintains a Contributor Plan and weekly work log.

### Residency checkpoints

**Week 0:** project selection and upstream-context review.

**Week 2:** first useful upstream interaction and reviewed Contributor Plan.

**Week 4:** evidence across at least two contribution types (for example testing + review, review + code, issue investigation + tests).

**Week 8:** increasing independence; participant should be sourcing/scoping some work themselves.

**Week 12:** upstream usefulness review and continuation plan.

**Week 16 (where used):** fellowship/independent-contribution decision.

## Phase 5 — Fellowship (3–6 months)

Fellows focus on one project/subsystem. Expected work is defined with the contributor and, where possible, upstream collaborators.

Fellowship goals should describe outcomes and areas of ownership rather than PR quotas.

Examples:

- become a recurring reviewer of a subsystem;
- own testing/fuzzing improvements around a privacy feature;
- advance a significant protocol implementation;
- investigate and resolve a class of privacy/network issues;
- improve wallet privacy behavior with upstream-reviewed changes;
- develop enough project knowledge to mentor new contributors.

## Ongoing — Privacy Review Club

Runs biweekly across phases 2–5. See `REVIEW_CLUB.md`.

## Suggested participant workload

Structured foundations/labs: 5–8 hours/week including preparation.

Rotations: 8–12 hours/week.

Residency: 10–20 hours/week depending on cohort/funding.

Fellowship: defined according to funding and project needs.

## Curriculum design rule

Do not create upstream tasks solely because they are easy for students. Prefer current project priorities and real review/testing needs. When no appropriate code contribution exists, a substantive review, test report, issue investigation, research artifact, or documentation improvement is a valid outcome.