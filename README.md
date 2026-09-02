## Matt Price

I build systems that know what they don't know.

Fifteen years between the business and the data — regulatory reporting,
attribute-level lineage, requirements that survive an audit. Now also the person
who builds the tooling.

**Most of my repositories are private.** The work below is real and running; the
source stays closed. Live demos and write-ups at **[rmprice.co](https://rmprice.co)**.

---

### Shipped since June 2026

| | |
|---|---|
| **[TrackRecord](https://www.thetrackrecordapp.com/)** | Personality analysis from listening history |
| **[Constellations](https://rmprice.co/constellations/)** | Cinematic universe graph explorer |
| **[LedgerLamp](https://www.ledgerlamp.com/demo/)** | Household credit and cashflow, deterministic rules engine |
| **[BuildWise](https://rmprice.co/buildwise/)** | 3D-printing advisor over a retrieval corpus |
| **[BallisticLens](https://www.ballisticlens.com/welcome.php)** | Computer-vision target scoring |
| **[TailTrackerAI](https://tailtrackers.org/)** | Animal shelter management (pro bono) |

Plus two private systems: a code and data-lineage engine, and a research
collaboration with another engineer.

Roughly 290,000 lines and 1,450 commits across the set.

---

### How I build

**Abstention is a feature.** These systems return *"could not evaluate"* as an
answer distinct from *"nothing found"*. Conflating the two is how a tool quietly
poisons every decision downstream of it.

**Measured, not asserted.** BallisticLens's scoring gate is measured at 0.949
precision / 0.758 recall against a labelled set, replacing a prior approach at
0.939 / 0.313 — better on both, which is why it wasn't a tradeoff. Thresholds
are derived from physical constraints rather than fitted to the data that
happens to be in front of them.

**Tests that bite.** Model behaviour is verified against recorded real API
responses rather than stubs, so the output contract is checked against what a
model actually says instead of what a mock was written to return.

**I design the system and the verification; an LLM writes much of the
implementation.** I own whether the result is correct.

---

### Background

SQL developer, business analyst, then senior product delivery associate at a
global bank — regulatory reporting, attribute-level lineage across platform
migrations, and an internal guardrailed LLM tooling platform that teams across
the org adopted for use cases it wasn't built for.

Interested in remote work where the analyst also builds the tooling.

📍 Dallas–Fort Worth · [rmprice.co](https://rmprice.co) ·
[LinkedIn](https://www.linkedin.com/in/rm-price/)
