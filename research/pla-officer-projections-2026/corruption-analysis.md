# Reading the Purge: what corruption announcements do and do not tell you

Companion to [`README.md`](README.md) §6 and [`purge-tracker.md`](purge-tracker.md). The main report gives the corruption *findings*; this file gives the *inferential machinery* behind them — why the obvious reading of the purge record is wrong, and what can be extracted instead.

---

## 1. The inference problem

The intuitive reading of the PLA purge is: *the state announced that General X violated discipline, therefore General X was corrupt.* This is unsafe, and understanding why is the difference between analysis and stenography.

### 1.1 The conditional is backwards

Observers reason from *purged* to *corrupt*. But the quantity the announcement actually licenses is P(purged | corrupt), while the quantity people want is **P(corrupt | purged)**. These diverge sharply when the base rate of corruption is high and enforcement is selective — exactly the PLA's situation.

Model an officer's probability of being purged as a function of three variables:

> **P(purged) = f( guilt, network exposure, current utility to the leadership )**

- **Guilt** — whether the officer took or paid money. On the documented record (see §2), among officers who held procurement, construction, logistics, or cadre-selection authority between roughly 2012 and 2023, this variable appears close to **saturated**: the promotion market was institutionalized under Guo Boxiong and Xu Caihou, and the regime's own 2024 charging language against Li Shangfu — that he both *took* bribes (受贿) and *paid* them (行贿) — is an admission that even the head of the equipment system had to buy his own position from someone.
- **Network exposure** — whose client the officer is. Highly variable.
- **Utility** — whether the officer is currently needed (Dong Jun's diplomatic indispensability; Zhang Shengmin's role as chief enforcer).

**When one variable is saturated, it explains almost none of the variance in outcomes.** If nearly everyone in the eligible pool is technically chargeable, then who actually gets charged is determined by network and utility. That is the formal reason the purge record is a far better measurement of **political alignment** than of **criminality**.

### 1.2 Three corollaries that matter for forecasting

1. **Survival is not exculpatory.** An officer still standing in 2026 is best explained by being unaffiliated, useful, or not yet reached — not by being clean. This is why the report's §6.3 register rates *exposure* (a fact about their career) separately from *political risk* (a judgment about network and utility). Conflating them is the standard error in this genre.
2. **Purging is not proof.** Some fraction of the fallen are guilty of nothing more than the wrong patron. The report names no serving officer as corrupt for exactly this reason.
3. **The campaign structurally cannot end.** An always-available, always-valid charge is an instrument of control, not merely a remedy for a problem. Ending the campaign would forfeit the instrument. This predicts — and the record confirms — that enforcement recurs in the same systems rather than resolving them: the Rocket Force was purged in 2023 and again in 2025–26; the Equipment Development Department lost two consecutive directors; the political-work department was decapitated twice. **"Why didn't the first purge fix it?" is the wrong question.** The purge is not a repair mechanism.

### 1.3 What *is* recoverable from the record

Three things, reliably:

- **Which systems generate rents** — revealed by where enforcement concentrates (§2 below and README §6.2).
- **Which networks are being dismantled** — revealed by the co-timing of removals (the October 2025 nine; the June 2026 six).
- **What the leadership currently fears** — revealed by charge *language*, which is where §3 comes in.

---

## 2. The rent map, from the enforcement record

Ranking the PLA's rent-bearing systems by revealed enforcement intensity, 2023–2026 (counts from [`purge-tracker.md`](purge-tracker.md)):

| Rank | System | Senior figures actioned | Why the rents exist |
|---|---|---|---|
| 1 | **Political-work / cadre selection** | ~13 | Controls promotion. In a system where rank was demonstrably purchasable, the PWD *is* the marketplace — and its custodians are the market makers |
| 2 | **Armaments & procurement (EDD + service equipment depts + SOE primes)** | ~10 | Monopsony buyer, classified budgets, no external audit, prices negotiated with a handful of state primes. **Every director the Equipment Development Department has ever had — Zhang Youxia, Li Shangfu, Xu Xueqiang — has been purged**, and its political-commissar billet has stood empty since April 2019: the buyer of every Chinese weapon system has gone seven years without its designated internal watchdog |
| 3 | **Rocket Force** | ~8 (+3 reported) | Absorbed the largest concentrated capital programme in PLA history (silo fields, solid-motor production); construction plus secrecy is the maximal-graft combination |
| 4 | **Theater/operational command** | ~9 | Not intrinsically rent-rich; enforcement here tracks *network*, not money — see §3 |
| 5 | **Logistics & infrastructure (LSD, JLSF)** | ~6 | Land, housing, food, fuel, medical: high-volume, low-visibility |
| 6 | **Internal security (PAP)** | 2 | Loyalty-critical rather than rent-rich; zero tolerance for ambiguity |

The ordering itself carries information. Systems 1–3 and 5 are where the money is; system 4's presence in the table at comparable volume is the tell that this campaign is **not only** about money.

---

## 3. A charge-language decoder

Chinese Communist Party disciplinary announcements are formulaic, and the formula varies in ways that are informative. Party discipline is enumerated in a conventional order — **political discipline (政治纪律), organizational discipline (组织纪律), integrity discipline (廉洁纪律), and so on** — and practitioners have long noted that *what is listed first, and whether money is quantified*, signals what the case is really about.

Applying that to the PLA record produces four tiers:

