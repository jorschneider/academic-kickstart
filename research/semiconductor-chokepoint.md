# China's Semiconductor & Compute Chokepoint

*The one domain where China still bends the knee — and is spending its way out. A map of where the PLA's compute base is dependent, where it's brute-forcing around the controls, and where it has quietly stopped depending at all.*

*Working draft — August 30, 2026. Part of the [China Defense-Industrial Atlas](https://claude.ai/code/artifact/ecc69e75-bcc3-46cf-a303-3b95f8ac9b4c); the compute layer also underlies the [drone/robot](./drone-robot-ecosystem.md) and [robot](./robot-ecosystem.md) ecosystems.*

---

## Why this is the "Dependent" domain — with an asterisk

Across the atlas, this is the single domain rated **Dependent**: China cannot yet make a leading-edge logic chip the way TSMC does, because it cannot buy or build an EUV lithography machine. That is real, and it is the tightest chokepoint the United States holds.

But "dependent" flattens a more interesting picture. China is simultaneously (1) **brute-forcing near-frontier logic** without EUV, at a cost and yield penalty it is willing to eat for strategic chips; (2) **rapidly localizing the rest of the toolchain** — etch, deposition, cleaning — where it has largely closed the gap; (3) **racing on memory**, including the HBM that gates AI accelerators; and (4) **locking up mature-node ("legacy") production** as a strategic base that the whole world will depend on. The dependency is narrowing to a handful of genuinely hard chokepoints. This document maps all four moves and names the chokepoints that remain.

The strategic stakes are the rest of the atlas: every domain where China leads — drones, robots, missiles, radar — runs on compute, and the PLA's AI-targeting and autonomy ambitions are downstream of whether Huawei can get enough good silicon. Export controls on this one domain are Washington's highest-leverage tool; the question this map answers is how much leverage is left.

---

## Layer 1 — Leading-edge logic: brute-forcing past EUV

- **SMIC (中芯国际)** is the whole story's fulcrum. Entity-Listed, it fabs Huawei's Ascend AI accelerators and Kirin SoCs on its **7nm (N+2)** process — functional, but with yields reported at [40–55% on complex dies](https://supplyics.com/insights/market-intelligence/china-logic-fabs-yield-geopolitical-risks-2026/). It is pushing a **5nm (N+3)** node into pilot production at ~20% yield, [targeting mass production in 2026](https://www.techpowerup.com/344000/chinese-smic-achieves-5-nm-production-on-n-3-node-without-euv-tools) for Huawei and Alibaba silicon, and has begun **3nm GAA** R&D aimed at a 2026 tape-out.
- **The catch — all of it without EUV.** Barred from ASML's extreme-ultraviolet scanners, SMIC prints these nodes with **193nm immersion DUV plus self-aligned quadruple patterning (SAQP)** — more mask layers, lower yield, longer cycle time. External estimates put SMIC's 5nm cost at **~50% above TSMC's** EUV 5nm. It works for strategic chips where cost is no object; it does not scale economically to consumer volumes. This is the precise shape of the dependency: not "can't," but "can't cheaply, at volume."
- **Huawei / HiSilicon** is the demand engine and system integrator behind the push — designing the Ascend line and willing to absorb SMIC's yield penalty because there is no alternative fab it can legally use.

## Layer 2 — Lithography: the master chokepoint

Lithography is where the dependency is deepest and least likely to close soon.
- **SMEE (Shanghai Micro Electronics, 上海微电子)** is China's national litho champion, and it is far behind: its most advanced production tool is a **~90nm** dry scanner, with a **28nm-class immersion SSA800** [still in testing rather than in a commercial fab](https://www.trendforce.com/news/2025/11/10/news-decoding-chinas-lithography-push-to-challenge-asml-from-sicarrier-to-alternative-euv-paths/). That is roughly a decade behind EUV.
- **The EUV moonshots are early and hype-prone.** Two domestic paths get attention — **steady-state microbunching (SSMB)**, an accelerator-based light source tied to Tsinghua with a test site at Xiongan, and Huawei/SMIC's **Localized Dynamic Patterning (LDP)** — but, as [CSIS cautions](https://www.csis.org/blogs/strategic-technologies-blog/breakthroughs-or-boasts-assessing-recent-chinese-lithography), generating EUV light is not the same as shipping a commercial scanner, and the gap is enormous. **SiCarrier (新凯来)**, the Huawei-linked toolmaker that made a splashy litho debut at SEMICON 2025, conspicuously sent only subsidiaries to the 2026 show — a tell that the litho program is not yet ready to be shown off.

## Layer 3 — The rest of the toolchain: quietly closing the gap

Away from lithography, China has localized fast:
- **NAURA (北方华创)** — the largest domestic equipment maker, with 2026 revenue [expected to top ¥50B](https://greathandshake.com/en/chinas-semiconductor-equipment-industry-how-naura-amec-and-domestic-toolmakers-are-closing-the-gap/) and an installed base of ~3,000 etch chambers; covers etch, deposition, thermal, cleaning, and ion implant.
- **AMEC (中微公司)** — plasma etch and CVD; its **Primo Angnova** ICP etcher targets logic at **5nm and below**, a genuine advanced-node capability.
- **ACM Research (盛美, Shanghai)** — wafer cleaning. Together the three form a "Big Three" with a [combined ~45–50% domestic share](https://greathandshake.com/en/chinas-semiconductor-equipment-industry-how-naura-amec-and-domestic-toolmakers-are-closing-the-gap/), already designed into SMIC, Hua Hong and YMTC lines. Etch localization is running **30–45%**, overall equipment self-sufficiency ~35% — and rising. Lithography is the lone laggard dragging the average down.

## Layer 4 — Memory & HBM: the AI-accelerator gate

High-bandwidth memory, not just logic, gates an AI accelerator — and it was cut off entirely in late 2024.
- **CXMT (长鑫存储)** — China's DRAM champion, now targeting **domestic HBM3 mass production by end-2026** (~30k HBM wafers/month) after US controls pulled foreign field-service engineers in December 2024. DRAM capacity is scaling from [~300k wafers/month (2025) toward ~500k (2028)](https://www.tomshardware.com/pc-components/dram/chinas-cxmt-and-ymtc-to-expand-memory-output). CXMT is the binding constraint on how many Ascend accelerators China can actually build, and it is racing to relieve itself.
- **YMTC (长江存储)** — the 3D-NAND champion (Xtacking architecture), Entity-Listed since 2022, now [closing on SK Hynix's NAND share](https://www.digitimes.com/news/a20260828VL214/nand-dram-technology-sk-hynix-cxmt.html) and standing up a **DRAM subsidiary** (¥20.7B, Sept 2025) plus joint HBM work with CXMT. Both are moving toward IPOs.

## Layer 5 — EDA: the other deep bottleneck

The design software almost no one outside the field thinks about, and the second-hardest chokepoint after litho.
- **Empyrean (华大九天)** — the domestic leader, claiming ~half the local market; full-flow analog (partial 5nm) and digital (full 7nm, advancing to 5nm), plus [China's first full-flow memory EDA](https://www.scmp.com/tech/article/3315237/chinas-top-player-empyrean-eyes-opportunities-us-chip-curbs-design-software). **Primarius (概伦电子)** and **Semitronix (广立微)** round out the top tier, and even SiCarrier has launched an EDA unit.
- **The gap that remains.** Domestic analog EDA is deployable at mature nodes (≥28nm); the **digital critical path — logic synthesis and physical implementation at advanced nodes — is the deepest bottleneck.** When Washington ordered Synopsys, Cadence and Siemens EDA to [halt China sales in May 2025](https://www.scmp.com/tech/tech-war/article/3313069/tech-war-chinas-top-three-eda-firms-under-spotlight-after-us-ban-chip-design-tools) (a cutoff reversed within weeks in the rare-earths truce), it exposed how much of China's advanced design still runs on three American companies' tools.

## Layer 6 — The compute payoff (and where it feeds the PLA)

All of the above exists to produce compute: **Huawei Ascend** accelerators (targeting ~600k 910Cs in 2026) and CloudMatrix systems, **Cambricon** (Entity-Listed, the domestic-substitution darling), and the CPU tier (**Loongson, Phytium**). This is the silicon that runs China's AI models — including the PLA experimentation with DeepSeek-class models on Ascend hardware noted in the [drone/robot map](./drone-robot-ecosystem.md) — and every autonomy, targeting, and swarm ambition elsewhere in the atlas is rate-limited by it. Not Nvidia parity, but, as with SMIC's 5nm, *enough for the strategic use case* even at a cost premium.

## Layer 7 — The legacy-node long game

The move most likely to matter for the world economy is at the *trailing* edge. Redirecting state capital after the 2022 EUV controls, Beijing poured the **$47.5B "Big Fund III"** (May 2024, nearly as large as its first two chip funds combined) into **mature-node ("legacy") capacity** — the ≥28nm silicon that runs cars, appliances, machine tools, base stations, grid controllers and most weapons. China's mature-node share has grown from [under a fifth of global supply to roughly a third](https://www.csis.org/blogs/trustee-china-hand/legacy-chip-overcapacity-china-myth-and-reality), heading toward ~33% of the legacy market by 2027, with 2026 chip exports up ~73%. The risk analysts flag is a **solar/LCD-style overcapacity price war** in 2026–27 that could hollow out foreign legacy fabs — turning a defensive localization drive into an offensive dependency the other way.

---

## The chokepoints that actually remain

Stripped of the noise, the genuine US/allied chokepoints on Chinese compute in 2026 are few but sharp:

1. **EUV lithography** — no domestic scanner; the alternatives (SSMB, LDP) are years from commercial. The master lock.
2. **Advanced digital EDA** — logic synthesis and physical implementation at ≤7nm still lean on Synopsys/Cadence/Siemens.
3. **HBM at scale** — CXMT's end-2026 HBM3 target is the swing variable for how many AI accelerators China can build.
4. **A few tool niches** — top-tier metrology, ion implantation, and some advanced deposition steps.
5. **The trailing dependencies inside the tools** — even NAURA's and AMEC's machines still contain some Western sub-components.

Everything else — 7nm logic, most etch/deposition/clean, DRAM/NAND, mature nodes, domestic AI accelerators — China now makes for itself, at a cost. The controls still bite where it counts; the surface they bite has shrunk to these five.

---

## Sources & further reading

- SupplyICs and TechPowerUp on [SMIC 5nm/N+3 yields and cost](https://www.techpowerup.com/344000/chinese-smic-achieves-5-nm-production-on-n-3-node-without-euv-tools); Semiecosystem (Mark LaPedus), "[Can China Make 5nm Chips?](https://marklapedus.substack.com/p/can-china-make-5nm-chips)"
- CSIS Strategic Technologies, "[Breakthroughs or Boasts? Chinese Lithography](https://www.csis.org/blogs/strategic-technologies-blog/breakthroughs-or-boasts-assessing-recent-chinese-lithography)"; TrendForce on the [SiCarrier / SMEE / EUV-alternative landscape](https://www.trendforce.com/news/2025/11/10/news-decoding-chinas-lithography-push-to-challenge-asml-from-sicarrier-to-alternative-euv-paths/)
- Great Handshake and TrendForce on the [NAURA / AMEC / ACM equipment breakout](https://greathandshake.com/en/chinas-semiconductor-equipment-industry-how-naura-amec-and-domestic-toolmakers-are-closing-the-gap/)
- Tom's Hardware on [CXMT HBM3 and CXMT/YMTC capacity](https://www.tomshardware.com/pc-components/dram/chinese-semiconductor-industry-gears-up-for-domestic-hbm3-production-by-the-end-of-2026-cxmt-to-produce-chips-while-naura-maxwell-and-u-preseason-design-tools-for-assembly); ChinaTalk, "[Mapping China's HBM Advancement](https://www.chinatalk.media/p/mapping-chinas-hbm-advancement)"
- SCMP on the [EDA firms (Empyrean, Primarius, Semitronix) and the May 2025 cutoff](https://www.scmp.com/tech/tech-war/article/3313069/tech-war-chinas-top-three-eda-firms-under-spotlight-after-us-ban-chip-design-tools)
- CSIS Trustee China Hand and Eurasia Review on [Big Fund III and legacy-node overcapacity](https://www.csis.org/blogs/trustee-china-hand/legacy-chip-overcapacity-china-myth-and-reality)
- SemiAnalysis on the [Huawei Ascend production ramp](https://newsletter.semianalysis.com/p/huawei-ascend-production-ramp); DoD CMPR (Dec 2025); Congressional Research Service, *U.S. Export Controls and China*

*Caveats: node names (SMIC "5nm/N+3") are marketing conventions, not TSMC-equivalent; yields and costs are external estimates and should be read as directional. Lithography claims (SSMB, LDP) are the most hype-prone in the whole atlas — treat unverified "EUV breakthrough" reports with heavy skepticism. A 2026 snapshot of the fastest-moving controls story in tech policy.*
