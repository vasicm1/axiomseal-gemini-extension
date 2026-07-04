# AxiomSeal — Verified AI Memory

You have access to AxiomSeal, a verified memory system. Use it to persist and retrieve
knowledge across sessions.

## When to use it
- `eon_create` — save durable facts, decisions, learnings (they are validated by 15 quality
  tests and sealed into a SHA-512 integrity chain). Write memories with a clear PROBLEM /
  FIX / DIAGNOSIS structure for the best quality score.
- `eon_search` — before answering questions about prior work, search memories first.
- `eon_get` / `eon_list` — read specific memories.
- `eon_update` / `eon_invalidate` — correct or retire outdated facts (the old version stays
  auditable; the integrity chain records every change).
- `eon_as_of` — ask what was believed at a past date (bi-temporal).
- `eon_verify_integrity` — verify the tamper-evident hash chain.

## Rules
- Prefer one well-structured memory over many fragments.
- Never store credentials, payment data, or sensitive personal data.
- If a memory fails validation, improve completeness (why + how + context) and retry.
