# AxiomSeal — Gemini CLI Extension

**Verified AI memory with cryptographic integrity.** Every memory your agent stores is
validated by 15 quality tests, ethically scored, and sealed into a per-tenant **SHA-512
hash chain** — tamper-evident, auditable, bi-temporal. EU/Swiss hosted, GDPR-compliant.

## Install

```bash
gemini extensions install https://github.com/vasicm1/axiomseal-gemini-extension
```

## Setup (2 minutes)

1. Get an API key: sign up at [axiomseal.com](https://axiomseal.com) → Dashboard → Settings → API.
2. Export the key before starting Gemini CLI:

```bash
export AXIOMSEAL_API_KEY="eon_..."
gemini
```

That's it — Gemini now has 30 memory tools (`eon_create`, `eon_search`, `eon_verify_integrity`, …).

## Try it

```
> Save a memory: our staging cluster moved to eu-west on July 1st.
> What do my memories say about staging infrastructure?
> Verify the integrity of my memory chain.
> What did we believe about staging as of June 1st?   # bi-temporal
```

## What makes AxiomSeal different

| Feature | What it means |
|---|---|
| 15 validation tests | No junk memories — completeness, actionability, technical depth are scored on every write |
| SHA-512 integrity chain | Every memory is sealed; any tampering is detectable (`eon_verify_integrity`) |
| Bi-temporal queries | "What did we believe on date X?" — knowledge with history (`eon_as_of`) |
| Ethics scoring | Every write gets a coherence/ethics score (proprietary black-box) |
| Tenant isolation | Your data lives in its own database, EU/Swiss hosted |

## Links

- Website: https://axiomseal.com
- Docs: https://axiomseal.com/docs
- All tools: https://axiomseal.com/mcp
- Privacy: https://axiomseal.com/privacy · Support: https://axiomseal.com/support

## License

The extension manifest and docs in this repo: MIT. The AxiomSeal service itself is a
commercial SaaS (see [terms](https://axiomseal.com/terms)).
