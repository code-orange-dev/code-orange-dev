# Code Orange Privacy Review Club

## Purpose

The Privacy Review Club develops contributors who can understand, test, critique, and discuss real upstream work. Code review is treated as a first-class open-source contribution and a core route to deeper codebase understanding.

## Cadence

Recommended: every two weeks during the specialization, rotations, and residency phases.

One real active or recently active upstream PR is selected per session. Prefer work that is privacy-relevant, scoped enough for preparation, and useful to the upstream project.

## Before the session

Participants should:

1. read the PR description, linked issue/specification, and discussion;
2. check out the branch;
3. build the project/change;
4. run relevant tests;
5. locate the changed subsystem and surrounding code;
6. inspect related historical PRs/issues when useful;
7. prepare written review notes;
8. identify at least one question, assumption, test case, or design trade-off worth discussing.

## Session format (90–120 minutes)

### 1. Context — 10 minutes
What problem is being solved? Why does the project care?

### 2. Participant explanation — 15 minutes
Participants, not the instructor, explain the approach and relevant code paths.

### 3. Test evidence — 15 minutes
Compare build/test results, reproduction steps, platforms and unexpected behavior.

### 4. Conceptual review — 25 minutes
Discuss architecture, assumptions, privacy/security properties, alternatives and scope.

### 5. Code/test review — 25 minutes
Inspect implementation details, edge cases, test coverage and failure modes.

### 6. Upstream action — 10 minutes
Decide what feedback is genuinely useful upstream. Participants should not post comments merely to satisfy a program requirement.

## Review progression

### Level 1 — Reproduce
Build/test the PR and report reliable results.

### Level 2 — Explain
Accurately explain motivation, implementation and affected subsystem.

### Level 3 — Challenge
Identify an edge case, missing test, unclear assumption, privacy concern or alternative.

### Level 4 — Review
Provide substantive conceptual/code feedback and participate in follow-up discussion.

### Level 5 — Own
Independently select and review unfamiliar work and become a reliable reviewer in the project.

## Review quality principles

- Understand before commenting.
- Test claims when possible.
- Separate questions from objections.
- Explain reasoning, not only conclusions.
- Respect maintainer/project norms.
- Do not manufacture feedback for metrics.
- A clean test report can be valuable review work.
- 'I found no issue after checking X/Y/Z' is useful when backed by evidence.
- Withholding a low-quality comment is better than generating noise.

## Facilitator responsibilities

The facilitator should select suitable PRs, prepare context, ensure participants do the reasoning, correct misconceptions, prevent low-signal upstream comments, and record learning evidence.

The facilitator should not turn Review Club into a lecture or dictate review comments for participants to paste upstream.

## Evidence captured

For each participant/session record:

- PR reviewed;
- build/test status;
- review preparation completed;
- codebase areas understood;
- review observations;
- upstream comment/discussion URL if applicable;
- review competency level demonstrated;
- next learning target.

## Relationship to authorship

Participants who author substantial PRs should also review or validate other contributors' work. The goal is to develop reciprocal project participants rather than developers focused solely on getting their own patches merged.

## Upstream etiquette

Review Club is a learning environment; upstream repositories are not classrooms. Only feedback that is genuinely useful should be posted publicly. Learning notes, incorrect hypotheses, and exploratory questions can remain inside Code Orange until participants have enough confidence/context to engage upstream constructively.