# Reading the Purge: what corruption announcements do and do not tell you

Companion to [`README.md`](README.md) §6 and [`purge-tracker.md`](purge-tracker.md). The main report gives the corruption *findings*; this file gives the *inferential machinery* behind them — why the obvious reading of the purge record is wrong, and what can be extracted instead.

Two further companions carry the material this file rests on. [`corruption-casebook.md`](corruption-casebook.md) is the **evidentiary floor**: every case where charge language, method, amount or sentence is actually public, plus an explicit list of the mechanisms that have *never* been prosecuted. [`why-purges-recur.md`](why-purges-recur.md) is the **structural account**: why fourteen years of enforcement has not worked, what the military audit organ can and cannot do, and what the spending numbers do and do not support. Where a claim below is traceable to a specific adjudicated case, the casebook is where to check it.

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
3. **The campaign structurally cannot end.** An always-available, always-valid charge is an instrument of control, not merely a remedy for a problem. Ending the campaign would forfeit the instrument. This predicts — and the record confirms — that enforcement recurs in the same systems rather than resolving them: the Rocket Force was purged in 2023 and again in 2025–26; the Equipment Development Department has lost every director it has ever had; the political-work department was decapitated twice. **"Why didn't the first purge fix it?" is the wrong question.** The purge is not a repair mechanism.

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

## 2A. The mechanism: how PLA corruption actually works

The rent map above says *where*. This section says *how* — and its central finding is that the two largest rent systems are not separate.

### 2A.1 The circuit: procurement and office-selling are one market

The single most analytically important charge in the entire corpus is the one laid against **Li Shangfu** at his expulsion in June 2024. He was charged with **both** 受贿 (taking bribes) **and** 行贿 (*giving* them) — and separately with having "sought personnel benefits **for himself and for others** in violation of the rules" (违规为本人和他人谋取人事利益).

Read those together. As director of the Equipment Development Department, Li was the monopsonist *buyer* of Chinese weapons: taking money from suppliers is the expected direction of flow. The only plausible market in which such a man is himself a *payer* is **his own career**. The two counts in combination describe an officer who **bought his own advancement with money extracted from the procurement system**.

That makes procurement graft and office-selling **not two mechanisms but one vertically integrated circuit: rents enter at the contract and exit at the appointment.** And it is not an anomaly — the same both-directions pattern was charged against **Fang Fenghui**, **Zhang Yang**, and **Gu Junshan** (whose indictment was amended *during trial* to add the offering-bribes count).

The Party said as much in Li's verdict language: he "severely polluted the political ecology of the military equipment domain **and the ethos of the industry sector**" — an explicit statement that the contamination crossed from the uniformed acquisition organ into the defence industry.

**This is why purging one system never works.** Cut the procurement end and the promotion market still prices appointments; cut the promotion market and the procurement rents still need somewhere to go. It also explains the otherwise puzzling sequencing in [`purge-tracker.md`](purge-tracker.md): the campaign moved from the Rocket Force and the Equipment Development Department (2023–24) to the Political Work Department and the service political commissars (2024–25). It was following the money upstream.

### 2A.2 Why the Political Work Department sits at the centre

The structural fact: in the PLA, officer appointment, evaluation and promotion are **political work**, not personnel administration. They run through the political-officer chain. The CMC Political Work Department's **Cadre Bureau (干部局)** manages appointments, transfers and promotions, and every unit at regiment level and above is headed by a paired commander and political commissar, with the commissar responsible for personnel decisions.

And until the 2016 reform, **the military's disciplinary organ sat inside the same department it was meant to police**. Xu Caihou ran both in sequence: secretary of the CMC Discipline Inspection Commission (2000–02), then head of the General Political Department (2002–04), then CMC vice chairman. *The man who priced promotions had previously run the body meant to police the pricing of promotions.*

The regime's current language names the problem. The five-part rectification agenda set out in PLA Daily in October 2025 lists **整顿用人 — "rectify the employment of personnel"** — second of five, immediately after ideology. That is the Party's own term for office-selling.

### 2A.3 What a promotion cost

**There was no published tariff, and analysts should be sceptical of the ones in circulation.** What the record actually supports:

- **No CCDI notice, procuratorate finding or court verdict has ever published a per-rank price schedule.** None.
- The procuratorate's finding on Xu Caihou uses the standard office-selling formula: he "used the convenience of his office to **provide assistance for others' promotion in post**, and accepted bribes **directly and through family members**, in a particularly enormous amount." The same construction recurs in Guo Boxiong's verdict.
- Pricing appears to have been **competitive rather than fixed**. Reporting sourced to named PLA figures describes one officer offering RMB 10 million for a higher rank and a second outbidding him at RMB 20 million, with the first arrangement annulled. Major General Yang Chunchang, who had worked for Xu, described the decision criteria in order: "first, see how much money is involved, second, his personal affinity to them, and third … emotions and feelings."
- **The only judicially established figure in the public record is not for a star but for protection:** in January 2012, with his own case closing in, Lieutenant General **Gu Junshan paid Xu Caihou RMB 40 million** to save himself. Xu took it knowing he could not.
- Tariff tables for 少将 / 中将 circulating in Hong Kong and diaspora media have **no traceable documentary basis** and are mutually inconsistent across outlets — which is itself diagnostic. **[RUMOR]**

The defensible formulation: *promotions were sold; the price was set case by case by competitive bidding rather than by a published schedule; and the only court-established figure is the RMB 40 million Gu Junshan paid for protection.*

### 2A.4 How the money moved

