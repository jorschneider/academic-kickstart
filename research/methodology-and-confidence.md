# Methodology & Confidence: How to Read This Atlas

*Part of the [China Defense-Industrial Atlas](https://claude.ai/code/artifact/ecc69e75-bcc3-46cf-a303-3b95f8ac9b4c). Compiled from open sources through August 2026.*

Every other page in this atlas makes claims: China leads here, depends there, is catching up somewhere else. This page is about how much to trust those claims. It documents where the ratings come from, grades the confidence behind each one, and — most importantly — is honest about what open-source analysis structurally *cannot* see. An atlas that tells you China "leads in robots" without telling you whether that rests on customs data or on a single trade-press estimate is doing marketing, not analysis. The goal here is the opposite: to make the atlas's own epistemics legible, so a serious reader can discount the soft calls and lean on the hard ones.

The short version: **treat this as a well-sourced analytical synthesis, not a measurement.** The tier ratings are judgments a reasonable analyst could move up or down a notch. The confidence grades tell you which ones are worth arguing about.

---

## 1. What the atlas is built from

Everything here comes from open sources — no classified material, no proprietary datasets, no non-public interviews. That is a genuine limitation (see §4), but it is also what makes the atlas checkable: every load-bearing claim traces to a citation in the companion essays. The sources fall into four tiers of evidentiary weight.

**Tier 1 — Official and primary.** Government documents and disclosures that carry institutional accountability behind them:

- **DoD's** *Military and Security Developments Involving the PRC* (the annual "China Military Power Report," Dec 2025 edition) and the **Section 1260H** list of Chinese military companies (June 2026).
- **BIS Entity List** actions and the **Section 1237/NDAA** designations — these name specific firms with specific findings.
- **US Geological Survey** and **IEA** commodity data for rare earths, gallium, germanium and processing shares.
- **Commercial satellite imagery** (Planet, Maxar) as analyzed by FAS and the James Martin Center — the backbone of the nuclear-silo and shipyard-expansion findings.
- **Chip teardowns** by TechInsights — physical evidence of what SMIC and Huawei can actually fabricate, which is far harder to spin than a press release.

**Tier 2 — Specialist research institutions.** Analysts with domain depth and reputational stakes: CSIS (ChinaPower, the shipbuilding-capacity work), RAND, RUSI, IISS (*Military Balance 2026*), FDD, the Mercator Institute (MERICS), SemiAnalysis on the compute stack, and Kharon on corporate-network and sanctions-evasion mapping.

**Tier 3 — Trade press and industry trackers.** Defense and technology reporting, plus market-share estimates from firms like Morgan Stanley, Interact Analysis and TrendForce. Useful for the *shape* of a market, but the precise figures (a "97% share," an "80–90% of FPV motors") are private estimates with real error bars, not audited counts.

**Tier 4 — Chinese-language corporate and state material.** Company filings, procurement notices, patent records, and state-media coverage. Rich and often first-to-report, but the reporting incentive runs toward exaggeration (for commercial firms courting investment) or opacity (for anything genuinely sensitive).

A rating built mostly on Tier 1–2 evidence earns high confidence. One that leans on Tier 3–4 — a single tracker's market share, a state-media production claim — earns less, no matter how confident the number *sounds*.

---

## 2. The confidence grades

Each domain in the [scorecard](https://claude.ai/code/artifact/ecc69e75-bcc3-46cf-a303-3b95f8ac9b4c) carries a confidence grade — surfaced right in the row, next to the trajectory arrow. It answers a different question than the tier does. The **tier** says *where China stands*; the **confidence grade** says *how much you should trust that placement.* A domain can be rated Dominant with only moderate confidence (robots), or Dependent with high confidence (advanced semiconductors) — the two axes are independent.

**● ● ● — A · Well-documented.** The rating rests on Tier 1–2 evidence with independent corroboration, and the direction of any error is small. You could hand this to a skeptic and defend it. *Examples: advanced-semiconductor dependency (confirmed by chip teardown), shipbuilding dominance (leaked ONI capacity data via CSIS, plus hull counts), rare-earth-magnet leverage (USGS/IEA processing shares).*

**● ● ○ — B · Mixed evidence.** The broad rating is solid, but it blends documented fact with analytical inference, or the headline figure is a private estimate rather than an official count. Reasonable analysts will disagree on the exact tier. This is the honest grade for most of the atlas. *Examples: robots (leadership real, but the "~97% of humanoid shipments" is a tracker estimate), missiles/hypersonics (portfolio documented, but "ahead of the US" is a judgment about classified capability), nuclear (silos satellite-confirmed, warhead count a projection).*

**● ○ ○ — C · Largely inferential.** The rating rests on displayed-but-unproven capability, fragmentary reporting, or a specific claim that is exactly the kind of thing China conceals. Treat these as the atlas's working hypotheses, most exposed to revision. *Example: counter-UAS / directed energy — the systems appear at exhibitions (LY-1, Hurricane 3000), but combat reliability is unproven and the tier-3 placement is generous to displayed hardware.*

The distribution across the thirteen scorecard domains is deliberately uneven — roughly **four A, eight B, one C**. That is not false modesty: it reflects the real state of open-source knowledge. The hardest facts to hide (what a fab can etch, how many silos are in the desert, who processes the world's magnets) are documented and graded A. The things China most wants to obscure (warhead intent, weapon performance under fire, the true production rate of a specific engine) are graded B or C precisely because the reporting there is thinnest.

---

## 3. How the tiers were assigned

The scorecard's four capability tiers — Dominant, Competitive, Catching up, Dependent — are an **ordinal synthesis**, not a computed index. There is no weighted formula behind them; assembling one would imply a precision the evidence does not support. Instead each domain was placed by asking three questions and reconciling the answers against the source tiers above:

1. **Capacity** — can China build it *at scale*, on a wartime footing? (This is where it is strongest.)
2. **Frontier** — can China build the *best* version, at the technological frontier? (This is where it is weakest.)
3. **Autonomy** — can China build it *without foreign inputs* at a chokepoint? (This is the dependency column.)

A domain scores Dominant only when it clears all three — scale, frontier-competitive, and self-sufficient (shipbuilding, drones, the component/magnet layer). It scores Dependent when a single foreign chokepoint gates the whole domain (advanced semiconductors, gated by EUV). The middle two tiers are where most domains sit, and where the confidence grades matter most: "Competitive" and "Catching up" are genuinely contestable calls.

The **trajectory arrows** (⇈ rising fast · ↑ rising · → holding) are a separate, deliberately coarse judgment about the direction and speed of movement over roughly the next three to five years, drawn from the same sources. They are the softest layer in the atlas — a directional bet, not a forecast — and should be read as such.

---

## 4. What open source cannot see — the structural blind spots

This is the most important section, because it bounds everything else. Open-source analysis of the Chinese defense-industrial base has systematic blind spots, and honest use of this atlas means keeping them in view:

- **Performance under fire.** We can count platforms and read spec sheets; we cannot observe how systems perform in combat. A radar's exhibition claims, a missile's advertised range, a laser's demonstrated shoot-down — these are the *inputs* China controls most tightly. The counter-UAS domain is graded C for exactly this reason, but the caveat applies in softer form everywhere.

- **Depth of magazines and true production rates.** Wartime endurance turns on stockpiles and surge capacity — precisely the figures that are unpublished. We infer shipbuilding and munitions scale from yard imagery and industrial data, but the actual magazine depth (how many missiles, how many days of fire) is a genuine unknown, and it is decisive in the [Taiwan-contingency lens](https://claude.ai/code/artifact/14f256bd-9d68-4687-866e-054f89579299).

- **Intent and doctrine.** The atlas maps capability, not plans. Whether and how China would *use* what it builds is a separate question this corpus does not answer.

- **The classified frontier.** The most advanced programs — next-generation submarines, warhead design, space-based sensors — are the least visible. Where the atlas rates them, it is triangulating from budget signals, facility imagery, and analyst consensus, not direct evidence.

- **Survivorship and salience bias in the sources.** Firms that court investment (humanoid startups, commercial-drone makers) generate abundant coverage; quietly critical suppliers (a numbered institute making a specific alloy) generate almost none. The atlas actively hunts the second category — the "unheralded suppliers" of the original brief — but the source base tilts toward the loud, and some genuinely important nodes are certainly missing.

- **The snapshot problem.** Corporate structures, sanctions status and shipment figures are a 2026 snapshot of a fast-moving picture. The Entity List grows monthly; a firm's status can change between compilation and reading.

None of this makes the atlas unreliable — it makes it *bounded*. The findings graded A survive these blind spots; the ones graded B and C are where the blind spots bite hardest, which is exactly why they carry the caveat.

---

## 5. How to use it honestly

- **Lean on the A-grade findings.** The semiconductor dependency, the shipbuilding gap, the magnet leverage — these are as solid as open-source analysis gets. Build arguments on them.
- **Treat B-grade ratings as the consensus best-guess, and cite the underlying source, not this atlas,** when precision matters. Where it says "~97%," go to the tracker; where it says "ahead on hypersonics," go to the DoD report.
- **Read C-grade ratings as hypotheses.** They flag where China *claims* or *displays* a capability that has not been independently proven. They are the first place to look for the atlas being wrong.
- **Watch the trajectory arrows for direction, not magnitude.** A ⇈ means "this is where the picture is changing fastest," not "this will reach the next tier by year X."
- **Come back.** This is a living document. The confidence grades are as much a to-do list — where better evidence would change the picture — as a disclaimer.

---

*This methodology page is itself a claim, and the same standard applies: it describes the process actually used to build the atlas, and where the atlas's judgments are soft, this page says so rather than smoothing it over. Corrections and better sources are the point of an open, checkable corpus.*