### Tier A — Quantified financial case (money is the substance)
*Markers:* a named criminal charge (受贿罪 bribery), an amount or the formula 数额特别巨大 ("exceptionally large amounts"), and ultimately a published court verdict.
*Examples:* **Tan Ruisong** (AVIC) — bribery of ~RMB 613 million, plus embezzlement and insider trading, published verdict, suspended death sentence March 2026. **Wei Fenghe** and **Li Shangfu** — bribery convictions, suspended death sentences May 2026.
*Reading:* the state is willing to have this case understood as theft. Financial detail is a costly signal — it invites scrutiny of how the money moved and who else touched it — so its presence suggests the money really is the point, or at least that the regime is content to have it seen that way.

### Tier B — Duty-crime formula, no adjudication yet
*Markers:* 涉嫌严重职务犯罪 ("suspected serious duty-related crimes"), 数额特别巨大, referral to the military procuratorate — but no trial or verdict published.
*Examples:* the **nine generals expelled 17 October 2025** (He Weidong, Miao Hua, He Hongjun, Wang Xiubin, Lin Xiangyang, Qin Shutong, Yuan Huazhi, Wang Houbin, Wang Chunning).
*Reading:* the case is being processed on a financial theory, but the specifics are being withheld. Note the elapsed time: expelled October 2025, and as of August 2026 — ten months on — **no public trial**, whereas Li Shangfu and Wei Fenghe went from expulsion to sentence in ~23 months with the verdict published. If the October 2025 cohort's verdicts appear on a similar clock, expect them from roughly **mid-2027**; if they never appear, that silence is itself evidence the cases were not primarily financial.

### Tier C — Political-loyalty language (money is the vehicle, not the substance)
*Markers:* political discipline foregrounded; loyalty formulations rather than amounts. The strongest markers in the record: **"betrayed the trust of the party"** and **"severely trampled on and damaged the CMC Chairman responsibility system" (严重践踏破坏军委主席负责制)**. Also diagnostic: Li Shangfu's expulsion listed *political* discipline first, before organizational and integrity discipline, and accused him of having "polluted the political ecology of the military equipment sector" — a phrase about the system, not the sum.
*Examples:* **Zhang Youxia** and **Liu Zhenli** — the January 2026 announcement used only the vague 涉嫌严重违纪违法 with **no monetary language at all**, and the accompanying PLA Daily commentary went to loyalty.
*Reading:* **this is the most important tier for the projections.** When the state removes its two most senior operational officers and declines to allege theft, the charge is about control of the gun. It also means the officers who replace them are being selected against a *loyalty* specification, which is precisely what §2.5 of the main report observes in the promotion pattern.

### Tier D — Silence (the officer vanishes; nothing is ever said)
*Examples:* **Hu Zhongming**, **Chang Dingqiu**, **Wang Qiang**, and the theater commanders who disappeared in the September–October 2025 sweep.
*Reading:* genuinely ambiguous, and the report treats it as such. Silence covers (i) cases too damaging to announce, (ii) cases still maturing toward Tier B or C, and (iii) *non-purges* — illness, quiet retirement, reassignment — which produce an identical signature. The timing model in [`forecasting-model.md`](forecasting-model.md) §1 exists to discipline this tier: officers who stay silent well past the median 6–11 month lag (Hu Zhongming is the standout) become progressively more likely to belong to category (iii).

### Why the decoder is useful

It converts an undifferentiated list of "purged generals" into a claim about **motive mix**, and it is falsifiable: if the October 2025 cohort eventually receives published financial verdicts, Tier B was genuinely financial; if Zhang Youxia is eventually charged with a large bribery sum, Tier C collapses into Tier A and the "loyalty purge" reading weakens considerably. Both are checkable within the horizon of this report.

---

## 4. What the corruption record implies for the succession projections

Four transmission channels from graft to leadership outcomes:

1. **It sets the eligible pool.** Officers who rose through the rent-bearing systems in the 2012–2023 window carry latent liability. Officers who rose through *watching* institutions — discipline inspection, staff bureaus, training and test establishments — carry less. This is the mechanical reason the report finds enforcer-lineage and staff-lineage officers ascendant: they are the largest chargeable-proof pool, not necessarily the most capable one.
2. **It sets the tempo of vacancy creation.** Purges, not retirements, are now the principal mechanism of elite circulation, which is why the report pairs every seat-based projection with an attrition estimate.
3. **It transfers institutional power to the auditors.** Every cycle strengthens the discipline apparatus relative to the operational chain — the single clearest structural trend in the 2024–2026 record, and the basis for the prediction that a discipline-lineage officer holds a CMC seat after the 21st Congress.
4. **It creates a specific future risk for today's risers.** The officers this report ranks highest — Zhang Zheng, Zhu Chuansheng, Dai Mingmeng, Wang Gang — are about to inherit *service- and department-level signing authority* over procurement for the first time. Their exposure is not historical; it begins now. On the record of their predecessors, that is the moment the clock starts.

---

## 5. Limits of this analysis

- **No independent verification.** Everything rests on what the Chinese state chose to announce, plus press reporting about it. There is no audit trail, no discovery, no defence case in the public record. Even the published verdicts (Wei Fenghe, Li Shangfu, Tan Ruisong) are summaries released by the court, not documents.
- **Selection on the dependent variable.** The rent map in §2 is built from officers who were *caught*, which measures enforcement priorities as much as underlying corruption. A system with high graft and no enforcement would appear clean here — a real possibility for parts of the naval shipbuilding programme, which is precisely why the report flags it as the likeliest next target rather than as currently clean.
- **The decoder is a heuristic, not a law.** Charge language reflects drafting conventions and audience management as well as substance, and the conventions can change.
- **Nothing here identifies any serving officer as corrupt.** The exposure ratings in README §6.3 are statements about career position and network, published as forecasting inputs, and should not be read as allegations.
