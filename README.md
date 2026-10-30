# DOME — The Commons Engine

> Nothing exists in isolation, and data is what makes the interdependence visible.

Every person, place, thing and idea is inherently plural, part of a larger whole. **DOME** is a sovereign data ecosystem that gathers everything a life generates — from heart rate, location and transactions to searches, posts, conversations, relationships and thought — and makes it whole.

**Its purpose is awareness.** When the parts of a whole can see themselves clearly, they understand their own needs, their value and their effect on others, for better or worse, and can govern themselves, democratically.

**It is also part of an economic engine.** Simply by existing, we generate value as data, and today others capture it. In DOME, agents turn that data into knowledge, services and goods, and every output keeps its lineage, so value returns to all who contributed: a dividend for being, not only for working. A path beyond compulsory work, overconsumption, greed and waste.

DOME continues more than a decade of work by [Jennifer Lyn Morone](https://jenniferlynmorone.com) — from *Jennifer Lyn Morone™ Inc.*, the artwork in which she incorporated herself and claimed her data as an asset, to RadicalxChange. What was once a provocation is now buildable.

---

## Architecture

```
                    MODELS  (one switchboard: frontier, open and local models,
                             plus a fast decision model for triage and safety)
                                          │
   ┌──────────────── PRIVATE ─────────────┴──────────── PUBLIC ────────────────┐
   │  Private agent ("the Brain")              Public agent ("the Face")       │
   │  works only with sovereign data           shares only what is chosen      │
   │  under strict, verifiable rules           never reaches private data      │
   │  every action gated before it runs                                        │
   └──────────────────────────┬────────────────────────────────────────────────┘
                              │  vertical harnesses: one job each, proven by evals
                              │
   INGEST ──► LIBRARY ──► GRAPH ──► LENSES ──► LINEAGE ──► VALUE
   every      one object  people ·   every      who and     knowledge,
   trace of   per item,   places ·   discipline, what        services and
   a life     fingerprint- things ·  tradition   contributed goods; value
              addressed   ideas ·    and way of  to each     returns to all
                          consent    knowing     output      who contributed
```

**Principles**

- **Sovereign by default.** Private material is encrypted by its owner and read only by agents under the owner's rules. Public material is shared deliberately.
- **Provenance is sacred.** True creation dates are kept, and every item is labelled as original work, a conversion or AI-generated.
- **Relational, not individual.** The graph holds people, places, things and ideas as relationships, never as isolated records.
- **Consent before connection.** Other people in the data are recognised and asked, not assumed.
- **Proof over claims.** Every agent job has written acceptance checks, and an agent's report of success is not evidence of success.
- **Open lens space.** Interpretation is not limited to a fixed list. Any discipline, tradition or way of knowing can be applied where it illuminates.

---

## Status

Labels follow a simple honesty rule: nothing is called done until it has been run and checked.

| Part | Status |
|---|---|
| Archive fingerprinting, deduplication and cataloguing across drives | ✅ Implemented and verified (prototype) |
| Base extraction of entities and true dates from notes (local models) | ✅ Implemented (prototype) |
| Lens registry and per-lens agent design | 📝 Designed; per-lens agents in progress |
| Encrypted offsite backup with tested restore | ✅ Implemented and verified |
| Content-addressed library (one object per item) | 🔧 Being built |
| Private and public agents, decision-model gating, model routing | 🔧 Being built |
| Knowledge graph of relationships, consent and lineage | 📝 Designed |

## Still to design

These are open problems, named honestly rather than presented as finished plans:

1. **Consent and identity:** how everyone who appears in the data is recognised, asked and given control.
2. **Attribution and payment rails:** how lineage becomes actual value, and in what form a dividend is paid.
3. **Collective governance:** how the parts of the whole decide together.
4. **Data-intake connectors:** health, finance, location, search and social sources.
5. **Privacy-preserving shared compute:** creating shared value from data without the raw data leaving its owner.

---

## Built with

Python · local models via Ollama · Obsidian · Git · n8n · Neo4j · Hermes Agent · OpenRouter · Jev · Backblaze B2 · restic · Tailscale · Claude Code

---

*This repository describes the project. The working code and all personal data remain private by design.*