Four documented channels:

1. **Through family members** — this is in the charge language itself (直接和通过家人收受贿赂). The family is not an accessory; it is the payment rail.
2. **Physical cash, warehoused and labelled.** Investigators reportedly removed **over a tonne of currency** from Xu Caihou's Beijing residence, along with jade, antiquities and precious hardwoods — twelve military trucks' worth. The detail that matters analytically: much of the cash was still in boxes **marked with individual officers' names**. Boxes labelled by payer are a **ledger**. They imply payments were tracked and sequenced, not received as one-off gifts. **[REPORTED]**
3. **Fee-for-intervention from the civilian economy** — the military selling administrative protection to businessmen. **[REPORTED]**
4. **Family businesses monetising the office indirectly.**

### 2A.5 Why weapons procurement is the ideal target

Elliot Ji's account identifies a "corruption sweet spot" with three components, and the second is the one non-specialists miss:

1. **Abundant funding under monopoly.** State-owned primes, rapidly growing budgets, no competitive discipline.
2. **Strategic systems are almost never used, so defects are never discovered.** US Minuteman IIIs are test-launched regularly; the DF-41 has been tested roughly 7–10 times since 2012, the DF-5 only a handful of times since 2000. **Deterrent weapons work by *perceived* readiness — which makes them the perfect thing to sell defectively, because nobody ever checks.**
3. **The quality gate is a single buyable official.** The PLA embeds **军代表 (military representatives)** inside manufacturers to certify quality. China's own *Legal Daily* warned as early as 2012 that some military representatives were taking money from the firms they were certifying.

Internal PLA audit research — by researchers at the CMC Audit Office and the Naval University of Engineering — documents two concrete fraud typologies: **围标/串标** (contractors consulting beforehand to rig bid prices) and **collusion between suppliers and PLA personnel or tendering agencies to exclude competing bids**. One audit found a unit's communications-equipment purchase priced **RMB 2 million above actual cost**. Post-award, contractors "neglect to deliver goods on time or fail to meet the agreed quantitative and qualitative standards" — so the PLA pays more for worse equipment while honest firms lose share.

A rare published enforcement action shows the reach: in **August 2024 the PLA's procurement network barred three universities** — Xi'an Technological, Xi'an Jiaotong and Southwest Jiaotong — **from Rocket Force procurement until 2027** for collusive bidding. The fraud extends into the university R&D layer, not just the SOE primes.

### 2A.6 The tell in the July 2023 tip-line

In July 2023 the Equipment Development Department solicited public tips on procurement irregularities — **covering violations back to October 2017**.

That date is not arbitrary. October 2017 is when **Li Shangfu** took over the department. The scoping implicated him while **conveniently excluding his predecessor**, who ran the armaments system from 2012 to 2017: **Zhang Youxia**, Xi's oldest military ally.

**The scoping was itself a political act — and it did not hold.** Zhang Youxia was placed under investigation on 24 January 2026 and stripped of his CMC posts on 28 August 2026. Whatever protection the 2017 cut-off was meant to provide expired in about thirty months. For a report about *who survives*, that is the most instructive single fact in the corruption record: a boundary drawn around the paramount leader's closest military associate lasted less than three years.

### 2A.7 What showed up in the hardware

Handle this tier carefully — the most-quoted claims are journalism sourced to unnamed intelligence assessments, not adjudicated findings.

- **[REPORTED]** US intelligence assessments relayed in January 2024 described "mishandling of missile fuel and silo lid malfunctions that could prevent the launch of intercontinental ballistic missiles" — popularly rendered as missiles filled with water and silo doors that would not open. The water formulation is a press rendering, not an official finding.
- **[OFFICIAL]** The failure mode is nonetheless real and self-documented: in 2005 *PLA Daily* praised a missile brigade commander for **refusing delivery of silo lids** because one would not open, the product being too heavy.
- **[OFFICIAL]** DoD's 2024 report links the Rocket Force dismissals to "fraud cases involving the construction of underground silos" — and assesses that the investigation "likely resulted in the PLARF repairing the silos, which would have increased the overall operational readiness of its silo-based force."
- **[OFFICIAL]** DoD's 2025 report goes further, attributing to procurement corruption "**malfunctioning lids installed on missile silos**" and "possibly the **pier-side sinking of the PLAN's first Zhou-class submarine** as it prepared for sea trials."
- **[OFFICIAL]** In March 2024 CMC Vice Chairman **He Weidong** told an NPC delegation the CMC would crack down on **"fake combat capabilities" (假战斗力)**. He was expelled nineteen months later.
- **[REPORTED]** SIPRI's Nan Tian records that corruption allegations led to major arms contracts being postponed or cancelled in 2024, with revenue drops at Chinese defence firms — the clearest market-observable trace of the campaign.

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
- **The scale is unmeasured and, on present disclosure practice, unmeasurable.** No PLA verdict since Wang Shouye's in 2006 has published an amount; the CMC Audit Office publishes no reports, no results bulletin and no recovery figures; and the only official breakdown of what the defence budget is spent on stops at 2017. Any aggregate estimate of PLA graft an analyst encounters — including the widely-quoted “half the military budget” figure, which traces to a 2014 panel discussion and has no documentary basis — is an extrapolation from roughly nine published data points. What *is* measurable is direction ([`why-purges-recur.md`](why-purges-recur.md) §4.5).
- **Nothing here identifies any serving officer as corrupt.** The exposure ratings in README §6.3 are statements about career position and network, published as forecasting inputs, and should not be read as allegations.
