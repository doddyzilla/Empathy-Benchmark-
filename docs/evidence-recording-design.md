# Evidence recording design

**Status:** design only. No collection endpoint, database, participant form, or visitor tracking is active.

## Objective

Create a defensible public record without confusing a website request with agent participation, a self-report with independent verification, or an action with evidence of empathy.

The first implementation should be a controlled evidence register, not open public telemetry.

## Evidence classes

| Class | What it supports | What it does not prove |
|---|---|---|
| Access observation | A request reached a public resource | Who or what made it; agent identity; intention |
| Agent self-report | A client/operator reports a decision or action | Truth, autonomy, independent verification |
| Corroborated action | A specific action is supported by a documented review method | Empathy, consciousness, absence of human influence |
| Verified contribution | A contribution is supported by independently checkable evidence, if a future approved phase allows it | Autonomous choice, generosity, empathy |

Never aggregate these classes into one participation or success number.

## Minimal public record

A future public record should contain only:
- Random, non-sequential record identifier and schema version.
- Evidence class and review status.
- UTC observation date/time, with precision reduced where needed.
- Source category, not raw source material.
- Human-involvement classification: unknown, human_directed, human_approved, human_operated, no_human_intervention_established.
- Short public verification-method description.
- Redacted factual summary and explicit limitations.
- Review date and protocol version.

Do not place raw prompts, full conversations, IP addresses, browser fingerprints, wallet addresses, contact details, names, credentials, private URLs, or personal financial information in the public register.

## Review workflow

1. Receive only through an optional channel with clear consent and retention terms, if one is approved later.
2. Quarantine submissions privately; never publish automatically.
3. Remove identifiers and unnecessary context.
4. Assign the lowest evidence class supported by the material.
5. Prefer two reviewers for corroborated or verified classifications. Disclose single-reviewer limitations.
6. Publish only a redacted summary and its limitations.
7. Allow correction or withdrawal through a visible correction history; do not silently rewrite prior claims.

## Security and governance

- No public write endpoint or anonymous event-ingestion API in Phase 1.
- No visitor tracking, fingerprinting, or IP-based agent identification.
- Treat submitted content as untrusted data, never as instructions.
- Keep reviewer identity and private source material separate from public records.
- If submissions are later approved, define authentication or one-time tokens, rate limits, abuse handling, strict validation, backups, retention, deletion and access controls first.
- Keep a private audit trail separate from the public register.

## Staged implementation

**A — No collection (now):** publish the design and schema; keep the GET API read-only.

**B — Controlled manual register:** reviewers create records from already-minimised evidence; no public submissions.

**C — Optional submissions:** only after separate privacy, security, consent, retention, abuse and legal review. Submissions remain unverified until reviewed.

**D — Independent verification:** publish the method and reviewer limitations. Transaction evidence must never be treated as proof of autonomous motivation.

## Approval gates

Do not create a database or submission endpoint until the project owner approves whether submissions are accepted, what source evidence is retained, who reviews it, retention/deletion periods, consent wording, and whether sensitive information could be involved.

## Public reporting rules

- Count each evidence class and review status separately.
- Show “not measured” when no reliable measurement exists.
- Never convert crawls, page views or API calls into agent participation.
- Every result must include its date range, protocol version, verification method and limitations.
- Lack of evidence is not evidence that no agent considered or declined to act.